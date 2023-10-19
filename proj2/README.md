## New Additions:

### Feature 1: Group Scheduling

As an upgrade we have added a group scheduling feature. Previously, the bot was able to schedule events and event types for a single user in DMs. However, now ,one can mention the users of the channel and for each mentioned user, the schedule gets created.

<img width=900 src="/proj2/img/WhatsApp Image 2023-10-18 at 4.55.49 PM.jpeg">

### Feature 2: Database Storage

Previously, the events and all other data were stored in a file-folder hierarchy and in csv files. Now, all the data gets stored efficiently in a mySQL database. Schedules are now read, written and updated on the configured database. 


<img width=900 src="/proj2/img/WhatsApp Image 2023-10-18 at 4.55.41 PM.jpeg">


### Demo

Watch the demonstration of ScheduleBot with new feature here: https://youtu.be/dpqK9mt-y28?si=pEcUhaD2_mjGg3jn

|Description|Rating|Notes|
|-----|---------|-------|
|Does your website and documentation provide a clear, high-level overview of your software?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your website and documentation clearly describe the type of user who should use your software?|3| [Explicitly mentioned the target audience](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Do you publish case studies to show how your software has been used by yourself and others?|||
|Is the name of your project/software unique?|1|Name is common|
|Is your project/software name free from trademark violations?|0|Generic Name|
|Is your software available as a package that can be deployed without building it?|2|Its on Python, but dependencies need to be installed|
|Is your software available for free?|3|Yes|
|Is your source code publicly available to download, either as a downloadable bundle or via access to a source code repository?|3| Yes|
|Is your software hosted in an established, third-party repository likeGitHub (https://github.com), BitBucket (https://bitbucket.org),LaunchPad (https://launchpad.net) orSourceForge (https://sourceforge.net)?|3| [Yes, Repo available](https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is your documentation clearly available on your website or within your software?|3|It is available in the [README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your documentation include a "quick start" guide, that provides a short overview of how to use your software with some basic examples of use?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|If you provide more extensive documentation, does this provide clear, step-by-step instructions on how to deploy and use your software?|3||
|Do you provide a comprehensive guide to all your software’s commands, functions and options?|2|(https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Do you provide troubleshooting information that describes the symptoms and step-by-step solutions for problems and error messages?|0|There is no support to aid troubleshooting|
|If your software can be used as a library, package or service by other software, do you provide comprehensive API documentation?|0|No|
|Do you store your documentation under revision control with your source code?|3||
|Do you publish your release history e.g. release data, version numbers, key features of each release etc. on your web site or in your documentation?|2|We have the space for it on [Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your software describe how a user can get help with using your software?|3|[Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)and our bot has a !help command.|
|Does your website and documentation describe what support, if any, you provide to users and developers?|3|Issues can be publicly opened in the [repo](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Does your project have an e-mail address or forum that is solely for supporting users?|0|No|
|Are e-mails to your support e-mail address received by more than one person?|0|There is no support contact in place|
|Does your project have a ticketing system to manage bug reports and feature requests?|2|Issues can be opened [here](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Is your project's ticketing system publicly visible to your users, so they can view bug reports and feature requests?|3|Issues can be opened [here](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Is your software’s architecture and design modular?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/src)|
|Does your software use an accepted coding standard or convention?|3|Check [CONTRIBUTING.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CONTRIBUTING.md)|
|Does your software allow data to be imported and exported using open data formats?|0|Not yet|
|Does your software allow communications using open communications protocols?|1|Discord|
|Is your software cross-platform compatible?|3|Multi-platform through Discord, either native or online clients|
|Does your software adhere to appropriate accessibility conventions or standards?|3|[code of conduct](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CODE_OF_CONDUCT.md)|
|Does your documentation adhere to appropriate accessibility conventions or standards?|1|Its autogenerated by pdoc3.|
|Is your source code stored in a repository under revision control?|3|[yes] (https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is each source code release a snapshot of the repository?|3|Every release is stored in Zenodo(https://zenodo.org/record/5523462)|
|Are releases tagged in the repository?|3|Check releases(https://github.com/lyonva/ScheduleBot/releases)|
|Is there a branch of the repository that is always stable? (i.e. tests always pass, code always builds successfully)|3||
|Do you back-up your repository?|2|main, but not 100% of the time, check the action log(https://github.com/lyonva/ScheduleBot/actions)|
|Do you provide publicly-available instructions for building your software from the source code|3|Python is scripted, and all required packages are available on requirements.txt|
|Can you build, or package, your software using an automated tool?|2||
|Do you provide publicly-available instructions for deploying your software?|3||
|Does your documentation list all third-party dependencies?|3||
|Does your documentation list the version number for all third-party dependencies?|2| Most of the cases|
|Does your software list the web address, and licences for all third-party dependencies and say whether the dependencies are mandatory or optional?|2|GH dependency graph lists all repos.|
|Can you download dependencies using a dependency management tool or package manager?|3|run pip install -r requirements.txt|
|Do you have tests that can be run after your software has been built or deployed to show whether the build or deployment has been successful?|3|All in the test directory|
|Do you have an automated test suite for your software?|3|Through github actions|
|Do you have a framework to periodically (e.g. nightly) run your tests on the latest version of the source code?|3| Github actions|
|Do you use continuous integration, automatically running tests whenever changes are made to your source code?|3| Github actions|
|Are your test results publicly visible?|3|Yes|
|Are all manually-run tests documented?|0||
|Does your project have resources (e.g. blog, Twitter, RSS feed, Facebook page, wiki, mailing list) that are regularly updated with information about your software?|0||
|Does your website state how many projects and users are associated with your project?|1||
|Do you provide success stories on your website?|0||
|Do you list your important partners and collaborators on your website?|0||
|Do you list your project's publications on your website or link to a resource where these are available?|0||
|Do you list third-party publications that refer to your software on your website or link to a resource where these are available?|0||
|Can users subscribe to notifications to changes to your source code repository?|0||
|If your software is developed as an open source project (and, not just a project developing open source software), do you have a governance model?|0||
|Do you accept contributions (e.g. bug fixes, enhancements, documentation updates, tutorials) from people who are not part of your project?|3|Issues are ope, repo is open|
|Do you have a contributions policy?|3|CONTRIBUTING.md|
|Is your contributions' policy publicly available?|3|CONTRIBUTING.md|
|Do contributors keep the copyright/IP of their contributions?|1|maybe? MIT license is not specific|
|Does your website and documentation clearly state the copyright owners of your software and documentation?|3|Yes|
|Does each of your source code files include a copyright statement?|0||
|Does your website and documentation clearly state the licence of your software?|3|README.md|
|Is your software released under an open source licence?|3|Yes|
|Is your software released under an OSI-approved open-source licence?|3|Yes|
|Does each of your source code files include a licence header?|0||
|Do you have a recommended citation for your software?|2|A DOI|
|Does your website or documentation include a project roadmap (a list of project and development milestones for the next 3, 6 and 12 months)?|3||
|Does your website or documentation describe how your project is funded, and the period over which funding is guaranteed?|3|By the contributors|
|Do you make timely announcements of the deprecation of components, APIs, etc.?|0|No rollbacks|
|Video : 2min video of new functionality, showing a significant delta from prior.|2| Only the video of the latest realease is present and this makes sense|
|Workload is spread over the whole team (one team member is often Xtimes more productive than the others... 
but nevertheless, here is a track record that everyone is contributing a lot)|3|Evidence in GH, Github Contributions|
|Number of commits|3|Github Contributions|
|Number of commits: by different people|3| Github Contributions|
|Issues reports: there are **many**|2|GH Issues|
|Issues are being closed|3|GH Issues|
|DOI badge: exists|3|Readme.md|
|Docs: doco generated, format not ugly |3|Documentation|
|Docs: what: point descriptions of each class/function (in isolation) |3|Documentation|
|Docs: how: for common use cases X,Y,Z mini-tutorials showing worked examples on how to do X,Y,Z|2|Readme.md|
|Docs: why: docs tell a story, motivate the whole thing, deliver a punchline that makes you want to rush out and use the thing|2|Readme.md|
|Docs: short video, animated, hosted on your repo. That convinces people why they want to work on your code.|3|Readme.md|
|Use of version control tools|3|You're here(https://github.com/lyonva/ScheduleBot/)|
|Use of style checkers |3|Flake8: Automated as a GH Action|
|Use of code formatters. |3|Flake8: Automated as a GH Action|
|Use of syntax checkers. |3|Flake8: Automated as a GH Action|
|Use of code coverage |3|Automated as a GH Action|
|Other automated analysis tools|3|Flake8: Automated as a GH Action|
|Test cases exist|3|Test Directory|
|Test cases are routinely executed|3|Automated as a GH Action|
|The files CONTRIBUTING.md lists coding standards and lots of tips on how to extend the system without screwing things up|3|contributing.md|
|Issues are discussed before they are closed|2|GH Issues|
|Chat channel: exists|3|Discord chat channel|
|Test cases: a large proportion of the issues related to handling failing cases.|2|GH Issues|
|Evidence that the whole team is using the same tools: everyone can get to all tools and files|2|Requirements.txt|
|Evidence that the whole team is using the same tools (e.g. config files in the repo, updated by lots of different people)|3|Requirements.txt frequently updated and.gitignore has also been updated with the different IDEs the team uses.|
|Evidence that the whole team is using the same tools (e.g. tutor can ask anyone to share screen, they demonstrate the system running on their computer)|3|Statement of the team members. Also most of us have a personal test bot.|
|Evidence that the members of the team are working across multiple places in the code base|3|Commits on main|
|Short release cycles |3|Frequency of commits|
