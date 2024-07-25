# UHML ASpace Upgrade Workflows - Overview

Note: Each list item is further described in a detailed workflow for that process/sub-task. (Eventually these will all be linked below.)

## Version Upgrades

### A) September-December: background research / sandboxing and unit tests / etc

1. Preparation / background research on target version and on any/all intervening updates
2. Test drive target version in sandbox
3. Pre-emptive (draft) updates to presumably-affected plugins, config settings, workflows, etc.
4. Pre-upgrade data cleanup (in production) and low-level testing (in sandbox)

### B) January-April: putting it all together and exploring the impact of new changes on a test server with real data

1. Data capture from production and creation of test instance of new version
2. Refine / solidify updates to affected plugins, config settings, workflows, etc.
3. Thorough testing; troubleshooting
4. Review of likely known issues (troublespots from past version upgrades)
5. Ensure GitHub codebase repo is up to date (merge branch initially created in step A.3.)

### C) May-August: performing the production server upgrade / documentating the work / training and outreach

1. Embargo production server
2. Data capture from old/existing production instance and creation of production instance of new version
3. Apply local updates from step B to production server
4. Inspect new version
5. Documentation: update GitHub docs repo (Staff Manual, Update Chronology, Release Notes, and Workflow Guide)
6. Training and outreach

## Feature Upgrades

### A) September-December: background research / drafting (or fixing) code / sandboxing and unit tests / etc

1. Preparation / background research into issues to be resolved / features to be added
2. Create new branch with draft versions of fixes / new features
3. Test drive fixes / new features in sandbox
4. Pre-upgrade data cleanup (in production) and low-level testing (in sandbox)

### B) January-April: putting it all together and exploring the impact of new changes on a test server with real data

1. Data capture from production to turn sandbox into true test instance
2. Refine / solidify updates to affected plugins, config settings, workflows, etc.
3. Thorough testing; troubleshooting
4. Ensure GitHub codebase repo is up to date (merge branch initially created in step A.2)

### C) May-August: performing the production server upgrade / documentating the work / training and outreach

1. Embargo production server
2. Apply changes / fixes from step B to production server
3. Inspect improved instance
4. Documentation: update GitHub docs repo (Staff Manual, Update Chronology, Release Notes, and Workflow Guide)
5. Training and outreach

## Non-upgrade Improvement Projects

### A) September-October: scoping the project(s) and doing preliminary groundwork  

1. Select project(s)
2. Determine scope of project(s),  as well as goals/metrics for completion
3. Create project plan(s)

### B) November-May: working on the project(s)

1. Do the work
2. Document the process
3. Keep ArchivesSubcommittee updated

### C) July-August: preparing deliverables / documenting the work / training and outreach

1. Draft summary report and present back to ArchivesSubcommittee
2. Documentation: update GitHub docs repo (Staff Manual, Update Chronology, Release Notes, and Workflow Guide)
3. Training and outreach
