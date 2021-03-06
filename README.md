# BugAway

BugAway is a web-based issue tracking tool for IT professionals such as software developers/testers/managers used in software development process.

* BugAway implements user- and role-level security for authorization to PRs and projects.

* BugAway has four roles for the users: tester, developer, project manager, admin.

I used ASP.NET Core, C#, Entity Framework Core, VS Community 2019 to build BugAway, and its webpages use HTML5, Razor, and Boostrap.

A user will be automatically assigned as a reporter role upon registration. They can have more than one role at any given time.

A tester can create a new PR for a project, and read and update PRs that they reported.

A developer can read and update PRs to which they are assigned.

A project manager can read & update assigned PRs, create new projects, assign users to the projects, assign a developer to a PR, and archive the projects.

An admin can assign users to roles, read and update PRs, create new projects, assign users to projects, and archive projects.

For all the roles, the users can post comments and attachments to PRs to access.
