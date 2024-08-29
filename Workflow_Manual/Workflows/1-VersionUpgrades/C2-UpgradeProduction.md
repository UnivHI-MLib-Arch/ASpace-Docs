# Version Upgrade Process: Section C Part 2: Capture Data From Production and Upgrade Production Instance to Target Version

**[incomplete draft outline; what steps are present are not necessarily in order]**

## Timing

Late May (more or less, aim to have it done sometime in the last two weeks of the month)

## Tasks

- Remember: location records often don't update / show up on their own: delete location logs and/or run script to touch them all.
- other items to be remembered noted by Wing (in his email of 5.24.2024):
  "I'm listing a number of step that I forgot to do initially in no particular order."
  1. run the setup-database.sh script to migrate schema version
  2. copy from plugins/local plugins like frontend and backend
     1. note these should be copied from the test instance of the target version, not from the old production version
  3. diff config.rb files to apply just the configured settings
     1. note the config file should be copied from/compared to the test instance of the target version, not the old production version
  4. delete the solr core and recreate using the configs specific to our version https://github.com/archivesspace/archivesspace/blob/v2.7.1/solr/ --> except note, the '2.7.1' would need to be replaced with whatever our upgrade target version was/is.
     1. Also note: The solr settings should be copied from the test instance of the target version, not from the old production version
  5. delete the indexer_pui_state folder after full staff side indexing on process start.

Other notes:

When reindexing: Delete:

- \archivesspace\data\indexer_state
- \archivesspace\data\indexer_pui\state

Also see ASpace tech docs page on soft reindexing vs. hard reindexing.  (Logs are available at: archivesspace\logs\)
