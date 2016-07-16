Hamster-GTD
===========

Organize your documents and workflow. Boost productivity while reducing your stress with an ultra-simple implementation of [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup> 1</sup> using [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup> 5</sup> and a paper notebook.

###So, how can you start?

**Organize your (digital) documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Naming](#naming)
- [Archiving](#archiving)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actionable items: Tasks](#actionable-items-tasks)
- [Non-Actionable items: Notes](#non-actionable-items-notes)
- [How does it look?](#how-does-it-look)

---
###// Organize your (digital) documents

===
####Main folder:

*MAIN FOLDER {project status}*

- main folder<sup> 2</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- project status: **{ }**

        Inside your main folder there are 3 folders:

        {inbox} folder where you put new documents until deciding what to do with them.
        {current} folder where you store your current projects.
        {archive} folder where you store your archived projects.

===
####Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (derived from twitter hashtag): **#**

        Inside folders {current} and {archive} you have bundles of projects:
        Example: #large investor (bundle with all projects of a client)

- project<sup> 3</sup> (derived from twitter mention): **@**

    	Inside bundle folders you have projects:
        Example: @house in lisbon

        To reduce the need of memorization, when naming the project folder
        you might add the bundle name (if existent):
        Example: #large investor@house in lisbon

- subproject (derived from object oriented programming): **.**

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
####Naming:

- use spaces or other naming style<sup> 4</sup>:

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
####Archiving:

- archive releases of (sub)projects using a simplified [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor**

- archive files using [BranchVer](https://github.com/galfarragem/branchVer) (each version *adds* a change on data): **+ branch . progress**

===
####How to navigate through your documents:

- you only need 2 (or 3) *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary* desktop shortcuts to specific folders that you use a lot.

---
###// Organize your workflow

===
####Introduction:

- for workflow management, Hamster-GTD uses a simplified version of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf)<sup> 1</sup> for  [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup> 5</sup> and a paper notebook. Main differences (check also [how does it look](#how-does-it-look)):

  - different Evernote notebook's structure:

           0.Inbox (temporary storage before deciding what to do with an item)
           1.Tasks (to store all actionable items)
           2.Notes (to store all non actionable items)
  
  - simplified *.When* tags for *actions*:

           // Used on a paper notebook
           0-Next (tasks to be done ASAP)
           
           // Used on Evernote
           1-Soon (tasks in the queue to get done)
           2-Someday (tasks to get done someday)
           3-Calendar (tasks with a precise/deadline date or with a trigger/fuzzy date to get done)

- resuming, in Hamster-GTD:

  - actionable items are called [Tasks](#actionable-items-tasks).

  - non-actionable items are called [Notes](#non-actionable-items-notes)

===
####Actionable items (Tasks):

- actionable items are called **tasks**. All tasks are tagged and managed in one Evernote notebook.

- every task should have a due date: **( )**

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
####Non-actionable items (Notes):

- non-actionable items are called **notes**. To simplify and optimize your workflow, notes are managed in one major Evernote notebook (and not inside local project folders).

- each project (or subproject) should have a note to compiles info as: a list of future tasks (*briefing*), a list of past tasks (*changelog*) or specific *references*. Therefore name your notes using [project folders notation](#project-folders):

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

		Suggestion: use notes to keep your collection of bookmarks. It will allow easy access and share:
		Example: #research@frontend

===
####How does it look?

- screenshot of Hamster-GTD using Evernote (*calendar* tag).

![hamster-workflow-screenshot](https://github.com/galfarragem/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example2.PNG)

---
<sup>Notes:</sup><br>
<sup>1 - without understanding it, this system will not make much sense.</sup><br>
<sup>2 - the hamster cheeks :)</sup><br>
<sup>3 - in GTD any document belongs to a project.</sup><br>
<sup>4 - snake_case is not recommended due to search difficulties in Evernote software.</sup><br>
<sup>5 - other note taking apps might work also.</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
