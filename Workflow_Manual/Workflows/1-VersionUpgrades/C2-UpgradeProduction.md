# [incomplete draft outline; what steps are present are not necessarily in order]

- Remember: location records often don't update / show up on their own: delete location logs and/or run script to touch them all.
- other items to be remembered noted by Wing (in his email of 5.24.2024):
  "I'm listing a number of step that I forgot to do initially in no particular order."
  1. run the setup-database.sh script to migrate schema version
  2. copy from plugins/local plugins like frontend and backend
  3. diff config.rb files to apply just the configured settings
  4. delete the solr core and recreate using the configs specific to our version https://github.com/archivesspace/archivesspace/blob/v2.7.1/solr/ --> except note, the '2.7.1' would need to be replaced with whatever our upgrade target version was/is.
  5. delete the indexer_pui_state folder after full staff side indexing on process start.
