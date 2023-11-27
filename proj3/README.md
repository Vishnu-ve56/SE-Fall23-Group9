## New Additions:

The forked repo can be found [here]: (https://github.com/SE-Fall23-Group9/FinBot)

### Feature 1: Add Category

While adding our expenses, we have a select set of categories pre loaded and available for use. However, modern day needs require modern day solutions where users need to have the freedom to create and add their own categories. To enable this customization and user freedom, we have developed an add category feature which helps add a whole new category to the existing category list and with this new category, the user can go ahead and log new expenses.


<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.29.59 PM.jpeg">

### Feature 2: Delete Category

When we allow a user to add their own category, we also give them freedom to delete existing and newly created categories. This feature allows users to take away categories that do not make sense to them and this allows personalisation and customization. 

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.30.28 PM.jpeg">

### Feature 3: List Category

This new feature allows users to see the categories that are present. This gives them a good sense of what to expect and if any modifications or additions are necessary, they can go ahead and make them. This feature was found lacking in the previous implementation and to view the list, the users always had to log a new expense. Now, with one command, the user has the ability to glance and view the whole set of pre-set and newly added categories.

### Feature 4: Download expenses

It is always easy to maintain a file of your expenses and have it downloaded in your local system. Keeping this in mind and considering modularity and seperation of concerns, a whole new module was developed which helps download the logged expenses. This downloads as a csv file onto the user's local system and this file can be easily subjected to data analysis if the user wishes. It can also be viewed as structured data which better helps the users. 

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.31.20 PM.jpeg">

### Feature 5: Send Email

Our bot via a single command possesses the capability of sending an email to your email id which contains the logged expenses as a CSV file.  By providing users with the option to receive expense data via email, we enhance the overall user experience and accessibility. Users can now access their data conveniently through their email, which can be more accessible than logging into the application.

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.31.40 PM.jpeg">


<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.32.16 PM.jpeg">

### Feature 6: Open AI integration

Until now the features implemented were straightforward and easy to use. Users these days prefer an even more simplification and we have the right solution for that ! Instead of filling out a questionarre where users are asked questions and based on the responses, the expense is logged accrodingly, we have upped the game and have implemented a version of NLP in our app. All you have to do is enter a sentence in lay man terms and our bot will pick up the key words and log the expense. For example, you can say " I spent 20 dollars on food on 12th Dec 2022" and our bot via the power of OpenAI API, it can pick up "20 dollars" as the expense, "food" as the category and "12th Dec 2022" as the date. This feature demonstrates good API design and usage, and it promotes modularity in our application.

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.32.37 PM.jpeg">

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.33.18 PM.jpeg">

### Feature 7

The basic UI which leverages existing appreance and features of Discord has been improved to provide a more intuitive and a user friendly, modern design. 

<img width=500 src="/proj3/img/WhatsApp Image 2023-11-20 at 6.33.33 PM.jpeg">


### Demo

Watch the demonstration of ScheduleBot with new feature here: (https://www.youtube.com/watch?v=X3ZyGA6PUtM)

### Scorecard

|Description|Rating|Notes|
|-----|---------|-------|
|Does your website and documentation provide a clear, high-level overview of your software?|3|[Yes](https://github.com/SE-Fall23-Group9/FinBot/blob/main/README.md)|
|Does your website and documentation clearly describe the type of user who should use your software?|3| [Explicitly mentioned the target audience](https://github.com/SE-Fall23-Group9/FinBot/blob/main/README.md)|
|Do you publish case studies to show how your software has been used by yourself and others?|3|[Yes](https://github.com/SE-Fall23-Group9/FinBot/blob/main/README.md)|
|Is the name of your project/software unique?|3|It is a unique name.|
|Is your project/software name free from trademark violations?|0|Apparently there is a [character](https://powerpuffgirls.fandom.com/wiki/Schedulebot) and another [bot] (https://mellamopablo.github.io/schedulebot/)|
|Is your software available as a package that can be deployed without building it?|2|Its on Python, but dependencies need to be installed|
|Is your software available for free?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is your source code publicly available to download, either as a downloadable bundle or via access to a source code repository?|3| [Yes](https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is your software hosted in an established, third-party repository likeGitHub (https://github.com), BitBucket (https://bitbucket.org),LaunchPad (https://launchpad.net) orSourceForge (https://sourceforge.net)?|3| [Yes, Repo available](https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is your documentation clearly available on your website or within your software?|3|It is available in the [README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your documentation include a "quick start" guide, that provides a short overview of how to use your software with some basic examples of use?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|If you provide more extensive documentation, does this provide clear, step-by-step instructions on how to deploy and use your software?|3|Yes,(https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Do you provide a comprehensive guide to all your software’s commands, functions and options?|2|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Do you provide troubleshooting information that describes the symptoms and step-by-step solutions for problems and error messages?|0|There is no support to aid troubleshooting|
|If your software can be used as a library, package or service by other software, do you provide comprehensive API documentation?|0|No|
|Do you store your documentation under revision control with your source code?|3||
|Do you publish your release history e.g. release data, version numbers, key features of each release etc. on your web site or in your documentation?|2|We have the space for it on [Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your software describe how a user can get help with using your software?|3|[Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)and our bot has a !help command.|
|Does your website and documentation describe what support, if any, you provide to users and developers?|3|Issues can be publicly opened in the [repo](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Does your project have an e-mail address or forum that is solely for supporting users?|3|Yes, can be found in [Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Are e-mails to your support e-mail address received by more than one person?|3|Yes [Readme.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your project have a ticketing system to manage bug reports and feature requests?|2|Issues can be opened [here](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Is your project's ticketing system publicly visible to your users, so they can view bug reports and feature requests?|3|Issues can be opened [here](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Is your software’s architecture and design modular?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/src)|
|Does your software use an accepted coding standard or convention?|3|Check [CONTRIBUTING.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CONTRIBUTING.md)|
|Does your software allow data to be imported and exported using open data formats?|0|Not yet|
|Does your software allow communications using open communications protocols?|3|Discord|
|Is your software cross-platform compatible?|3|Multi-platform through Discord, either native or online clients|
|Does your software adhere to appropriate accessibility conventions or standards?|3|[code of conduct](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CODE_OF_CONDUCT.md)|
|Does your documentation adhere to appropriate accessibility conventions or standards?|3|Its autogenerated by pdoc3.|
|Is your source code stored in a repository under revision control?|3|[yes](https://github.com/SE-Fall23-Group9/ScheduleBot)|
|Is each source code release a snapshot of the repository?|1|Previous releases are stored in [Zenodo](https://zenodo.org/record/5523462)|
|Are releases tagged in the repository?|3|Check [releases](https://github.com/SE-Fall23-Group9/ScheduleBot/releases)|
|Is there a branch of the repository that is always stable? (i.e. tests always pass, code always builds successfully)|2|[main](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main),but not 100% of the time.|
|Do you back-up your repository?|3|Each contributor constantly pulls from the repo, every release is stored in [releases](https://github.com/SE-Fall23-Group9/ScheduleBot/releases)|
|Do you provide publicly-available instructions for building your software from the source code|3|Python is scripted, and all required packages are available on [requirements.txt](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt)|
|Can you build, or package, your software using an automated tool?|0|Not yet|
|Do you provide publicly-available instructions for deploying your software?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your documentation list all third-party dependencies?|3|All required packages are available on [requirements.txt](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt)|
|Does your documentation list the version number for all third-party dependencies?|2| [Most of the cases](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt)|
|Does your software list the web address, and licences for all third-party dependencies and say whether the dependencies are mandatory or optional?|2|[Most of them](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt)|
|Can you download dependencies using a dependency management tool or package manager?|3|run pip install -r requirements.txt|
|Do you have tests that can be run after your software has been built or deployed to show whether the build or deployment has been successful?|3|All in the [test](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/test) directory|
|Do you have an automated test suite for your software?|3|Through [github actions](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Do you have a framework to periodically (e.g. nightly) run your tests on the latest version of the source code?|3| [Github actions](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Do you use continuous integration, automatically running tests whenever changes are made to your source code?|3|[Github actions](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Are your test results publicly visible?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/test)|
|Are all manually-run tests documented?|0|No manual tests|
|Does your project have resources (e.g. blog, Twitter, RSS feed, Facebook page, wiki, mailing list) that are regularly updated with information about your software?|3|Usage of discord bot is fairly simple and there are plenty of posts online|
|Does your website state how many projects and users are associated with your project?|2|[README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)shows the amount of downloads for all releases|
|Do you provide success stories on your website?|2|The use cases are in a way success stories|
|Do you list your important partners and collaborators on your website?|3|Contributors can be seen on our repo|
|Do you list your project's publications on your website or link to a resource where these are available?|0||
|Do you list third-party publications that refer to your software on your website or link to a resource where these are available?|0||
|Can users subscribe to notifications to changes to your source code repository?|3|One can keep track of updates via our repo|
|If your software is developed as an open source project (and, not just a project developing open source software), do you have a governance model?|3||
|Do you accept contributions (e.g. bug fixes, enhancements, documentation updates, tutorials) from people who are not part of your project?|3|Issues are open, repo is open|
|Do you have a contributions policy?|3|[CONTRIBUTING.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CONTRIBUTING.md)|
|Is your contributions' policy publicly available?|3|[CONTRIBUTING.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CONTRIBUTING.md)|
|Do contributors keep the copyright/IP of their contributions?|1|maybe? [MIT license](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/LICENSE) is not specific|
|Does your website and documentation clearly state the copyright owners of your software and documentation?|3|[Yes]((https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/LICENSE))|
|Does each of your source code files include a copyright statement?|0|No|
|Does your website and documentation clearly state the licence of your software?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/LICENSE)|
|Is your software released under an open source licence?|3|[Yes](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/LICENSE)|
|Is your software released under an OSI-approved open-source licence?|3|[Yes,MIT](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/LICENSE)|
|Does each of your source code files include a licence header?|3||
|Do you have a recommended citation for your software?|2|A DOI|
|Does your website or documentation include a project roadmap (a list of project and development milestones for the next 3, 6 and 12 months)?|3|Yes, in the [README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Does your website or documentation describe how your project is funded, and the period over which funding is guaranteed?|3|By the contributors|
|Do you make timely announcements of the deprecation of components, APIs, etc.?|0|No rollbacks|
|Video : 2min video of new functionality, showing a significant delta from prior.|2| Only the [video of the latest realease](https://youtu.be/dpqK9mt-y28?si=nPnQ55X8d_-AML9a) is present and this makes sense|
|Workload is spread over the whole team (one team member is often Xtimes more productive than the others... 
but nevertheless, here is a track record that everyone is contributing a lot)|3|Evidence in GH, [Github Contributions](https://github.com/SE-Fall23-Group9/ScheduleBot/graphs/contributors)|
|Number of commits|3|[Github Contributions](https://github.com/SE-Fall23-Group9/ScheduleBot/graphs/contributors)|
|Number of commits: by different people|3|[Github Contributions](https://github.com/SE-Fall23-Group9/ScheduleBot/graphs/contributors)|
|Issues reports: there are **many**|2|[GH Issues](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Issues are being closed|3|[GH Issues](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|DOI badge: exists|3|[README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Docs: doco generated, format not ugly |3|Event.html file generated in [Documentation](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/docs)|
|Docs: what: point descriptions of each class/function (in isolation) |3|[Documentation](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/docs)|
|Docs: how: for common use cases X,Y,Z mini-tutorials showing worked examples on how to do X,Y,Z|3|[README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Docs: why: docs tell a story, motivate the whole thing, deliver a punchline that makes you want to rush out and use the thing|3|[README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Docs: short video, animated, hosted on your repo. That convinces people why they want to work on your code.|3|[README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Use of version control tools|3|You're here(https://github.com/SE-Fall23-Group9/ScheduleBot/)|
|Use of style checkers |3|Flake8:[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),[Script](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Use of code formatters. |3|Flake8:[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),[Script](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Use of syntax checkers. |3|Flake8:[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),[Script](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml) also [Test cases](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/test)to a lesser extent|
|Use of code coverage |3|[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),[Script](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml), also check the badge in [README.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/README.md)|
|Other automated analysis tools|3|Flake8:[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),[Script](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.github/workflows/python-app.yml)|
|Test cases exist|3|[Test Directory](https://github.com/SE-Fall23-Group9/ScheduleBot/tree/main/test)|
|Test cases are routinely executed|3|[Automated as A GH Action](https://github.com/SE-Fall23-Group9/ScheduleBot/actions),|
|The files CONTRIBUTING.md lists coding standards and lots of tips on how to extend the system without screwing things up|3|[contributing.md](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/CONTRIBUTING.md)|
|Issues are discussed before they are closed|2|[GH Issues](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Chat channel: exists|3|Discord chat channel|
|Test cases: a large proportion of the issues related to handling failing cases.|3|[GH Issues](https://github.com/Vishnu-ve56/SE-Fall23-Group9/issues)|
|Evidence that the whole team is using the same tools: everyone can get to all tools and files|3|[Requirements.txt](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt)|
|Evidence that the whole team is using the same tools (e.g. config files in the repo, updated by lots of different people)|3|[Requirements.txt](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/requirements.txt) frequently updated and[.gitignore](https://github.com/SE-Fall23-Group9/ScheduleBot/blob/main/.gitignore) has also been updated with the different IDEs the team uses.|
|Evidence that the whole team is using the same tools (e.g. tutor can ask anyone to share screen, they demonstrate the system running on their computer)|3|Statement of the team members. Also most of us have a personal test bot.|
|Evidence that the members of the team are working across multiple places in the code base|3|[Commits on main](https://github.com/SE-Fall23-Group9/ScheduleBot/commits/main)|
