# Section I Part B: Overview

## Types of Records in the ASpace SUI

As a collections information database, ArchivesSpace (ASpace) has four major record types and numerous minor ones.  The four major record types are Accessions, Resources, Archival Objects, and Digital Objects.  Minor record types include Subjects, Agents, Locations, Containers, Events, and Assessments.

Ordinarily, materials first get logged in ASpace when they are received, as an Accession.  When one or more related accessions get processed as a collection, that collection is entered as a Resource.  In simple cases, a Resource record can be spawned directly from an Accession Record, but more commonly, a Resource record will be created from scratch, and the relevant Accession records linked to it.  (Very rarely, a single accession might be split into multiple resources.)  

In general, a Resource record is the top-level record for a collection (or record group, or fonds).   In multi-level archival description, Archival Object records (a.k.a. Archival Component records) exist as children of a Resource record, and may describe series, sub-series, files, items, and various other levels in a collection hierarchy.  

It should be noted that Archival Object/Component records describe logical and/or intellectual entities, NOT specific physical or digital instances of those entities.   The physical form of an archival object would get described in a physical Container Instance attached to that component that notes the object’s container and the location of that container, while a digital version of it would be described in a Digital Instance attached to it.  

Additionally all digital material--whether born-digital archival materials or files digitized from physical collection items--may be described in Digital Object records, which may be linked to Resource records at the collection level, linked to Archival Object records at a lower level in a collection hierarchy, or left as stand-alone entities.  

## Other Notes

- Most of ASpace's functionality can be reached through either the Browse drop-down menu or the Create drop-down menu, both of which are located in the upper left hand corner of the page under the "University of Hawaiʻi at Mānoa Library' logo.  Notably, the Create menu includes the run reports (under the 'Background Job' option) as well as to create various types of records.
  - Searching and browsing is detailed in Section III of this guide *[include link]*, while creating records (and background jobs) is covered in Section IV.
- If you find yourself unsure of what you are looking at when you are viewing a record, note that many fields have tool tips that appear when you hover the mouse pointer over the field label.
- ArchivesSpace allows multiple people to work in the program at once—a good thing!—but also allows multiple people to work on a single record at the same time, which can be problematic.  If two (or more) people are editing the same record at the same time and both (or all) make changes to the record, the only changes that are kept are those of whoever saves first.  The second person (and anyone else who was also simultaneously editing that record) would then get an error message saying that their changes can’t be saved.
  - In order to avoid this, save often, especially when editing records that are often updated!  (Saving records frequently also helps prevent loss of data due to lost network connections or other weirdness.)
