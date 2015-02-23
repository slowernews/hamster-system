Folder-System
=============
**# bundle @ project . subproject - folder**

Organize your documents<sup> 1</sup>. Simple system inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf), [Semantic versioning](http://www.semver.org/)<sup> 2</sup> and [Twitter](https://twitter.com/)'s concept of *#* and *@*. 

###So, how to organize my documents?

- [Main folders](#main-folders)
- [Project folders](#project-folders)
- [Files](#files)
- [Archive](#archive)
- [How to navigate through my documents](#how-to-navigate-through-my-documents)
- [Others](#others)

---
####Main Folders:

- your main folder: **ALL CAPS**

        First of all create a folder in a safe place of your disk.
        ALL your stuff will be stored inside this folder named with your name 
        or/and surname using ALL CAPS.
        Example: JOHN

- action time: **{ }**
    
        Inside your main folder there are 3 folders:
        {inbox}, {next actions} and {archive}
    
- action scope: **[ ]** 

        Inside folder {inbox} there are no permanent folders, just temporary stuff.

        Inside folder {next actions} there are 2 folders with action scopes:
        [personal], [work]
    
        Inside folder {archive} there are 2 folders with action scopes and archive symbol: 
        +[personal], +[work]

---
####Project folders:

- bundle of projects (inspired in twitter hashtag): **#**
    
        Inside folders [personal], [work] you can have bundles of projects:
        Example: #large investor (bundle with all projects of a client)
        Example: #family (bundle with all your family related projects)

- project (inspired in twitter mention): **@**
    	
    	Inside folders [personal], [work] or bundles you have projects:
        Example: @house in lisbon

- subproject<sup> 3</sup> (inspired in object oriented programming): **.**
    	
    	Inside projects you can have subprojects:
        Example: .building permit

- folder (each nesting level): **-**
    	
    	Inside subprojects you can have folders:
        Example: -plans
        Example: -drawings--sections

When naming folders you can combine this notation (adding the previous naming level) 
to reduce the need of memorization while navigating:

        Example: #large investor@house in lisbon
        Example: @house in lisbon.building permit
        Example: .building permit-drawings

---
####Files:

- files named using folders logic or another naming system relevant to your job.

        Example using folders logic: plan+v1.0.1.2
        Example using another naming system: @ARC.EXE-plan+v1.0.1.2

- standard file: **$**
    
        Example: $curriculum
        Example: $curriculum+v1.0.1.2

---
####Archive:

- archived folder (just used for main folders): **+**
    
        Example: +[work]
        Example: +[personal]

- archived file (version): **+**
        
        Using + and semantic versioning (MAJOR . MINOR . PATCH)
        Example: plan+v0.1.2

        Using + and a versioning variant (MARKETING RELEASE . MAJOR . MINOR . WORKING FILE)
        Example: plan+v0.1.1.2

---
####How to navigate through my documents:

You only need 2 permanent (and some temporary) *desktop shortcuts* to navigate your files: 
		
- shortcut to *{inbox}*

		{inbox} is the folder where you put new files until deciding what to do with them.
		
- shortcut to *{next actions}*

		{next actions} is the folder where you store your current projects.

- if you use it often (in theory you don't - they are archived projects), a shortcut to *{archive}*

		{archive} is the folder where you store your archived projects.

- *temporary* shortcuts to specific folders that you use a lot.

		Example: #large investor@house in lisbon
		Example: [work] #large investor
		Example: [personal] #friends

---    
####Others: 

- insert a comment: **(comment)**

        Example: Write a mail to Susy (your comment here)

- insert a date: **(year-month-day=hour)**

        Use it in the beggining of the line to allow chronological sorting.
        Example: (2012-11-29=9h) Doctor appointment
        
- name your folders using UpperCamelCase, lowerCamelCase or snake_case: 

        Example using lowerCamelCase: #largeInvestor@houseInLisbon.buildingPermit
        Example using UpperCamelCase: #LargeInvestor@HouseInLisbon.BuildingPermit
        Example using snake_case: #large_investor@house_in_lisbon.building_permit

- or just use spaces, not everybody is a geek:

        Example using spaces: #large investor@house in lisbon.building permit

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---

<sup>Notes:</sup><br>
<sup>1 - This system was tested in a Windows PC and Evernote.</sup><br>
<sup>2 - If you don't know GTD, Secret Weapon and semantic versioning you must read about it first or this system will not make much sense.</sup><br>
<sup>3 - You can optionally use an underscore instead of a dot but beware of searching dificulties in Evernote.</sup>

---

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Folder-System</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.