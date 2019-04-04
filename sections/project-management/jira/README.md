# Atlassian Jira

Jira is at the center our project management toolset. [Official Jira Documentation](https://confluence.atlassian.com/jirasoftwarecloud/jira-software-documentation-764477791.html)
is available from Atlassian but the purpose of this section is to define standards around how we use Jira internally.

We have configured Jira so that there is never any question as to what is actionable to you. We do this with
assignments and statuses.

## The Dashboard

The [Dashboard](https://thinkbean.atlassian.net/secure/Dashboard.jspa) contains panels which clearly show which issues
are actionable to you.

### Assigned to Me

This panel contains a list of issues that are currently actionable to you. If there is something in this list that is
not actionable because it needs more info or is waiting for action by someone else, it probably should be in another
workflow status or be assigned to someone else.

### Filter Results: Status - More Info

PMs keep their eyes here as issues which require more info by the developer will be sent to this workflow status by
selecting `Workflow -> Request More Info` from an opened ticket.

### Filter Results: Status - QA

Those responsible for QA will keep an eye on this filter. It contains issues that have been resolved. It is important to
note that the resolution isn't always `fixed`. Other resolutions include `Cannot reproduce` or `Won't fix`. When an
issue is set as resolved, the developer is prompted for a comment which should explain in detail if the resolution 
is anything but fixed.

## Reporting Issues

Issues can be reported either directly in Jira, or by using the [Jira Capture](https://www.atlassian.com/software/jira/capture)
browser extension.

Jira capture is especially valuable when reporting bugs as it provides an easy to use annotation interface, as well as
forwards along detail including url and browser info.

For more detail on the standards to follow when creating issues, see the sections regarding [issue titles](issue-titles.md) 
and [issue content](issue-content.md).

## Issue types

There are 3 issue types we use in Jira.

- Bug: A problem with existing functionality.
- Task: New functionality or anything which needs to be done.
- Epic: A large body of work which may be composed of many tasks.

