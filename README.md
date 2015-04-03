Hamster-GTD
===========


Organize your documents and workflow. An ultra-simple implementation of [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup> 1</sup><sup> 2</sup>, using:

- [Twitter](https://twitter.com/)'s concept of *#* and *@* as the basis of the project folders notation.
- [SemVer](http://www.semver.org/) for file versioning.
- [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf) for workflow management in Evernote.

###So, how can you start?

**Organize your documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Files](#files)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)
- [Others](#others)

**Organize your workflow:**

- [Actions and briefings](#actions-and-briefings)
- [Cabinet](#cabinet)

---
###// Organize your documents

===
####Main folder:

*YOUR MAIN FOLDER {project status} [project scope]*

First of all create a folder in a safe place of your disk.
ALL your stuff will be stored here - the hamster cheeks :)

- your main folder: **YOUR NAME**

		Rename your folder with your name or/and surname using ALL CAPS.
        Example: JOHN

- project status: **{ }**

        Inside your main folder there are 3 folders:

        {inbox} is the folder where you put new documents until deciding what to do with them.
        {current} is the folder where you store your current projects.
        {archive} is the folder where you store your archived projects.
    
- project scope: **[ ]** 

        Inside:

        {inbox} there aren't permanent folders, just temporary stuff.
        {current} there are 2 folders: [personal], [work]
        {archive} there are 2 folders with archive symbol: +[personal], +[work]

        Inside these 2 folders with project scopes we will store our projects.

===
####Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (inspired in twitter hashtag): **#**

        Inside folders [personal], [work] you can have bundles of projects:
        Example: #large investor (bundle with all projects of a client)
        Example: #family (bundle with all your family related projects)

- project<sup> 3</sup> (inspired in twitter mention): **@**

    	Inside folders [personal], [work] or bundles you have projects:
        Example: @house in lisbon

        On projects you can add bundle name (if existent) to reduce the need of memorization:
        Example: #large investor@house in lisbon

- subproject<sup> 4</sup> (inspired in object oriented programming): **.**

    	Inside projects you can have subprojects:
        Example: .building permit

        On subprojects you can add project name to reduce the need of memorization:
        Example: @house in lisbon.building permit

- folder (each nesting level): **-**

    	Inside subprojects you can have folders:
        Example: -plans

        On nested folders always add previous folder(s) name to reduce the need of memorization:
        Example: -drawings-sections
        Example: -drawings-details-wall

===
####Files:

- files named using folders logic or other naming system relevant to your job.

        Example using folder's naming logic: plan+0.1.2
        Example using other naming system: @ARC.EXE-plan+0.1.2

- archived file using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch** 
        
        Example: plan+0.1.2

- prefix for standard / boilerplate files: **$**

        Example: $curriculum+1.1.2  

===
####How to navigate through your documents:

- you only need 2 *permanent desktop shortcuts* to navigate your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary desktop shortcuts* to specific folders that you use a lot.

===
####Others:

- use camelCase, PascalCase, snake_case or spaces:

        Example using camelCase: #largeInvestor@houseInLisbon
        Example using PascalCase: #LargeInvestor@HouseInLisbon
        Example using snake_case: #large_investor@house_in_lisbon
        Example using spaces: #large investor@house in lisbon  

- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---
###// Organize your workflow

===
####Actions and briefings:

- in GTD, undivisible tasks are called *actions*. A list of actions is called *briefing*<sup> 5</sup>. Actions and briefings are managed in Evernote using a variant of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf).

- if you need to detail an action: **( )**

        Insert a comment: (comment)
        Example: Write a mail to Susy (your comment here)

        Insert a date: (year-month-day=hour)
        You can use it in the beggining of the line to allow chronological sorting.
        Example: (2012-11-29=9h) Doctor appointment

- prefix for a finished action (before delete or store it): **%**

        Use it in the beggining of the line to allow sorting:
        Example: % going to bank

####Cabinet:

- to simplify and optimize your workflow, your project references and notes are always stored here (not inside project folders). They are also managed in Evernote using a variant of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf).

- name your notes using project folders notation:

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

---
<sup>Notes:</sup><br>
<sup>1 - Without understanding GTD, this system will not make much sense.</sup><br>
<sup>2 - Hamster-gtd was tested in a Windows PC and Evernote.</sup><br>
<sup>3 - In GTD any document belongs to a project.</sup><br>
<sup>4 - You can optionally use an underscore instead of a dot but beware of searching dificulties in Evernote.</sup><br>
<sup>5 - Innovation by Hamster-gtd.</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.