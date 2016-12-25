Hamster-GTD
===========

Boost productivity while reducing your stress by organizing your documents and workflow with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done) and [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format).



###So, how can you start?

**Organize your (digital) documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Naming](#naming)
- [Archiving](#archiving)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actionable notes: tasks](#actionable-notes-tasks)
- [Non-actionable notes: references](#non-actionable-notes-references)
- [How to navigate through your notes](#how-to-navigate-through-your-notes)
- [How does it look?](#how-does-it-look)



---
##Organize your (digital) documents
*'Every document belongs to a project'.*



###Main folder:

- main folder<sup id="refnote1"> [1](#footnote1)</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- project status: **PROJECT STATUS**

        Inside your main folder there are 3 folders:

        INBOX (folder to put new documents until deciding what to do with them).
        CURRENT (folder to store your active projects).
        ARCHIVE (folder to store your dormant projects).



===
###Project folders:

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



===
###Naming:

- to reduce unnecessary nesting and memorization, name some folders combining nesting levels:

        e.g: When having one or two folders inside a folder, you can join them and reduce nesting
        Use: #large investor@house in portugal
        Instead of: #large investor \ @house in portugal

        When the folder name is too generalist, add anterior nesting name(s) for context:
        e.g: -drawings-sections
        e.g: -drawings-details-wall

- use spaces or other naming style:

        e.g. using spaces: #large investor@house in portugal
        e.g. using camelCase: #largeInvestor@houseInPortugal
        e.g. using snake_case: #large_investor@house_in_portugal


- but don't use these symbols for regular naming: **# @ . - + $ % { } [ ]**

- enclose folder's name to mark it as private: **[ ]**

		Private bundle with all your personal related projects.
        e.g: [#personal]

- name your files using a system that fits you<sup id="refnote2"> [2](#footnote2)</sup>. Suggestions:

		Use a prefix for standard / boilerplate files: $
        e.g: $curriculum+A007

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).



===
###Archiving:

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch**

- archive files using [BranchVer](https://github.com/galfarragem/branchVer) (each version *adds* a change on data): **+ branch . progress**



===
###How to navigate through your documents:

- you only need two *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to INBOX folder
        Shortcut to CURRENT folder

        A shortcut to archive is not needed, only dormant projects are there.

- and *temporary* shortcuts to very active folders.



---
##Organize your workflow
*'Inputs to your workflow are materialized as notes'.*



###Introduction:

- your workflow consists of a collection of plain text notes on a cloud synced folder<sup id="refnote3"> [3](#footnote3)</sup> or on paper notebook.   

- actionable notes are called [tasks](#actionable-notes-tasks); non-actionable notes are called [references](#non-actionable-notes-references).

- workflow management is loosely inspired on [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) and [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf) but using only plain text files edited with any text editor and a paper notebook. Folder's structure (check also [how does it look](#how-does-it-look)):       

        1.Tasks (to store all actionable notes)
            // on a paper notebook
            0. Next (tasks to be done ASAP)

            // on a cloud synced folder.
            1. Soon (tasks in the queue to get done)
            2. Someday (tasks to get done someday)
            3. Calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)

        2.References (to store all non-actionable notes)



===
###Actionable notes (tasks):

- actionable notes are called **tasks**. All tasks are managed in one folder.

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



===
###Non-actionable notes (references):

- non-actionable notes are called **references**. All references are managed in one folder.

- projects should have a reference note to compile info as: a list of tasks (*briefing*), a list of completed tasks (*changelog*) and specific references. Therefore name your notes using [project folders notation](#project-folders):

        Note with all references regarding a particular subproject:
        e.g: @house in portugal.building permit

        Suggestion: use reference notes to keep your collection of bookmarks.
        e.g: #research@frontend



===
###How to navigate through your notes:

- use Text Editor's side bar for navigation.



===
###How does it look?

- screenshot of Hamster-GTD showing calendar folder on [Sublime](https://www.sublimetext.com/) text editor.

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.PNG)



---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - the hamster cheeks :) [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - e.g: relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - Google Drive, Dropbox, etc. [↩](#refnote3)</sup>



---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.