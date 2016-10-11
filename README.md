Hamster-GTD
===========

Organize your documents and workflow with simple conventions. Boost productivity while reducing your stress with an ultra-simple system inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup id="refnote1"> [1](#footnote1)</sup> using [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup id="refnote4"> [4](#footnote4)</sup> and a paper notebook.

###So, how can you start?

**Organize your (digital) documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Naming](#naming)
- [Archiving](#archiving)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actionable notes: Tasks](#actionable-notes-tasks)
- [Non-Actionable notes: References](#non-actionable-notes-references)
- [How does it look?](#how-does-it-look)

---
##Organize your (digital) documents
*'Every document belongs to a project'.*

===
###Main folder:

*MAIN FOLDER / PROJECT STATUS*

- main folder<sup id="refnote2"> [2](#footnote2)</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- project status: **PROJECT STATUS**

        Inside your main folder there are 3 folders:

        INBOX folder where you put new documents until deciding what to do with them.
        CURRENT folder where you store your current projects.
        ARCHIVE folder where you store your archived projects.

===
###Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (derived from twitter hashtag): **#**

        Inside folders {current} and {archive} you have bundles of projects:
        Example: #large investor (bundle with all projects of a client)

- project (derived from twitter mention): **@**

    	Inside bundle folders you have projects:
        Example: @house in lisbon

        To reduce the need of memorization, when naming the project folder
        you might add the bundle name (if existent):
        Example: #large investor@house in lisbon

- subproject (derived from OO programming): **.**

    	Inside projects you can have subprojects:
        Example: .building permit

        To reduce the need of memorization, when naming the subproject folder
        you might add the project name:
        Example: @house in lisbon.building permit

- folder (each nesting level): **-**

    	Inside subprojects you can have folders:
        Example: -plans

        On nested folders you might add previous folder(s) name to reduce memorization:
        Example: -drawings-sections
        Example: -drawings-details-wall

===
###Naming:

- use spaces or other naming style<sup id="refnote3"> [3](#footnote3)</sup>:

        Example using spaces: #large investor@house in lisbon
        Example using camelCase: #largeInvestor@houseInLisbon
        Example using PascalCase: #LargeInvestor@HouseInLisbon

- but don't use these symbols for regular naming: **# @ . - + $ % { } [ ]**

- name your files using the same rules (or other file naming system relevant to you).

- enclose folder's name to mark it as private: **[ ]**

        Example: [#personal] (private bundle with all your personal related projects)

- use a prefix for standard / boilerplate files: **$**

        Example: $curriculum+A007

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

===
###Archiving:

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch**

- archive files using [BranchVer](https://github.com/galfarragem/branchVer) (each version *adds* a change on data): **+ branch . progress**

===
###How to navigate through your documents:

- you only need 2 (or 3) *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary* desktop shortcuts to specific folders that you use a lot.

---
##Organize your workflow
*'Inputs to your workflow are materialized as notes'.*

===
###Introduction:

- actionable notes are called [Tasks](#actionable-notes-tasks); non-actionable notes are called [References](#non-actionable-notes-references).

- workflow management is made using a simplified version of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf)<sup id="refnote1"> [1](#footnote1)</sup> for  [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup id="refnote4"> [4](#footnote4)</sup> and a paper notebook. Main differences (check also [how does it look](#how-does-it-look)):

  - different Evernote notebook's structure:

           0.Inbox (temporary storage before deciding what to do with an item)
           1.Tasks (to store all actionable notes)
           2.References (to store all non-actionable notes)
  
  - simplified *.When* tags for *actions*:

           // Used on a paper notebook
           0-Next (tasks to be done ASAP)
           
           // Used on Evernote
           1-Soon (tasks in the queue to get done)
           2-Someday (tasks to get done someday)
           3-Calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)

===
###Actionable notes (Tasks):

- actionable notes are called **tasks**. All tasks are tagged and managed in one Evernote notebook.

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
###Non-actionable notes (References):

- non-actionable notes are called **references**. All references are managed in one major Evernote notebook.

- projects (and subprojects) should have a reference note to compile info as: a list of tasks (*briefing*), a list of completed tasks (*changelog*) and specific references. Therefore name your notes using [project folders notation](#project-folders):

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

		Suggestion: use notes to keep your collection of bookmarks.
		Example: #research@frontend

===
###How does it look?

- screenshot of Hamster-GTD using Evernote (*calendar* tag).

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example2.PNG)

---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - without understanding it, this system will not make much sense. [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - the hamster cheeks :) [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - snake_case is not recommended due to search difficulties in Evernote software.  [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - other note taking apps might work also. [↩](#refnote4)</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
