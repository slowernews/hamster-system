Hamster-GTD
===========

Boost productivity while reducing your stress by organizing your documents and workflow with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done). It uses only plain text files on a cloud synced folder<sup> [1](#footnote1)</sup> and a paper notebook.



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

- main folder<sup id="refnote2"> [2](#footnote2)</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- project status: **PROJECT STATUS**

        Inside your main folder there are 3 folders:

        INBOX folder (to put new documents until deciding what to do with them).
        CURRENT folder (to store your active projects).
        ARCHIVE folder (to store your dormant projects).



===
###Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (derived from twitter hashtag): **#**

        Inside CURRENT and ARCHIVE folders you store #bundles of projects:
        Example: #large investor (bundle with all projects of a client)

- project (derived from twitter mention): **@**

    	Inside #bundle folders you store @projects:
        Example: @house in portugal    

- subproject (derived from OO programming): **.**

    	Inside @projects you store .subprojects:
        Example: .building permit

- folder (each nesting level): **-**

    	Inside .subprojects you store -folders:
        Example: -plans



===
###Naming:

- to reduce the need of memorization or unnecessary nesting, you can name a folder joining more than one nesting level:

        You have only one project inside a bundle, you can simplify nesting:
        Example: #large investor@house in portugal

        Folder name is too generalist, you can add anterior nesting name(s) to help remembering:
        Example: @house in portugal.building permit
        Example: -drawings-sections
        Example: -drawings-details-wall

- use spaces or other naming style:

        Example using spaces: #large investor@house in portugal
        Example using camelCase: #largeInvestor@houseInPortugal
        Example using snake_case: #large_investor@house_in_portugal


- but don't use these symbols for regular naming: **# @ . - + $ % { } [ ]**

- enclose folder's name to mark it as private: **[ ]**

		Private bundle with all your personal related projects.
        Example: [#personal]

- name your files using a system that fits you<sup id="refnote3"> [34](#footnote3)</sup>. Suggestions:

		Use a prefix for standard / boilerplate files: $
        Example: $curriculum+A007

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

- your workflow consists of a colection of notes. Each note is a plain text file (txt).

- actionable notes are called [tasks](#actionable-notes-tasks); non-actionable notes are called [references](#non-actionable-notes-references).

- workflow management is loosely inspired on [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) and [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf) but using only plain text files on a cloud synced folder<sup> [1](#footnote1)</sup> (edited with any text editor) and a paper notebook. Main structure (check also [how does it look](#how-does-it-look)):

  - folder's structure:

           0.Inbox (temporary storage before deciding what to do with an item)           

           1.Tasks (to store all actionable notes)
             // Used on a paper notebook
             0. Next (tasks to be done ASAP)

             // Used on a cloud synced folder.
             1. Soon (tasks in the queue to get done)
             2. Someday (tasks to get done someday)
             3. Calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)

           2.References (to store all non-actionable notes)



===
###Actionable notes (tasks):

- actionable notes are called **tasks**. All tasks are tagged and managed in one folder.

- tasks should have a due date: **( )**

        Dates are inserted before the task description (allowing chronological sorting):
        
        Example inserting a scheduled date: (year-month-day=hour)
        (2015-11-29=9h) Doctor appointment

        Example inserting a trigger/fuzzy date: (date >>)
        (2015-03-10 >>) Waiting for client feedback after this date

        Example inserting a deadline date: (date <<)
        (2015-10-22 <<) Pay electricity bill until this date

        Example without knowing the due date: (soon) or (someday)
        (soon) Call Mom
        (someday) Bungee jumping with friends



===
###Non-actionable notes (references):

- non-actionable notes are called **references**. All references are managed in one folder.

- projects (and subprojects) should have a reference note to compile info as: a list of tasks (*briefing*), a list of completed tasks (*changelog*) and specific references. Therefore name your notes using [project folders notation](#project-folders):

        Note with all references regarding a particular subproject:
        Example: @house in portugal.building permit

        Suggestion: use reference notes to keep your collection of bookmarks.
        Example: #research@frontend



===
###How to navigate through your notes:

- you only need one *permanent* desktop shortcut to navigate through your documents: 

        Shortcut to NOTES cloud synced folder



===
###How does it look?

- screenshot of Hamster-GTD using Sublime text editor showing calendar folder.

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.PNG)



---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - Google Drive, Dropbox, etc.</sup><br>
<sup><a name="footnote2">2</a> - the hamster cheeks :) [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - e.g. relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote3)</sup>



---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.