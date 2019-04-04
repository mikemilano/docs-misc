# Issue Titles

Yes, an entire page on titling issues. This applies to both tasks and bugs.

Ticket titles should contain context and detail in an informative yet brief format.

This could be achieved by prefixing the title with a word or abbreviation of the section or component it relates to,
(for context) followed by a brief summary. If the solution is known, then the summary should reflect what is to be 
done. If the solution is unknown, then the summary should reflect the problem.

Here is an example of a task in which only the problem is known:

> "Email: Body appears as a block of text"

If the action has already been established, then the task title should reflect the action:

> "Email: Replace new lines with HTML line breaks for non HTML emails"

Formatting titles this way achieves the following:

- The objective is clear at a glance
- An issue is easy to find when looking at a list of titles
- It's easy to find similar tasks or tasks that involve the same components

Brief task titles with context make consuming and reporting on lists of issues easier.


## Comparing Brief Context Driven Titles to User Story Titles

User stories have often been used for titles of tasks and bugs. While a legitimate tool for discovery, it is important 
to note why they don't work well as actionable task titles.

Here are 2 lists of the same tasks, defined in the different styles. The first list uses a user story format, and the
second uses a brief context driven format.

### Consider the following:

- Which list is easier to find dashboard related tasks?
- Which list is easier to find the task involving adding fields to a user profile?
- Which list is easier to determine that the task to add a banner to the dashboard is missing?
- Which list will be easier to get back up to speed on after being at Drupalcon for a week?

#### List defined as user stories:

- As a user, I want to be able to click a button from my dashboard so that I can to add an article
- As a user, I want to see a list of recent comments on my dashboard so I can click through to those pages
- As an admininstrator, I want to click on an edit button below the users picture so I can edit their info
- As a user, I want to be able to select between a wysywig editor and plain text when submitting a comment
- As a user, I want to see a list of new users on my dashboard so that I can see who is knew to the site
- As a user, I want to be notified when a comment is added to a post I commented on
- As an user, I want to see another user's join date on their user profile

#### List defined briefly with context:

- Dashboard: Add button to post an article
- Dashboard: List recent comments
- User Profile: Add edit button below user picture for admin
- Article comment: Enable user to switch between wysiwyg and plain text
- Dashboard: List new users
- Article comment: Notify participants of new comments
- User Profile: Add join date

---

Other issues with using user stories as task titles is that by design, they are a very primitive form of a requirement.
Often the information gathered from several user stories is required to effectively define a single task. They are a 
great discovery tool but should be properly translated into requirements or tasks before assigning directly to 
developers.
