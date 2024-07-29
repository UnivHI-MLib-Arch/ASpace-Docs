# Notes on the present status of UHML's ASpace implementation

## As of: August 2024

Current AS version: 3.4.1

Last version update: July 2024 (a double upgrade, first from v. 2.5.1 to v. 2.7.1, and then from there to 3.4.1)

### Known issues lingering from last update

- PUI Logo placement: Logo should be on the top left corner of the screen, not the top right.
  - Negligible, to be fixed if/when time permits
- Page numbers in table of contents for printed PDF finding aids out of alignment
  - ![ASpace-PrintedPDFFindingAid-issue-2024](https://github.com/user-attachments/assets/7603dcba-7b89-4425-9be6-a5f64f4dcaee)
  - (NB: this issue comes from a PUI-generated pdf finding aid printout)
  - Minor, to be fixed if/when time permits
- PUI Logo link functionality: Logo should act as link back to the library home page, but it is not doing so.
  - Minor, to be fixed in next development cycle or as time permits
- PUI: When searching within a collection by date, not all records are surfaced and they don't always sort properly
  - Due to dates having been entered as Date Expressions (which are not machine-readable) rather than as specific Begin/End dates (which are).
  - Moderate, can be fixed by data remediation (e.g. installing and running the timewalk plugin) and by better data-entry practices going forward
  - NOTE: Since the issue is caused by dates being entered in the Date Expression field instead of as normalized dates, it affects all searching / sorting / filtering by date or date range, in both the PUI and the SUI.  (As a result it may be a good idea to bump this up from 'moderate' to 'major' and/or to prioritize testing and installing the Timewalk plugin...)
- Keyword search results:
  - Unlike past versions of ASpace, searches for keywords that include terms that are part of collection titles--e.g. 'inouye' or 'saiki'--no longer bring up *all* archival objects and digital objects that are linked to the parent resource record. That is, being a child object of a resource record with the term in the title is no longer by itself considered 'relevant'; instead the search term(s) must appear somewhere within the child object itself in order for the object to be included as part of the results set.
  - Moderate, to be worked-around / explained in user-facing help materials
- Keyword search results:
  - The ways that the solr indexes are constructed for the PUI and SUI have changed considerably since v.2.5.1; in the past the two indexes were fairly independent, and changing the solr parameters in ASpace's config.rb file (to boost certain records higher in the listing than they would otherwise appear) would affect one but not the other.  Now, it seems that changing these parameters affect both indexes, but not to the same degree (i.e. the SUI seems much more sensitive than the PUI). This seeming inbalance is currently creating a situation where improving the relevancy of the search result set rankings in the SUI makes the PUI result set rankings worse, and vice-versa.
  - Relatedly, searches in the SUI and in the PUI return more or less the same set of records overall--minus things like unpublished and/or suppressed records, which don't show up in the PUI--but the order of results is almost never the same.
    - Major, to be addressed in next development cycle

### Major changes between current production version (3.4.1) and previous production version (2.5.1)

Note: The list below includes only select highlights; for considerably more information on bug fixes, new features, etc., see [the official ArchivesSpace release notes page](https://github.com/archivesspace/archivesspace/releases). (And scroll to find the notes for a specific release.)

Also nb: remember to link to corresponding section of [the ASpace Help Center](https://archivesspace.atlassian.net/wiki/spaces/ArchivesSpaceUserManual/overview) throughout (in addition to linking to relevant sections of the staff manual).

- Changes in how language information is recorded in various records (especially Resources, but also Accessions, Archival Objects, and Digital Objects)
  - ... [overview of changes]
  - ... [default now set to English language /Latin script]
  - ... [link to staff manual section re: how to override these defaults]
- Importing / uploading spreadsheets is now part of the core code (instead of a plugin)
  - ... [link to part of staff manual with instructions for uploading data via spreadsheet, and to wherever (library intranet?) users can get the new blank spreadsheet templates] (short term/temporary location: folder in Leilani's google drive)
  - ... [link to relevant section of ASpace Help Center User Manual]
  - ... [link to relevant videos in ASpace Help Center]
- Greatly expanded Agent records, plus introduction of a new, 'light mode' for agents that mimics previous functionality
  - ... [overview of changes, including added fields, enhanced merging, etc.]
  - ... [full mode vs. light mode]
  - ... [agent record permissions ...]
  - ... [link to relevant section of ASpace Help Center User Manual]
  - ... [link to relevant videos in ASpace Help Center]
- Various Digital Object improvements
  - ... [overview of new functionality: "make representative" feature now works, can now spawn DO description from a linked Resource, AO, or accession, etc.]
  - ... [link to staff manual section re: digital objects]
  - ... [link to relevant section of ASpace Help Center User Manual]
  - ... [link to relevant videos in ASpace Help Center]
- Ability to set individual preferences for search/browse column order, default note order, default note text, etc.
  - ... [overview of changes]
  - ... [overview of current defaults]
  - ... [link to staff manual section re: how to override these defaults]
- New reports page with additional report options
  - ... [link to staff manual section re: reports]
  - ... [link to relevant section of ASpace Help Center User Manual]
  - ... [link to relevant videos in ASpace Help Center]
- Top container management improvements
  - ... [overview of new functionality: top container merge, top container csv export, etc.]
  - ... [link to staff manual section re: container instances]
- Other assorted changes
  - Accession records can now be linked to individual Archival Objects (no longer just to Resource records) ... [link to staff manual section]
  - Users can update their own SUI passwords ... [link to staff manual section]
  - Can now import subjects via csv upload ... [link to staff manual section]
