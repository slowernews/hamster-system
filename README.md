SUPERFOLDER
-----------

Boost productivity and reduce stress by organizing your documents and workflow with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Todo.txt](https://github.com/todotxt/todo.txt) (notes on TXT files), OBTF (One Big Text File), [Bullet journal](http://bulletjournal.com/) (notes on paper), index cards, Inbox and Desktop zero.

### So, how can you start?

- [organizing your (digital) documents](#how-to-organize-your-digital-documents)
- [organizing your workflow](#how-to-organize-your-workflow)

**TLDR:** 

- [What does this stuff solve?](#tldr)




---
## How to organize your (digital) documents
*'Every document belongs to a project'.*

### Container:

- superfolder: **YOUR NAME**

        First of all create a folder in a partition of your disk.
        ALL your stuff will be stored here.

- main folders: **PROJECT STATUS**

        Inside your superfolder there are 3 folders:

        INBOX (folder to put new documents until deciding what to do with them)
        CURRENT (folder to store your active projects)
        ARCHIVE (folder to store your dormant projects)

---
### Project folders:

*#bundle @project .subproject -folders*

- bundle of projects (derived from twitter hashtag): **#**

        Inside CURRENT and ARCHIVE folders you put #bundles of projects:
        e.g: #large investor

- project (derived from twitter mention): **@**  

        Inside #bundle folders you put @projects:
        e.g: @house in portugal    

- subproject (derived from OO programming): **.**

        Inside #bundles or @project folders you put @project.subprojects:
        e.g: @house in portugal.building permit

- storage folder: **-**

        Inside @project.subprojects you put -storage folders:
        e.g: -drawings
        e.g: -drawings-plans

---
### Naming:

- when reasonable reduce unnecessary nesting by merging folders:

        Prefer: @house in portugal.building permit
        Instead of: @house in portugal / .building permit

        Prefer: -drawings-details-wall
        Instead of: -drawings / -details / -wall

- name your files using a system that fits you<sup id="refnote1"> [1](#footnote1)</sup>. Hints:

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

- archive files using BranchVer (each version *adds* a change on data): **+ branch . progress**

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch**

---
### How to navigate through your documents:

- you only need two *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to INBOX folder
        Shortcut to CURRENT folder

        A shortcut to archive is not needed, only dormant projects are there.

- and/or a launcher-file finder<sup id="refnote2"> [2](#footnote2)</sup>. 




---
## How to organize your workflow
*'Managing a workflow consists on managing a collection of inputs'.*

- 3 plain text files on a cloud synced folder<sup id="refnote3"> [3](#footnote3)</sup> and a paper notebook collect all inputs:  
    - actionable inputs (todos) are managed in one text file and one paper notebook: calendar and now.
    - non-actionable inputs are managed in two text files: references and notes. Few long notes are easier to manage than many short notes. See them as *flat wikis* and use text editor's built-in search for navigation<sup id="refnote4"> [4](#footnote4)</sup>.

- todos listed in the calendar text file have a due date: **( )**

        Dates are inserted before the task description (allowing chronological sorting):
        
        e.g. inserting a scheduled date: (year-month-day=hour)
        (2017-11-29=9h) Doctor appointment

        e.g. inserting a trigger/fuzzy date: (date >>)
        (2017-03-10 >>) Waiting for client feedback after this date

        e.g. inserting a deadline date: (date <<)
        (2017-10-22 <<) Pay electricity bill until this date

        e.g. without knowing the due date: (soon) or (someday)
        (soon) Call Mom
        (someday) Bungee jumping with friends

- resuming (check also [screenshots](#screenshots)):

        on a cloud synced folder - 3 text files:
            Notes (collection of thoughts)
            References (collection of bookmarks)
            Calendar (collection of todos that can/must wait)

        on a paper notebook:
            Now (collection of todos to be done ASAP)

---
### Screenshots:

- calendar file on Sublime text editor.<sup id="refnote5"> [5](#footnote5)</sup>

![superfolder-workflow-screenshot](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example.png)

- [YAML](https://www.json2yaml.com/convert-yaml-to-json) on references file for readability and future data serialization.

![superfolder-workflow-screenshot-2](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example2.png)




---
## TLDR:
*'What does this stuff solve?'*

#### Naming system:

- prediction (with acceptable accuracy) of filenames and where they are stored.<br>
A file finder<sup> [2](#footnote3)</sup> is great when you remember the filename but less useful when you don't.

- transmission of project folders with all project files and a predictable structure.

#### Workflow management:

- simple solution: use your favorite text editor and cloud, a paper notebook and almost no syntax. Minimum overhead.

- practical solution: mix the *good parts* of [many workflow management approaches](#superfolder).

- future data exchange and serialization: [YAML](https://www.json2yaml.com/convert-yaml-to-json) notation saved as TXT files.

*'Possible painpoint?'*

This system is not smartphone oriented. That's not even an issue for me but it might be for you.

*'Is this the truth?'*

Probably not but I don't know nothing that works better. I test new options and 'tree shake' existent ones agressively.

---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - e.g: relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - after having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/) Lite.<br>
Pros: Launch and file search without external software, low memory usage (less than 40k on win7), fast and configurable. Cons: No calculator function. [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - Google Drive, Dropbox, etc. [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - hint: on Sublime press Ctrl+Shift+F to search all your notes. [↩](#refnote4)</sup><br>
<sup><a name="footnote5">5</a> - hint: on Sublime press F9 (or F5 on Mac) to sort dates. [↩](#refnote5)</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">SUPERFOLDER</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
