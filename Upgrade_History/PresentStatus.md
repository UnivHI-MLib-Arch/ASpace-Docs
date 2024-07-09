# Notes on the present status of UHML's ASpace implementation

## As of: August 2024

Current AS version: 3.4.1

Last version update: July 2024, from v. 2.5.1

Known issues lingering from last update:

- PUI Logo placement: Logo should be on the top left corner of the screen, not the top right.
  - Minor, to be fixed if/when time permits 
- PUI Logo link functionality: Logo should act as link back to the library home page, but it is not doing so.
  - Moderate, to be fixed in next development cycle or as time permits 
- Keyword search results:
  - Unlike past versions of ASpace, searches for keywords that include terms that are part of collection titles--e.g. 'inouye' or 'saiki'--no longer bring up *all* archival objects and digital objects that are linked to the parent resource record. That is, being a child object of a resource record with the term in the title is no longer by itself considered 'relevant'; instead the search term(s) must appear somewhere within the child object itself in order for the object to be included as part of the results set.
    - Moderate, to be worked-around / explained in user-facing help materials 
- Keyword search results:
  - The ways that the solr indexes are constructed for the PUI and SUI have changed considerably since v.2.5.1; in the past the two indexes were fairly independent, and changing the solr parameters in ASpace's config.rb file (to boost certain records higher in the listing than they would otherwise appear) would affect one but not the other.  Now, it seems that changing these parameters affect both indexes, but not to the same degree (i.e. the SUI seems much more sensitive than the PUI). This seeming inbalance is currently creating a situation where improving the relevancy of the search result set rankings in the SUI makes the PUI result set rankings worse, and vice-versa.
  - Relatedly, searches in the SUI and in the PUI return more or less the same set of records overall--minus things like unpublished and/or suppressed records, which don't show up in the PUI--but the order of results is almost never the same.
    - Major, to be addressed in next development cycle
