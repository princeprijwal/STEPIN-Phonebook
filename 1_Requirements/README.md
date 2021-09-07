# Requirements 

## Introduction 
In this project the user is able to access a phone book directory that will can be accessed by only authoried owners and can do various functions like input the list of names and their info and can modify it.

## Objective 

The main objectives of this project are: 
* To write all the importnt info about a person
* To perform search to find the info.
* To modify any changes in their infos.
* To delete anyone or person's credentials if they want.

## SWOT ANALYSIS
## Strength
* Can only be accessed by authorized person
* Can save details of any identity info for future reference.
* Can Modify any input by inputting their name.
* Can Delete any info directly by giving the name of the person.
## Weakness
* if the Input name is of same name and u want to search nd modify it it will show you the 1st one and neglect the second one.
* if user input the same name on 2 different info it will delete both.
## Opportunities
* It will be helpful to save the registry for future thet will have the info's of your important ones.
## Threats
* if you have written the name wrong you cannnot modify it as name is acting as a primary key.

## ***4 W's and 1 H***
## Who
Anyone who have the Password can access the Project.
## What
This project is concerned about saving the important info about persons for our purpose.
## When 
Whenever there is a need for finding any person credentials they can access this.
## Why
This project will be helpful tokepp a record of person's info for future purpose.
## How
Implemented using structure, pointers, enum and other functionalities of C.

Basic requirements that are very essential are:
* gcc compiler with a good system.
* Any of the two - linux/windows.

## HIGH LEVEL REQUIREMENTS:

|ID|DESCRIPTION|CATEGORY|STATUS|
|:-----|:--------------------------------|:----------------|:----------|
|HR01|Only Authorized Users can be able to access it.|Technical|Implemented|
|HR02|Users shall be able to write their info of a new person.|Technical|Implemented|
|HR03|User shall be able to Search any person credentials.|Technical|Implemented|
|HR04|User shall be able to List all the info of every person.|Technical|Implemented|
|HR05|User should be able to Modify any info of a person.|Technical|Implemented|
|HR06|User can delete any person info.|Technical|Implemented|
|HR07|Can modify only the one's that user want and not all info to write again|Technical|Future|

## LOW LEVEL REQUIREMENTS:

### VALIDATION
|ID|FUNCTIONS|DESCRIPTION|HLR ID|STATUS|
|:-------|:-------|:-------|:-------|:-------|
|LR01|password|checks if the user is authorized by password barrier|HR01|Implemented|
|LR02|password|If paswword is incorrect it will Exit the project|HR01|Implemented|

### BASIC OPERATIONS
|ID|FUNCTIONS|DESCRIPTION|HLR ID|STATUS|
|:-------|:-------|:-------|:-------|:-------|
|LR03|namefun|Enter all the Details about a person i.e. Name(imp),Address,Gender,Email,Mobile no.|HR02|Implemented|
|LR04|modifyfun|Input the name and then can change the Details i.e. Address,Gender,Email,Mobile no.|HR04|Implemented|
|LR05|searchfun|Input the name and then you can find all the details about that name.|HR03|Implemented|
|LR06|deletefun|Input the name of the person you want to delete the info of.|HR02_03|Implemented|