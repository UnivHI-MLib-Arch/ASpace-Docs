# Section IV Part A: Creating Accession Records

**[incomplete draft outline; what steps are present are not necessarily in order]**

*[Throughout: remember to also explain how to spawn records from other records and how to link records to each other.  Also remember to link to the relevant section(s) of the ASpace Help Center's User Manual.]*

## Overview

**Purpose**: To record information about new archival materials, whether distinct collections or accruals to existing collections.  

**Who creates, and when**: Anyone who needs to document the accessioning of archival material, either at the time the materials are received or after the fact.

**To Create a New Record**:

1. First, make sure that your accession has a unique identifier by making sure it isn't already in the master list: [UHM Library Archival Collections](https://drive.google.com/open?id=1VD_ShYlU-m_fzbAzrUhigjBtcp-6xGua1GxQFoEFm9s) in Google Sheets
    1. If it's a **new acquisition**
       1. Ask the registrar--as of Fall 2024, Leilani Dawson--to assign an accession number to your acquisition.
       2. Go to ASpace when you have the accession number.
    2. If it's a **pre-existing accession** (that for some reason wasn't ever recorded in ASpace) **but you don’t know the accession number**
       1. Ask the registrar to check to see if it already has an accession number
       2. In your request, make sure to note what you know about the accession, especially any details you may have about its title, creator, donor, the dates and formats of materials, and the year of donation.
       3. Go to ASpace when you have the accession number.
    3. If it’s a **pre-existing accession** (that for some reason wasn't ever recorded in ASpace) **and you know the accession number**
       1. You can go directly to ASpace.
2. Then, in ASpace
   1. Under the 'Create' menu, choose 'Accession'.
   2. Enter at least the 'Minimum Fields for Good Practice' (see below).
   3. (Optional): Add any 'Desirable' and/or 'Optional' fields (see below) if/as wished.
3. As you are working: Save throughout the process to ensure you don't lose data.
4. When finished: Make sure the 'Publish?' checkbox is left un-checked.  (We don't publish accession records.)

## Fields in Accession Records

### Minimum Fields for Good Practice

ArchivesSpace only requires the ‘Identifier’ field, but also fill out the ‘Title’, ‘Accession Date’, ‘Provenance’, ‘Acquisition Type’, and ‘Resource Type’ fields; plus the fields pertaining to restrictions if they apply.

1. **Basic Info > Title**
   1. Give the title of the accession, usually in the form of ‘Creator Name’ + ‘Resource Type’ (see instructions at link for ‘Resource Type’ options).
      1. If an accession is almost entirely made up of only one or two forms of material, use those form(s) in the title, e.g. 'Masao Sakagami Photographs' instead of the broader 'Masao Sakagami Papers'.
      2. See the description of the 'Title' field on the Resource Record page *[add link]* for more details and examples.
   2. If an accession is an accrual, it is very helpful to add the accession number to the title; otherwise, when linking accessions to either each other or to resource records, all the accessions in the search/browse lists for a single collection end up listed as 'So and So papers', with nothing to distinguish them from each other.
2. **Basic Info > Identifier**
   1. In the first box, enter the acquisition’s accession number.  Don't split the parts of the number into different boxes.  
      1. (I.e. the department code if present, the accession year, and the numeric sequence should all go into the first box.)
      2. NOTE: This is NOT standard practice! Most institutions put each section of an accession number into its own separate box, but at this point it would take a fairly significant change to switch everything.
3. **Basic Info > Accession Date**
   1. The field defaults to the current date.  
      1. If the materials were accessioned earlier than their being logged into ArchivesSpace, then replace the default date with the actual date that they were accessioned.
4. **Basic Info > Provenance**
   1. Enter a brief description of how the accession came into the library's possession.
      1. E.g. "Purchased from [X] with [Y] funds" or "Donated by [Creator]'s daughter, [Donor]".
   2. (The field can also be used for longer/more complicated chain of custody information, but this isn’t required.)
5. **Basic Info > Acquisition Type**
   1. Choose **‘Transfer’** for University of Hawai'i records; otherwise choose **‘Deposit’**, **‘Gift’**, or **‘Purchase’** as appropriate.
6. **Basic Info > Resource Type**
   1. Choose **‘Records’** for materials created by a corporate entity / organization / institution in the course of its work.
   2. Choose **‘Papers’** for materials created by an individual or a family in his/her/their everyday life/lives
   3. Choose **‘Publications’** for accessions consisting of only published print materials.
   4. Choose **‘Collection’** for anything else, but especially for materials collected/compiled by one person/family/corporate entity but created by (an)other(s).
7. **Basic Info > Access and/or Use Restrictions Fields**
   1. If there are either access or use restrictions, first click/check the **‘Restrictions Apply?’** checkbox.
   2. Then, if there are access restrictions, enter data into the **‘Access Restrictions?’** checkbox and **‘Access Restrictions Note’** pair; if there are use restrictions, enter data into the **‘Use Restrictions?’** checkbox and **‘Use Restrictions Note’** pair. (And if there are both, enter data into both pairs.)

#### Access Restrictions vs. Use Restrictions

**Access restrictions:** Used to describe any issues arising from materials’ physical condition, donor agreements, potential for containing sensitive information, licensing conditions, and/or intellectual property rights that prevent patrons from reading/viewing/listening to them, e.g.:

- “Fragile originals have been retired; patrons must use the microfilm version”
- “Correspondence closed until donor’s death”
- “Items containing SSNs or other sensitive information may be redacted”
- “Copyrighted AV materials not available for streaming online, and must instead be accessed on-site”
- “All records from [office of origin] are restricted for 20 years from date of creation”

**Use restrictions:** Used to describe any issues arising from materials’ licensing conditions, donor agreements, and/or intellectual property rights that prevent patrons from citing/copying/creating derivative works from them, e.g.:

- “Quoting materials from this collection requires permission from the donor’s estate”
- “No photographs or other reproductions allowed”
- “The donor published the designs in his collection with a CC-BY-NC-SA license, which is still in effect”

### Desirable Fields

1. **Basic Info > Content Description**
   1. Enter a brief narrative summary of the content of the accession.
2. **Basic Info > Condition Description**
   1. If the accession has preservation issues or includes things requiring special handling, note them here.
3. **Dates**
   1. General Usage Notes
      1. Click the **'Add Date'** button to get started.
      2. If necessary, multiple Dates sections can be added to describe the entire accession in different ways, for example 'bulk; vs. 'inclusive' dates, or 'Creation' vs. 'Publication', 'Copyright', or 'Broadcast' dates.
      3. Do not use multiple Dates sections to describe different parts of the accession; instead put that sort of information in either the 'Content Description' field or the 'Inventory' field.
      4. For each Dates section you add, the following fields are mandatory:
         1. 'Label'
         2. 'Type'
         3. Either 'Expression' or the appropriate combination of 'Begin' and/or 'End' dates
   2. **Dates > Label**
      1. The choice for this field will usually be **'Creation'**.  However, in rare cases one of the other options may be more appropriate.
   3. **Dates > Type**
      1. Choose **'Single'**, **'Inclusive'**, or **'Bulk'**, as appropriate.
   4. **Dates > Expression, Begin, and End Fields**
      1. You must use either the **'Expression'** field or the appropriate combination of **'Begin'** and/or **'End'** fields.
         1. If you have a **'Single'** date rather than a date range, in most cases you should use only the **'Begin'** field.
         2. If you have a date range, in most cases you should use both the **'Begin'** and the **'End'** fields.
         3. The **'Expression'** field is free-text, so if you need to add phrases like ‘circa’ or ‘not before’ to your date(s), choose this option.
            1. It can also be useful when a date range is very lopsided and/or sporadic, and you don't want to mislead researchers by entering a date range such as '1921-2021' when the materials actually cover 1921, 1997-1999, March 15th 2014, and 2020-2021. (This is another situation in which the  'Content Description' field and/or the 'Inventory' field can be useful places to provide more detail.)
         4. Using both sets of fields can make the record look weird--in some views both sets of dates display without context distinguishing them or explaining why they are both present--however nothing put into the **'Expression'** field shows up in date searches, and that data also cannot be used when sorting or or filtering search results by date. So, if the **'Expression'** field is used it is best to also put a normalized version of the expression into the **'Begin'** and/or **'End'** fields.
         5. For more details on how to enter dates, including examples and guidelines for translating date expressions into ranges, see the instructions on 'Dates' in Section IV Part B, Creating Resource Records *[add link]*.
4. **Extents**
   1. General Usage Notes
      1. Click the **'Add Extent'** button to get started.
      2. If necessary, multiple Extents sections can be added to either describe the entire accession in different ways--e.g. number of cubic feet vs. number of volumes for a collection of oversize ledgers--or to describe different parts of the accession (e.g. number of volumes plus number of reels for a collection of scrapbooks and films).
      3. For each Extents section you add, the **'Portion'**, **'Number'**, and **'Type'** fields are mandatory.
   2. **Extents > Portion**
      1. Choose either **'Whole'** or **'Part'** as appropriate.
   3. **Extents > Number and Type**
      1. These fields are used to record the amount and the unit of measure of the extent, respectively.  **'Type'** will usually be in 'Cubic Feet' or 'Linear Feet', but many of the other options will be appropriate at various times.
      2. **Note for Digital materials**: Only create extents in terms of Tera-, Giga-, Mega-, or Kilobytes.  Don’t create extents for the numbers of containers (e.g. discs, floppies, etc.).  Instead, list those in the 'Container Summary' field.
   4. **Extents > Container Summary**
      1. Give a parenthetical listing of the number and type of containers if it’s not obvious from the 'Number' and 'Type' fields, E.g.:
         1. "(20 records cartons, 5 oversize flat boxes, and 1 rolled tube)"
         2. "(Twelve 5¼-inch floppy diskettes)"
5. **Agent Links**
   1. Click the **'Add Agent Link'** button to get started. If you add Agent Links, each agent’s name and role are required.
      1. **'Role'**: If adding agent links, carefully consider the 'Role' in relation to the accession:
         1. Adding agents who are creators (i.e. Role = 'Creator') is desirable
         2. Adding agents as donors is optional
         3. Adding agents as subjects should not be done in accession records (subject analysis work should be done by Catalogers, and so that effort should be saved for resource records)
      2. **'Agents'**: Either type a few letters of the name into the ‘Agents’ box to search for a name, or click the downward-pointing triangle to bring up the browse list.
         1. If neither of those options brings up the desired name--or if the name may be confused with another agent with a similar name--do a separate Agent Records search to ensure that the name doesn't match any already-existing agent records, and if need be create a new Agent Record according to the instructions in Section IV Part E *[add link]*.

### Optional Fields

**Note re: Optional Fields**: All fields not either listed above in the 'Good Practice' and 'Desirable' sections or listed below in the 'Do Not Use' section are optional.  Add them if you think it is worth the effort, or if you particularly need to track the location(s) of the material you're accessioning.

- With the exception of the 'Instances' section, most should be fairly self-explanatory.
- If not, read the tool tips, look at the relevant section(s) of the User Manual in the ASpace Help Center *[add link]*, or ask Leilani for guidance.

1. **Instances**
   1. General Usage Notes
      1. An ‘Instance’ is a physical or digital instantiation of a specific set of materials. A set of materials may have multiple instances: born-digital items may be printed out, physical items may be digitized, and both physical and digital items may be reformatted (e.g. a folder of paper documents may also exist in microfilm form, or a file of digital photos may be have both preservation and access versions).
      2. In ArchivesSpace, physical materials--including microfilm, paper, photocopies, and other analog reproductions--are represented by container instances, and digital items--whether born-digital or digitized--are represented by digital object instances.
      3. To get started, click on either the **‘Add Container Instance’** button or the **‘Add Digital Object’** button.
   2. **Instances > Digital Object Instances**
      1. For Digital Object Instances, the **'Digital Object'** field is required.
      2. To link to an existing Digital Object record, either type a few letters into a search bar or click on the downward-pointing triangle to browse.
         1. If there isn’t already a Digital Object record for your material, follow the instructions for creating Digital Object records in Section IV Part D *[add link]*, and then return to the Accession Record and link to it.
      3. If there is more than one digital version of an item--e.g. original, thumbnail, mezzanine, etc.--each should have its own Digital Object Instance.
         1. (Note on the **'Make Representative'** checkbox: Clicking ‘Make Representative’ designates a specific file version/instance as the one that should be highlighted on a resource / accession / component page in the public view.  However, since we don’t publish accession records, ‘Make Representative’ is irrelevant for our Accession records.)
2. **Instances > Container Instances**
   1. If you are adding a Container Instance, the **'Type'** and **'Top Container'** fields are required, and the child and grandchild types and indicators are optional.
      1. **'Type'**: Choose the appropriate genre/format term for the material being described. 
         1. **'Mixed Materials'** is most common for archival material, but there may be cases where one of the other choices is more apt.
            1. (Because of database weirdness, some terms are listed twice; in these cases go with the capitalized version of the term.)
         2. Alternatively, if creating a single instance for the entire accession, choose **'Accession'** as the Type, and see below for what to enter for ‘Top Container’.
      2. **'Top Container'**:
         1. Containers vs. Top Containers vs. Locations:
            1. If it moves and/or can get paged, it’s a Container. If it’s stationary, it’s a Location. If it’s a container that is not contained within any other container, it’s a Top Container.
               1. So, folders are top containers when they’re in map case drawers--which don’t get paged--but not when they’re in boxes, which do.
               2. Similarly, objects, items, A/V reels, etc. that are not in boxes but are instead placed directly on shelves or in drawers should be listed as top containers (even though they don’t technically contain anything, but are just themselves).
         2. To link to an existing top container--for example when adding an accrual to an existing collection, or adding either a very small collection or a few folders of oversized materials to a multi-collection box--either type a few letters of the name of the container into the search bar or click on the downward-pointing triangle to browse.
            1. It is possible to search by keywords in addition to the exact container title, but this is considerably less helpful than it sounds, because the results don’t recognize quotes in phrases. So, for example, searching for “Box 3” brings up all the containers in ArchivesSpace tha have both ‘Box’ and ‘3’ in their records.  (Also, a maximum of 15 records shows up in the search list, even if there are more "Box 3"s in ASpace.)
            2. Browsing takes you to a pop-up screen, and is much more helpful, acting is some ways like an advanced search.
         3. To create a new Top Container record directly from the Container Instance Section of the Accession Record
            1. (Also see Section IV Part H for more on Locations and Containers *[add link]*, including how to create new top containers.)
            2. Click on the downward-pointing triangle and choose **'Create'**.
            3. If possible, use a Container Profile to help standardize things.
               1. As of 2024 there are very few Container Profiles entered into ASpace, so it may not be possible.
               2. Note on dimensions in container profiles: the dimensions in the profile’s **Container Title** are the stated dimensions of the boxes (usually the interior dimensions), while the ones in the **Dimensions** fields are the actual average outside dimensions, including lids.
            4. **'Container Type'**
               1. **‘Box’** is the most common type for top containers, but occasionally some of the others are appropriate.
               2. NOTE: If you chose **‘Accession’** as your instance type, then choose **‘bin’** as your Top Container type (in this case ‘bin’ represents a fake top container holding the entire accession).
               3. Ignore the container types of **‘map-case’** and **‘drawer’**!!  Treat these as locations, not as containers. 
                  1. (Leilani will periodically check to see if any records use either of these as container types, and is looking into how to delete them as options.)
                  2. If you by some odd chance have drawers that can be removed and paged--like natural history specimen drawers in museums--ask Leilani what to do instead.
            5. **'Indicator'**
            6. **'Barcode'**
            7. **'Location'**
            8. Child and/or Grandchild Containers



### Do Not Use These Fields

[...]
