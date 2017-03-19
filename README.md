Hamster-GTD
-----------

Boost productivity while reducing your stress by organizing your documents and workflow with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) (notes on TXT files), [Bullet journal](http://bulletjournal.com/) (notes on paper), Inbox and Desktop zero.



### So, how can you start?

**Organize your (digital) documents:**

- [Container](#container)
- [Project folders](#project-folders)
- [Naming](#naming)
- [Archiving](#archiving)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actionable notes: tasks](#actionable-notes-tasks)
- [Non-actionable notes: references](#non-actionable-notes-references)
- [How to navigate through your notes](#how-to-navigate-through-your-notes)
- [Screenshots](#screenshots)



---
## Organize your (digital) documents
*'Every document belongs to a project'.*



### Container:

- container folder<sup id="refnote1"> [1](#footnote1)</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- main folders: **PROJECT STATUS**

        Inside your container folder there are 3 folders:

        INBOX (folder to put new documents until deciding what to do with them).
        CURRENT (folder to store your active projects).
        ARCHIVE (folder to store your dormant projects).



---
### Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (derived from twitter hashtag): **#**

        Inside CURRENT and ARCHIVE folders you store #bundles of projects:
        e.g: #large investor (bundle with all projects of a client)

- project (derived from twitter mention): **@**

    	Inside #bundle folders you store @projects:
        e.g: @house in portugal    

- subproject (derived from OO programming): **.**

    	Inside @projects you store .subprojects:
        e.g: .building permit

- folder (each nesting level): **-**

    	Inside .subprojects you store -folders:
        e.g: -plans



---
### Naming:

- to reduce unnecessary nesting and memorization, name some folders combining nesting levels:

        e.g: When having just one or two folders inside a folder, join them and reduce nesting.
        Use: #small investor@house in portugal
        Instead of: #small investor / @house in portugal

        When the folder name is too generalist, add anterior nesting name(s) for context:
        e.g: -drawings-sections
        e.g: -drawings-details-wall

- name your files using a system that fits you<sup id="refnote2"> [2](#footnote2)</sup>. Hints:

		Use spaces or other naming style:
        e.g. using spaces: #large investor@house in portugal
        e.g. using camelCase: #largeInvestor@houseInPortugal

		Enclose folder's name to mark it as private: [ ]
        e.g: [#personal]

		Use a prefix for standard / boilerplate files: $
        e.g: $curriculum+A007

		Use a prefix for temporary files: _
        e.g: _tempFile 

- but don't use these symbols for regular naming: **# @ . - + $ % { } [ ] _**

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).



---
### Archiving:

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch**

- archive files using [BranchVer](https://github.com/galfarragem/branchVer) (each version *adds* a change on data): **+ branch . progress**



---
### How to navigate through your documents:

- you only need two *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to INBOX folder
        Shortcut to CURRENT folder

        A shortcut to archive is not needed, only dormant projects are there.

- and/or a laucher-file finder<sup id="refnote3"> [3](#footnote3)</sup>. 



---
## Organize your workflow
*'Inputs to your workflow are materialized as notes'.*



### Introduction:

- your workflow consists of a collection of plain text notes on a cloud synced folder<sup id="refnote4"> [4](#footnote4)</sup> and on paper notebook.   

- actionable notes are called [tasks](#actionable-notes-tasks); non-actionable notes are called [references](#non-actionable-notes-references).

- workflow management is loosely inspired on [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) and [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf) but using only plain text files edited with any text editor and a paper notebook. Files's structure (check also [screenshots](#screenshots)):       

        References (TXT files on a cloud synced folder)

        Tasks (on a paper notebook)
            0-next (tasks to be done ASAP)
            1-soon (tasks in the queue to get done)

            // TXT files on a cloud synced folder
            2-calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)
            3-someday (tasks to get done someday)



---
### Actionable notes (tasks):

- actionable notes are called **tasks**. Time related tasks live within the same file:<br>
Short term tasks are managed on a paper notebook.<br>
Long term tasks are managed on a cloud synced folder.

- tasks should have a due date: **( )**

        Dates are inserted before the task description (allowing chronological sorting):
        
        e.g. inserting a scheduled date: (year-month-day=hour)
        (2015-11-29=9h) Doctor appointment

        e.g. inserting a trigger/fuzzy date: (date >>)
        (2015-03-10 >>) Waiting for client feedback after this date

        e.g. inserting a deadline date: (date <<)
        (2015-10-22 <<) Pay electricity bill until this date

        e.g. without knowing the due date: (soon) or (someday)
        (soon) Call Mom
        (someday) Bungee jumping with friends



---
### Non-actionable notes (references):

- non-actionable notes are called **references**. All references are managed on a cloud synced folder.

- projects should have a reference note to compile info as: a list of tasks (*briefing*), a list of completed tasks (*changelog*) and specific references. Therefore name your notes using [project folders notation](#project-folders):

        Note with all references regarding a particular project:
        e.g: @house in portugal

        Suggestion: use reference notes to keep your collection of bookmarks.
        e.g: #research@frontend



---
### How to navigate through your notes:

- use Text Editor's side bar for navigation.



---
### Screenshots:

- calendar tasks note on Sublime text editor.<sup id="refnote5"> [5](#footnote5)</sup>

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.PNG)

- I use [YAML](https://www.json2yaml.com/convert-yaml-to-json) on reference notes. It's readable and allows data exchange.

![hamster-workflow-screenshot-2](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example2.png)



---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - the hamster cheeks :) [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - e.g: relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - after having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/).<br>
Pros: Launch and file search without external software, low memory usage (less than 40k on win7), fast and configurable. Cons: No calculator function. [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - Google Drive, Dropbox, etc. [↩](#refnote4)</sup><br>
<sup><a name="footnote5">5</a> - hint: on Sublime press F9 (or F5 on Mac) to sort dates. [↩](#refnote5)</sup>



---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.