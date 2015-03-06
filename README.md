Folder-System
=============

Organize your documents and workflow<sup> 1</sup>. Simple system influenced by [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf), [SemVer](http://www.semver.org/) and [Twitter](https://twitter.com/). 

###So, how to organize myself?

- [Introduction](#introduction)

**Organize your documents (Project-system):**

- [Main folders](#main-folders)
- [Project folders](#project-folders)
- [Files](#files)
- [How to navigate through my documents](#how-to-navigate-through-my-documents)
- [Others](#others)

**Organize your workflow (Action-system):**

- [Actions and lists](#actions-and-lists)

---
####Introduction:

This system is influenced by:

- [GTD](http://amzn.to/1BKSJbz). Resuming: *Everything is* a *project*, an *action* or a *list*.
- [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf), used to manage actions in Evernote.
- [SemVer](http://www.semver.org/), used for file versioning.
- [Twitter](https://twitter.com/)'s concept of *#* and *@*, used for *project* notation.

Without understanding these concepts this system will not make much sense.

---

###Project-system
*Organize your documents*
=================

####Main folders:

**ALL CAPS {project status} [project scope]**

- your main folder: **ALL CAPS**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored inside this folder named with your name 
        or/and surname using ALL CAPS.
        Example: JOHN

- project status: **{ }**

        Inside your main folder there are 3 folders:
        {inbox}, {current} and {archive}

        Resuming:

        {inbox} is the folder where you put new documents until deciding what to do with them.
        {current} is the folder where you store your current projects.
        {archive} is the folder where you store your archived projects.
    
- project scope: **[ ]** 

        Inside folder {inbox} there are no permanent folders, just temporary stuff.

        Inside folder {current} there are 2 folders with project scopes:
        [personal], [work]
    
        Inside folder {archive} there are 2 folders with project scopes and archive symbol: 
        +[personal], +[work]

---
####Project folders:

**# bundle @ project . subproject - folder - nested folder**

- bundle of projects (inspired in twitter hashtag): **#**

        Inside folders [personal], [work] you can have bundles of projects:
        Example: #large investor (bundle with all projects of a client)
        Example: #family (bundle with all your family related projects)

- project (inspired in twitter mention): **@**

    	Inside folders [personal], [work] or bundles you have projects:
        Example: @house in lisbon

        On projects always add bundle name (if existent) to reduce the need of memorization:
        Example: #large investor@house in lisbon

- subproject<sup> 2</sup> (inspired in object oriented programming): **.**

    	Inside projects you can have subprojects:
        Example: .building permit

        On subprojects always add project name to reduce the need of memorization:
        Example: @house in lisbon.building permit

- folder (each nesting level): **-**

    	Inside subprojects you can have folders:
        Example: -plans

        On nested folders always add previous folder(s) name to reduce the need of memorization:
        Example: -drawings-sections
        Example: -drawings-details-wall

---
####Files:

- files named using folders logic or another naming system relevant to your job.

        Example using folder's naming logic: plan+0.1.2
        Example using a naming system relevant to your job: @ARC.EXE-plan+0.1.2

- archived file (each version *adds* a change on data): **+**
        
        Using + and semantic versioning (MAJOR . MINOR . PATCH)
        Example: plan+0.1.2

- prefix for standard / boilerplate files: **$**

        Example: $curriculum+1.1.2
     
---
####How to navigate through my documents:

- you only need 2 *permanent shortcuts* to navigate your files: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't - they are archived projects):
        Shortcut to {archive}

- and some *temporary shortcuts* to specific folders that you use a lot:

		Example: #large investor@house in lisbon
		Example: [work] #large investor
		Example: [personal] #friends
        Example: @house in lisbon.building permit

---
####Others:

- use UpperCamelCase, lowerCamelCase, snake_case or spaces:

        Example using lowerCamelCase: #largeInvestor@houseInLisbon
        Example using UpperCamelCase: #LargeInvestor@HouseInLisbon
        Example using snake_case: #large_investor@house_in_lisbon
        Example using spaces: #large investor@house in lisbon  

- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---

###Action-system
*Organize your workflow*
================

####Actions and lists:

- actions ([GTD concept](http://amzn.to/1BKSJbz)) managed in Evernote using a variant of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf).

- lists are also managed in Evernote. There are 2 types of lists:

        Briefing (list of actions)
        Cabinet (list of references)

- prefix for a finished action (until delete or store it): **%**

        Use it in the beggining of the line to allow sorting:
        Example: % going to bank

- if you need to detail an action (sometimes a file or a folder name):

        Insert a comment: (comment)
        Example with an action: Write a mail to Susy (your comment here)

        Insert a date: (year-month-day=hour)
        You can use it in the beggining of the line to allow chronological sorting.
        Example with an action: (2012-11-29=9h) Doctor appointment
        Example with a file name: plan+1.1.2 (2012-11-29)

---

<sup>Notes:</sup><br>
<sup>1 - This system was tested in a Windows PC and Evernote.</sup><br>
<sup>2 - You can optionally use an underscore instead of a dot but beware of searching dificulties in Evernote.</sup>

---

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Folder-System</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.