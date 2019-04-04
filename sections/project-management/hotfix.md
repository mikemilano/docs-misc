# Hotfix

Any tasks which need to be released immediately once complete \(and potentially prior to a migrated release from the 'develop' branch\) should be labelled in JIRA with “hotfix” and have a priority setting of "Critical".

Hotfix tasks need to have their own dedicated branch \(use 'hotfix\/&lt;jira-id&gt;' for branch name\).

* Once hotfix is ready for QA; push branch and deploy to STAGE.

* Another person to QA. Possible scenarios:

 * Passes: Merge hotfix branch into master and tag release from master. Finally merge master back into develop.

 * Reopened: Continue to work on hotfix branch until pass then follow above bullet.




