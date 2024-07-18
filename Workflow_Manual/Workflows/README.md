# UHML ASpace Upgrade Workflows - Overview

Note: Eventually, this will be a table of contents, with each sub-section (e.g. "1.3." or "2.4.") linking to a detailed workflow for that process/sub-task.

- A) Version Upgrade
  1. September-December: background research / sandboxing and unit tests / etc.  
    1.1. Preparation / background research
    1.2. Test drive in sandbox
    1.3. Pre-emptive (draft) updates to affected plugins, config settings, workflows, etc.
    1.4. Pre-upgrade data cleanup and low-level testing
  2. January-April: putting it all together and exploring the impact of new changes on a test server with real data
    2.1. Data capture from production and creation of test instance of new version
    2.2. Refine / solidify updates to affected plugins, config settings, workflows, etc.
    2.3. Thorough testing; troubleshooting
    2.4. Review of likely known issues (troublespots from past upgrades)
    2.5. Ensure GitHub codebase repo is up to date (merge branch initially created in step 1.3.)
  3. May-August: performing the production server upgrade / documentating the work / training and outreach
    3.1. Embargo production server
    3.2. Data capture from production and creation of production instance of new version
    3.3. Apply local updates from step 2. to production server
    3.4. Inspect new version
    3.5. Documentation: update GitHub docs repo (Staff Manual, Update Chronology, Release Notes, and Workflow Guide)
    3.6. Training and outreach
- B) Feature Upgrade
  1. September-December: background research / drafting (or fixing) code / sandboxing and unit tests / etc.  
  2. January-April: putting it all together and exploring the impact of new changes on a test server with real data
  3. May-August: performing the production server upgrade / documentating the work / training and outreach
- C) Non-upgrade Improvement Project
  1. September-October: scoping the project(s) and doing preliminary groundwork  
  2. November-May: working on the project(s)
  3. July-August: preparing deliverables / documenting the work / training and outreach
