Hamster-GTD
===========

Organize your documents and workflow. Boost productivity while reducing your stress with an ultra-simple implementation of [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup> 1</sup> using [Evernote](https://www.evernote.com/referral/Registration.action?sig=3ce24e3db69e37fbf772dab92921127b&uid=52016286)<sup> 5</sup>.

###So, how can you start?

**Organize your documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Files](#files)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)
- [Others](#others)

**Organize your workflow:**

- [Introduction](#introduction)
- [Actions](#actions)
- [Briefings](#briefings)
- [Cabinet](#cabinet)
- [How does it look?](#how-does-it-look)

---
###// Organize your documents

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
####Files:

- name your files using folders notation (or other file naming system relevant to you).

- archive files using [SemVer](http://www.semver.org/)<sup> 6</sup> (each version *adds* a change on data): **+ major . minor . patch**
        
        Example: plan+0.1.2

- prefix for standard / boilerplate files: **$**

        Example: $curriculum+1.1.2  

===
####How to navigate through your documents:

- you only need 2 *permanent* desktop shortcuts to navigate your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary* desktop shortcuts to specific folders that you use a lot.

===
####Others:

- use camelCase, PascalCase or spaces<sup> 4</sup>:

        Example using camelCase: #largeInvestor@houseInLisbon
        Example using PascalCase: #LargeInvestor@HouseInLisbon
        Example using spaces: #large investor@house in lisbon  

- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**
- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---
###// Organize your workflow

===
####Introduction:

- in Hamster-GTD:
  - undivisible tasks are called *actions*.
  - a list of actions is called *briefing*.
  - non-actionable items are called *notes* or *references*.

- for workflow management, Hamster-GTD uses a simplified version of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf)<sup> 1</sup>.<br>
Main differences (check also [how does it look](#how-does-it-look)):

  - different notebook structure:

           1.Inbox (temporary storage before deciding what to do with an item)
           2.Actions (to store all actions)
           3.Briefings (to store all briefings)
           4.Cabinet (to store all notes/project references)
  
  - simplified *.When* tags for *actions*:

           1-Next (next actions to be done)
           2-Soon (actions in the queue to get done)
           3-Someday & maybe (actions to get done later/someday & maybe)
           4-Waiting (actions with a trigger/fuzzy date to get done)
           5-Calendar (actions with a precise/deadline date to get done)

####Actions:

- undivisible tasks are called *actions*. Actions are managed in one Evernote<sup> 5</sup> notebook.
- if you need to detail an action add a comment: **( )**

        Comments are inserted after the action description.
        Example: Write a mail to Susy (your comment here)

        Dates are inserted before the action description (allowing chronological sorting):
        
        Example inserting a strict date: (year-month-day=hour)
        (2015-11-29=9h) Doctor appointment

        Example inserting a trigger/fuzzy date: (date >>)
        (2015-03-10 >>) Waiting for client feedback after this date

        Example inserting a deadline date: (date <<)
        (2015-10-22 <<) Pay electricity bill until this date

####Briefings:

- a list of actions is called *briefing*. Briefings are managed in one Evernote notebook.

####Cabinet:

- to simplify and optimize your workflow, items for reference that aren’t actionable (project references and notes) are always stored here (not inside project folders) and managed in one Evernote major notebook.

- name your notes using project folders notation:

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

- suggestion: use notes to keep your bookmark collections. It will allow easy access and share:

		Example: @resources.frontend-bootstrap

####How does it look?

- screenshot of Hamster-GTD using Evernote.

![hamster-workflow-screenshot](https://github.com/we-build-dreams/hamster-gtd/blob/master/examples/hamster-workflow_screenshot%20example.png)

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
