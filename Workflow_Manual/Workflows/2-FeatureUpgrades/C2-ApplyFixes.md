# Feature Upgrade Process: Section C Part 2: Apply the Updates / Changes to the Production Instance

**[incomplete draft outline; what steps are present are not necessarily in order]**

## Timing

Mid May - Mid June (more or less, aim for May 16th - June 15th)

## Tasks

- install / update plugins; update config.rb; and so on

Note: if any of the changes/updates require reindexing: Delete:

- \archivesspace\data\indexer_state
- \archivesspace\data\indexer_pui\state

Also see ASpace tech docs page on soft reindexing vs. hard reindexing.  (Logs are available at: archivesspace\logs\)

- If/as needed, re-apply (or update) various default settings in SUI (language/script; note order; browse+search column order; etc.)  specifically:
  - Controlled Value List: ISO 639-2: Language (of both materials and description)  [in resource, accession, and object records]: English set as default
  - Controlled Value List: ISO 1xxxx: Script (of both materials and description) [in resource, accession, and object records]: Latin set as default
  - Repository / Global Default settings:  see uploaded word doc w/details

- *[also figure out / determine: how is this step different from the parallel step in a version upgrade?]*
