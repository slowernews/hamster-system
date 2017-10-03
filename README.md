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

**TLDR:** 

- [What does this stuff solve?](#tldr)

---
## Organize your (digital) documents
*'Every document belongs to a project'.*

### Container:

- container folder<sup id="refnote1"> [1](#footnote1)</sup>: **YOUR NAME**

        First of all create a folder in a partition of your disk.
        ALL your stuff will be stored there.

- main folders: **PROJECT STATUS**

        Inside your container folder there are 3 folders:

        INBOX (folder to put new documents until deciding what to do with them)
        CURRENT (folder to store your active projects)
        ARCHIVE (folder to store your dormant projects)

---
### Project folders:

*#bundle / @project.subproject / -storage folders*

- bundle of projects (derived from twitter hashtag): **#**

        Inside CURRENT and ARCHIVE folders you store #bundles of projects:
        e.g: #large investor (bundle with all projects of a client)

- project (derived from twitter mention): **@**  

    	Inside #bundle folders you store @projects:
        e.g: @house in portugal    

- subproject (derived from OO programming): **.**

    	Inside #bundle folders or @project folders, you store @project.subprojects:
        e.g: @house in portugal.building permit

- storage folder: **-**

    	Inside @project.subprojects you put -storage-folders:
        e.g: -plans

---
### Naming:

- always reduce unnecessary nesting and memorization by merging folders:

        Use: @house in portugal.building permit
        Instead of: @house in portugal / .building permit

        Use: -drawings-details-wall
        Instead of: -drawings / -details / -wall

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

- archive files using [BranchVer](https://github.com/galfarragem/branchVer) (each version *adds* a change on data): **+ branch . progress**

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch**

---
### How to navigate through your documents:

- you only need two *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to INBOX folder
        Shortcut to CURRENT folder

        A shortcut to archive is not needed, only dormant projects are there.

- and/or a launcher-file finder<sup id="refnote3"> [3](#footnote3)</sup>. 

---
## Organize your workflow
*'Inputs to your workflow are materialized as notes'.*

### Introduction:

- your workflow consists of a collection of plain text notes on a cloud synced folder<sup id="refnote4"> [4](#footnote4)</sup> and notes on a paper notebook.   

- actionable notes are called [tasks](#actionable-notes-tasks); non-actionable notes are called [references](#non-actionable-notes-references).

- workflow management is loosely inspired on GTD, [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) (plain text files) and [Bullet journal](http://bulletjournal.com/) (notes on paper). Files's structure (check also [screenshots](#screenshots)):       

        References (TXT files on a cloud synced folder)

        Tasks
            (on a paper notebook)
            0-next (tasks to be done ASAP)
            1-soon (tasks in the queue to get done)

            (TXT files on a cloud synced folder)
            2-calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)
            3-someday (tasks to get done someday)

---
### Actionable notes (tasks):

- actionable notes are called **tasks**. Time related tasks live within the same file:<br>
Short-term due tasks are managed on a paper notebook.<br>
Long-term due tasks are managed on a cloud synced folder.

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

- non-actionable notes are called **references**  and are managed on a cloud synced folder.

- to guarantee future data exchange and serialization use [YAML](https://www.json2yaml.com/convert-yaml-to-json).

- hint: use reference notes to keep your collection of bookmarks.

---
### How to navigate through your notes:

- use text editor's side bar and built-in search.<sup id="refnote5"> [5](#footnote5)</sup>

---
### Screenshots:

- calendar tasks note on Sublime text editor.<sup id="refnote6"> [6](#footnote6)</sup>

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.PNG)

- [YAML](https://www.json2yaml.com/convert-yaml-to-json) on reference notes for readability and future data serialization.

![hamster-workflow-screenshot-2](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example2.png)

---
## TLDR:
*'What does this stuff solve?'.*

#### Naming system:

- prediction (with acceptable accuracy) of filenames and where they are stored.<br>
A file finder<sup> [3](#footnote3)</sup> is great when you remember the filename but less useful when you don't.

- transmission of project folders with all project files and a predictable structure.

#### Workflow management:

- simple solution: use your favorite text editor, your favorite cloud and a paper notebook. No extra tools.

- practical solution: mix the *good parts* of many workflow management approaches: [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf) (GTD on Evernote), [Todo.txt](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) (notes on TXT files), [Bullet journal](http://bulletjournal.com/) (notes on paper), Inbox Zero and Desktop zero.

- future data exchange and serialization: notes using [YAML](https://www.json2yaml.com/convert-yaml-to-json) notation saved as TXT files.

*'Possible painpoint?'.*

This system is not smartphone oriented. That's not even an issue for me but it might be for you.

---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - the hamster cheeks :) [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - e.g: relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - after having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/) Lite.<br>
Pros: Launch and file search without external software, low memory usage (less than 40k on win7), fast and configurable. Cons: No calculator function. [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - Google Drive, Dropbox, etc. [↩](#refnote4)</sup><br>
<sup><a name="footnote5">5</a> - hint: on Sublime press Ctrl+Shift+F to search all your notes. [↩](#refnote5)</sup><br>
<sup><a name="footnote5">6</a> - hint: on Sublime press F9 (or F5 on Mac) to sort dates. [↩](#refnote6)</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.