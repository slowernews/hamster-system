Hamster-GTD
===========

Organize your documents and workflow. Boost productivity while reducing your stress with an ultra-simple implementation of [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup> 1</sup> using [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup> 5</sup>.

###So, how can you start?

**Organize your (digital) documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Naming](#naming)
- [Archiving](#archiving)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actions](#actions)
- [Briefings](#briefings)
- [Notes](#notes)
- [How does it look?](#how-does-it-look)

---
###// Organize your (digital) documents

===
####Main folder:

*MAIN FOLDER {project status} [project scope]*

- main folder<sup> 2</sup>: **YOUR NAME**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored there.

- project status: **{ }**

        Inside your main folder there are 3 folders:

        {inbox} folder where you put new documents until deciding what to do with them.
        {current} folder where you store your current projects.
        {archive} folder where you store your archived projects.
    
- project scope: **[ ]** 

        Inside:

        {inbox} there aren't permanent folders, just temporary stuff.
        {current} and {archive} there are 2 folders: [personal], [work]
        Inside these folders you will store your projects.

===
####Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (derived from twitter hashtag): **#**

        Inside folders [personal], [work] you can have bundles of projects:
        Example: #large investor (bundle with all projects of a client)
        Example: #family (bundle with all your family related projects)

- project<sup> 3</sup> (derived from twitter mention): **@**

    	Inside folders [personal], [work] or bundles you have projects:
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

- use camelCase, PascalCase or spaces<sup> 4</sup>:

        Example using camelCase: #largeInvestor@houseInLisbon
        Example using PascalCase: #LargeInvestor@HouseInLisbon
        Example using spaces: #large investor@house in lisbon  

- but don't use these symbols for regular naming: **# @ . - + $ % { } [ ]**

- name your files using the same rules (or other file naming system relevant to you).
- suggestions:
  - use a prefix for standard / boilerplate files: **$**

          Example: $curriculum+A007

  - great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

===
####Archiving:

- archive releases of (sub)projects using [SemVer](http://www.semver.org/)<sup> 6</sup> (each version *adds* a change on data): **+ major . minor . progress**

- archive files using [BranchVer](https://github.com/eniomauro/branchVer) (each version *adds* a change on data):**+ branch . progress**

===
####How to navigate through your documents:

- you only need 2 *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary* desktop shortcuts to specific folders that you use a lot.

---
###// Organize your workflow

===
####Introduction:

- for workflow management, Hamster-GTD uses a simplified version of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf)<sup> 1</sup> based in  [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup> 5</sup>.<br>
Main differences (check also [how does it look](#how-does-it-look)):

  - different notebook structure:

           1.Inbox (temporary storage before deciding what to do with an item)
           2.Actions (to store all actions)
           3.Briefings (to store all briefings)
           4.Notes (to store all notes/project references)
  
  - simplified *.When* tags for *actions*:

           1-Soon (actions in the queue to get done)
           2-Someday (actions to get done someday)
           3-Calendar (actions with a precise/deadline date or with a trigger/fuzzy date to get done)
           
  - next actions to be done are listed in a paper notebook. This list is fed mostly by *1-Soon* tag.

- resuming, in Hamster-GTD:

  - undivisible tasks are called [Actions](#actions).
  - lists of actions are called [Briefings](#briefings).
  - non-actionable items are called [Notes](#notes).

####Actions:

- undivisible tasks are called *actions*. All actions are tagged and managed in one Evernote notebook.

- every action should have a due date: **( )**

        Dates are inserted before the action description (allowing chronological sorting):
        
        Example inserting a strict date: (year-month-day=hour)
        (2015-11-29=9h) Doctor appointment

        Example inserting a trigger/fuzzy date: (date >>)
        (2015-03-10 >>) Waiting for client feedback after this date

        Example inserting a deadline date: (date <<)
        (2015-10-22 <<) Pay electricity bill until this date

        Example without knowing the due date: (soon) (someday)
        (soon) Call Mary
        (someday) Holydays in North Pole

####Briefings:

- a list of actions is called *briefing*. Briefings are managed in one Evernote notebook.

####Notes:

- non-actionable items are called *notes*. To simplify and optimize your workflow, notes are managed in one major Evernote notebook (and not inside local project folders).

- name your notes using project folders notation:

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

- suggestion: use notes to keep your collection of bookmarks. It will allow easy access and share:

		Example: @bookmarks.frontend-bootstrap

####How does it look?

- screenshot of Hamster-GTD using Evernote (*briefings* notebook).

![hamster-workflow-screenshot](https://github.com/we-build-dreams/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.png)

- screenshot of Hamster-GTD using Evernote (*calendar* tag).

![hamster-workflow-screenshot2](https://github.com/we-build-dreams/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example2.PNG)

---
<sup>Notes:</sup><br>
<sup>1 - without understanding it, this system will not make much sense.</sup><br>
<sup>2 - the hamster cheeks :)</sup><br>
<sup>3 - in GTD any document belongs to a project.</sup><br>
<sup>4 - snake_case is not recommended due to search difficulties in Evernote software.</sup><br>
<sup>5 - other note taking apps might work also.</sup><br>
<sup>6 - other archiving systems, depending on your needs, might be used also or even recommended.</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
