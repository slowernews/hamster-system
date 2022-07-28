# Hamster system

Boost productivity and reduce stress by organizing your documents, workflow and personal budget with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Todo.txt](https://github.com/todotxt/todo.txt), OBTF (One Big Text File), [Bullet journal](http://bulletjournal.com/) (notes on paper), spreadsheets, index cards, inbox zero and desktop zero.

### So, how can you start?

- [hamster folder](#hamster-folder---organize-your-documents): organize your (digital) documents
- [hamster flow](#hamster-flow---organize-your-workflow): organize your workflow
- [hamster budget](#hamster-budget---organize-your-money): organize your money
- [TLDR - what does this stuff solve?](#tldr)




---
## Hamster folder - organize your documents

*'Every document belongs to a project'.*

### Container

- root folder: **YOUR NAME**

        First of all create a folder in a partition of your disk.
        ALL your stuff will be stored here.

- main folders: **PROJECT STATUS**

        Inside your root folder there are 2 folders:

        INBOX (folder to store your active projects)
        ARCHIVE (folder to store your inactive projects - often organized in collections)

### Project folders

*[collection] #project @subproject -folders*

- collection: **[ ]**

        Inside ARCHIVE folder you put [collection] folders:
        e.g: [large investor]

- project (derived from twitter hashtag): **#**  

        Inside INBOX, ARCHIVE or [collection] folders you put #project folders:
        e.g: #house in portugal    

- subproject (derived from twitter mention): **@**

        Inside #project folders you put @subproject folders:
        e.g: @building permit

- storage folder [^1]: **-**

        Inside @subprojects you put -storage folders:
        e.g: -drawings

And be pragmatic:

        When reasonable reduce unnecessary nesting by merging folders:
        Prefer: #project@onlyOneSubproject
        Instead of: #project / @onlyOneSubproject

        Prefix for temporary folders: _
        e.g: _standby

        Folders to keep old versions of files: +
        e.g: -plans / +

### File naming

- use a system that fits your needs[^2]. Some hints:

        Prefix for template / boilerplate files: $
        e.g: $curriculum

- version files by using a *modification date* suffix[^3]: **Calendar Versioning**

        e.g: yourfile+20211018

### Navigation

- you only need one *permanent* desktop shortcut to navigate through your documents: 

        Shortcut to INBOX folder

        A shortcut to ARCHIVE is optional - only inactive projects are there.

- and/or a launcher-file finder[^4]. 




---
## Hamster flow - organize your workflow

*'Manage a collection of inputs'.*

- One text file[^5] and a paper notebook collect all inputs:  
    - actionable inputs (*Tasks*) are managed in the paper notebook. Non-urgent tasks eventually move to the *Calendar* section of the text file[^6].
    - non-actionable inputs are managed in the (markdown) text file. Hints:
        - One long file is easier to manage than many short files.[^7] See it as a *flat wiki* and use built-in search for navigation.
        - This file is not *write-only*: progressively summarize and *tree-shake* it each time you iterate your notes. You'll leverage your excitement instead of forcing discipline.
        - Ideally, notes are organized by *project*, not by category. It can be a catalyst for action and reviews.
        - Only store things that surprise you, not stuff you already know.

- Tasks listed in the *Calendar* section of the text file have a due date: **[ ]**

        Dates are inserted before the task description (allowing chronological sorting):
        
        e.g. inserting a scheduled date: [year-month-day=hour]
        [2021-11-29=9h] Doctor appointment

        e.g. inserting a trigger/fuzzy date: [date >>]
        [2021-10-10 >>] Waiting for client feedback after this date

        e.g. inserting a deadline date: [date <<]
        [2021-10-22 <<] Pay electricity bill until this date

        e.g. without knowing the due date: [soon] or [someday]
        [soon] Call Mom
        [someday] Bungee jumping with friends

- Resuming (check also [screenshots](#screenshots)):

        on a paper notebook:
            Tasks (collection of tasks to be done ASAP)

        on a text file with 2 sections:
            Calendar (collection of tasks that can/must wait)
            Notes (collection of thoughts and bookmarks)

### Screenshots

- *Calendar* section on Sublime text editor.[^8]

![superfolder-workflow-screenshot](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example.png)

- Easy text-editor navigation with markdown (adaptable to [YAML](https://www.json2yaml.com/convert-yaml-to-json) for data serialization).

![superfolder-workflow-screenshot-2](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example2.png)




---
## Hamster budget - organize your money

*'You may not need a personal budget'.*

Does it worth to spend cognitive bandwidth to know that last month I spent €321,83 on groceries? I already know that I spend *around* €300. **What I crave is to feel in control of my finances.**

**How to do it in a practical way? Track your net worth** in a spreadsheet:
 
- List all your assets (cash, stocks, bonds, crypto, real estate, whatever) and sum them. List and sum your liabilities (if relevant). Every case is a case so you must build your own spreadsheet.
- When your net worth is too risky *for your personality* get more tight.
- When you feel confortable with your number you can loosen up a bit.
- I used to track it every month. I've loosen up to every quarter and eventually to semiannual.[^9]




---
## TLDR:

### What does this stuff solve?

Complicated systems always fail on the long-term. Hamster-system aims to be *simple and practical*.

- Hamster folder (organize your documents)
    - Transmission of projects with a predictable structure.
    - Prediction (with acceptable accuracy) of filenames and their location. A file finder is great when you remember the filename but less useful when you don't.

- Hamster flow (organize your workflow)
    - Mix the *good parts* of  many workflow management approaches using your favorite text editor, cloud and a paper notebook. Markdown - if necessary - can be adapted into formats like [YAML](https://learn-the-web.algonquindesign.ca/topics/markdown-yaml-cheat-sheet/) to facilitate data exchange and serialization.

- Hamster budget (organize your money)
    - *Feel in control* of your finances spending a couple of hours every quarter. Minimum overhead.

### Possible painpoint?

This system doesn't have specialized apps nor I plan to add any. However, it is platform agnostic so you can easily adapt it to meet your needs.

### Is this the truth?

Probably not but I test new options and *tree shake* existent ones agressively.[^10]

---

[^1]: This is the deepest level you'll get. It's enough and keeps it simple.
[^2]: e.g: relevant [naming system for architects](https://github.com/slowernews/archi-project). I use a great [free tool for batch renaming](https://www.bulkrenameutility.co.uk/#mainscreen).
[^3]: After a long trial, Semver and then "builds" were deprecated. "Modification dates", aka [Calendar versioning (CalVer)](https://calver.org) are simpler.
[^4]: After having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/). Pros: Launch and file search without external software, low memory usage (less than 40Mb on win7), fast and configurable. Cons: No calculator function.
[^5]: Hosted in a cloud (Google Drive, Dropbox, etc) if possible.
[^6]: A full featured calendar (Google calendar, Apple calendar, etc) may pay off in "busy" lifestyles.
[^7]: Try to keep it under 2K lines. If you can't, it may mean some excerpts should live independently or even in a more suitable format (e.g. spreadsheet or [public notes](https://github.com/slowernews/notebook)).
[^8]: Hint: on Sublime press F9 (or F5 on Mac) to sort dates.
[^9]: I will stop here. Longer timeframes imply too delayed signals.
[^10]: Org-mode, «wiki notes» (Roam, Foam, Obsidian), Johnny-decimal, (...)

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hamster-System</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
