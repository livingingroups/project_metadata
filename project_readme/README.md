# Project ReadMe Documentation for MPI-AB Ecology of Animal Societies Projects
***
This is an overview of the basic project ReadMe that our department requires for researchers going out into the field.

## What is a project README file?
Project metadata is data about the project that will be used in an overall database to link related projects, and allow researchers to access resources, data, methods, and information about projects so we know about where they will overlap. 
It is different, but related, to "File Metadata" which is metadata extracted from particular files types (i.e. creation date, file length, camera setrial number) that can be extracted using something like 'exiftool'.

A README file should be saved as a Markdown (.md) or Text (.txt) file, or other plain text readable file. MS Word/PDF is acceptible, but discouraged.

## What goes into a project README file?
README files contain Project Metadata (**Brendan add link here**) that will be comparible across datasets.
They also contain a brief summary of the project and its goals, more detailed information about methods, things that happened in the field, hardware, software and  fieldnotes


## When do I complete my project README file?
In the days and weeks immediately following a field trip or conclusion of a local study/experiment.

## Where can I find examples of project Metadata?
In this file you can find a template:

Below are examples from other reearcher's projects.
1. Kat's Bonobo Project
2. Brendan's Coiba or Woodrat Project


## Read Me Template
0. Project Summary
1. Project Name
2. People
3. Species
4. Location
5. Data Overview
6. Dates
7. Funding Sources
8. Data File Details (*I want a new name*)
9. Hardware
10. Software
11. Methods
12. Field Notes

Items 1-7 are common to all projects
Each csv, yaml, or other plain text file should also have a corresponding `.txt.` file that explains each column and what is in it.
In the case of a csv this would include:

	1. Number of Variables
	2. Number of cases/rows
	3. Variable list
		* list variable name(s), description(s), unit(s) and value labels as appropriate for each
	4. Missing data codes 
		* i.e. symbol/code and definition
	5. Other specialized formats or abbreviations if applicable

Items 0 and 8-12 are project specific. Below summarizes what the are.

### 0. Project Summary
This is a paragraph summary about the project, its history, and general goals
### 8. Data File Details
Each csv, yaml, or other plain text file should also have a corresponding `.txt.` file that explains each column and what is in it.
In the case of a csv this would include:
1. Number of Variables
2. Number of cases/rows
3. Variable list
	* list variable name(s), description(s), unit(s) and value labels as appropriate for each
4. Missing data codes 
	* i.e. symbol/code and definition
5. Other specialized formats or abbreviations if applicable

The goal of this file should be that any reearcher, not knowing what the project is, can pick it up and be able to make sense of what it contains. 

### 9. Hardware

Having an idea of who used what in the field might be ideal to know what things were collected with. 
I am thinking of models of devices where their accuracy, or sensitivty changes over years, with enough of an impact to affect inference 
(i.e. consider accuracy of GPS collars changing oer the years, or sensitivty of camera traps changing with models). 
This matters for analysis.
If this equipment gets checked out from Angie, we can link to that info. 
Otherwise we case have researchers add details.
1. Device Manufacturer and Version (i.e. Reconyx Hyperfire 2 or Garmin Inreach GPSs60)
2. Serial No or internal code (if this matters...)
Some of this data can be extracted from the raw data if need be (i.e. camera model and serial number info using EXIFtool). We should inform where that can be found.

### 10. Software
If special proprietary software or code was used for data collection in the field, info on it should be provided (or links to source code). Examples include:
1. Software name, make, serial number
2. Link to source code
3. Link to form (i.e. if something like ODK or KOBO collect is used)

### 11. Methods
A document describing methods for data collection is worthwhile including, so we know how data came into existence. 
This can go in your paper anyway, and writing it up now will save headache down the line in 10 years once you finally get around to writing these papers we think will just take "a few weeks." This includes:
	1. Sampling Design
	2. Sampling Effort
	3. Animal handling/Collaring Protocols
	
###12. Field Notes
	Having a text file of useful field notes would be a good idea, aprticularly if someone pick up your project or visits your site in the future.
	This can also include helpful contacts (i.e. cab drivers, friends), places(safe places to stay, restaurants), stores (where to get the weird equipment you need in a city).
	Perhaps things related to "the field" vs, the logistics in getting to the field could be separated. 
	This should also include relevant permit numbers. 


