# Hamster system

Boost productivity and reduce stress by organizing your documents, workflow and personal budget with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Todo.txt](https://github.com/todotxt/todo.txt), OBTF (One Big Text File), [Bullet journal](http://bulletjournal.com/) (notes on paper), spreadsheets, index cards, inbox zero and desktop zero.

### So, how can you start?

- [hamster folder](#hamster-folder): organize your (digital) documents
- [hamster flow](#hamster-flow): organize your workflow
- [hamster budget](#hamster-budget): organize your money

**TLDR:** 

- [What does this stuff solve?](#tldr)




---
## Hamster folder
### Organize your (digital) documents

*'Every document belongs to a project'.*

### Container:

- root folder: **YOUR NAME**

        First of all create a folder in a partition of your disk.
        ALL your stuff will be stored here.

- main folders: **PROJECT STATUS**

        Inside your root folder there are 2 folders:

        INBOX (folder to store your active projects)
        ARCHIVE (folder to store your inactive projects - often organized in bundles)

---
### Project folders:

*[bundle] #project @subproject -folders*

- bundle of projects: **[ ]**

        Inside ARCHIVE folder you put [bundles of projects]:
        e.g: [large investor]

- project (derived from twitter hashtag): **#**  

        Inside INBOX, ARCHIVE or [bundle] folders you put #projects:
        e.g: #house in portugal    

- subproject (derived from twitter mention): **@**

        Inside #project folders you put @subprojects:
        e.g: @building permit

- storage folder: **-**

        Inside @subprojects you put -storage folders:
        e.g: -drawings

---
### Naming:

- use a system that fits your needs<sup id="refnote1"> [1](#footnote1)</sup>. Some hints:

        Prefix for template / boilerplate files: $
        e.g: $curriculum

        Prefix for folders where you keep stuff temporarly: _
        e.g: _standby

        Prefix for folders where you keep old versions of files: +

- version files by using a *modification date* suffix<sup id="refnote2"> [2](#footnote2)</sup>: **Calendar Versioning**

        e.g: yourfile-2019-10-18
        e.g: yourfile+20191018

- when reasonable reduce unnecessary nesting by merging folders. Hints:

        Prefer: #project@onlyOneSubproject
        Instead of: #project / @onlyOneSubproject

        Prefer: -drawings-details-wall
        Instead of: -drawings / -details / -wall

---
### How to navigate through your documents:

- you only need one *permanent* desktop shortcut to navigate through your documents: 

        Shortcut to INBOX folder

        A shortcut to ARCHIVE is optional - only inactive projects are there.

- and/or a launcher-file finder<sup id="refnote3"> [3](#footnote3)</sup>. 




---
## Hamster flow
### Organize your workflow

*'Manage a collection of inputs'.*

- One text file<sup id="refnote4"> [4](#footnote4)</sup> and a paper notebook collect all inputs:  
    - actionable inputs (*Tasks*) are managed in the paper notebook. Non-urgent tasks eventually move to the *Calendar* section of the text file<sup id="refnote5"> [5](#footnote5)</sup>.
    - non-actionable inputs are managed in a (Markdown) text file. Hints:
        - One long file is easier to manage than many short files.<sup id="refnote6"> [6](#footnote6)</sup> See it as a *flat wiki* and use built-in search for navigation.
        - This file is not *write-only*: progressively summarize and *tree-shake* it each time you iterate your notes. You'll leverage your excitement instead of forcing discipline.
        - Ideally, notes are organized by *project*, not by category. It can be a catalyst for action and reviews.
        - Only store things that surprise you, not stuff you already know.

- Tasks listed in the *Calendar* section of the text file have a due date: **[ ]**

        Dates are inserted before the task description (allowing chronological sorting):
        
        e.g. inserting a scheduled date: [year-month-day=hour]
        [2020-11-29=9h] Doctor appointment

        e.g. inserting a trigger/fuzzy date: [date >>]
        [2020-10-10 >>] Waiting for client feedback after this date

        e.g. inserting a deadline date: [date <<]
        [2020-10-22 <<] Pay electricity bill until this date

        e.g. without knowing the due date: [soon] or [someday]
        [soon] Call Mom
        [someday] Bungee jumping with friends

- Resuming (check also [screenshots](#screenshots)):

        on a paper notebook:
            Tasks (collection of tasks to be done ASAP)

        on a text file with 2 sections:
            Calendar (collection of tasks that can/must wait)
            Notes (collection of thoughts and bookmarks)

---
### Screenshots:

- *Calendar* section on Sublime text editor.<sup id="refnote7"> [7](#footnote7)</sup>

![superfolder-workflow-screenshot](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example.png)

- Easy text-editor navigation with Markdown (adaptable to [YAML](https://www.json2yaml.com/convert-yaml-to-json) for data serialization).

![superfolder-workflow-screenshot-2](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example2.png)




---
## Hamster budget
### Organize your money

*'You may not need a personal budget'.*

Does it worth to spend cognitive bandwidth to know that last month I spent €321,83 on groceries? I already know that I spend *around* €300. **What I crave is to feel in control of my finances.**

How to do it in a practical way? Track your **net worth** in a spreadsheet:
 
- List all your assets (bank, ebank, stocks, funds, crypto, real estate, whatever) and sum them. List and sum your liabilities (if relevant). Every case is a case so you must build your template from zero.
- When your net worth is too risky *for your personality* get more tight.
- When you feel confortable with your number you can loosen up a bit.
- I used to track it every month. I loosen up to every quarter.

### Organize your investments

To keep some control over your finances and still invest nothing beats *Barbell investment strategy*. I use a loose version of it.




---
## TLDR:

#### What does this stuff solve?

*hamster folder: organize your (digital) documents*

- transmission of projects with a predictable structure.
- prediction (with acceptable accuracy) of filenames and their location. A file finder is great when you remember the filename but less useful when you don't.

*hamster flow: organize your workflow*

- Simple and practical: mix the *good parts* of  many workflow management approaches using your favorite text editor, cloud and a paper notebook. Use  Markdown that can be adapted into [YAML](https://learn-the-web.algonquindesign.ca/topics/markdown-yaml-cheat-sheet/) for data exchange and serialization.

*hamster budget: organize your money*

- simple and practical: *feel in control* of your finances using just a couple of hours every quarter. Minimum overhead.

#### Possible painpoint?

This system is not smartphone oriented. That's not even an issue for me but it might be for you. My strategy, when a paper notebook is not enough (and most times it is), is to email myself the new stuff and take care of it later.

#### Is this the truth?

Probably not but I test new options and 'tree shake' existent ones agressively.<sup id="refnote8"> [8](#footnote8)</sup>

---
<sup>Footnotes:</sup><br>
<sup><a name="footnote1">1</a> - e.g: relevant [naming system for architects](https://github.com/slowernews/archi-project). I use a great [free tool for batch renaming](https://www.bulkrenameutility.co.uk/#mainscreen). [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - After a long trial, "builds" were deprecated. "Modification dates", aka [Calendar versioning (CalVer)](https://calver.org/) are more practical and descriptive. [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - After having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/). Pros: Launch and file search without external software, low memory usage (less than 40Mb on win7), fast and configurable. Cons: No calculator function. [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - Hosted in a cloud (Google Drive, Dropbox, etc) if possible. [↩](#refnote4)</sup><br>
<sup><a name="footnote5">5</a> - A full featured calendar (Google calendar, Apple calendar, etc) might pay off in certain cases. [↩](#refnote5)</sup><br>
<sup><a name="footnote6">6</a> - Try to keep it under 2K lines. If you can't, it means that some excerpts should live independently or even in a more suitable format (e.g. spreadsheet) [↩](#refnote6)</sup><br>
<sup><a name="footnote7">7</a> - Hint: on Sublime press F9 (or F5 on Mac) to sort dates. [↩](#refnote7)</sup><br>
<sup><a name="footnote8">8</a> - Org-mode, Roam research, Johnny-decimal (...) [↩](#refnote8)</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hamster-System</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
