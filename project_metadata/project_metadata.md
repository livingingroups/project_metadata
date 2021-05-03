# Project Metadata for MPI-AB Ecology of Animal Societies Projects

Here is an overview of the basic project metadata that our department requires for researchers going out into the "field".
For many of us this means trips where we travel away from Konstanz, but for some of us it may mean things we do in the Barn in Möggigen, captivity, or locally.
Those projects may have some additional requirements which we can address at a later time, or with input from those who work in these contexts.

## What is project metadata?
Project metadata is data about the project that will be used in an overall database to link related projects, and allow researchers to access resources, data, methods, and information about projects so we know about where they will overlap. 
It is different, but related, to "File Metadata" which is metadata extracted from particular files types (i.e. creation date, file length, camera setrial number) that can be extracted using something like 'exiftool'.

## How will we use Project Metadata
Projects will be tagged with metadata available from a specified list available on a Github repository.
If new metadata needs to be added to a project, that can be passed to Angie(?) and uploaded additionally. 
It will be key to make sure metadata ID from a specified list to that indexing is consistent across file types.
Hashing could be key to the succes of this.

When a researcher returns from the field all of their raw data should be uploaded to:
`/EAS_shared/project_folder/working/UPLOADS/` 
on the server. The name of the folder should be your project name. The data will only be here temporarily while you are organizing it.
The **Data Catalog Entry Form** should be updated and sent to Angie. This form will contain project metadata.

This project metadata file should also be linked to a Project README **(add link, future Brendan)**. These two files are closely linked, but the information in the `project_metadata` file will be used to link comparisons across all the project datasets over the lifetime of the department.
For example, say a hypothetical someone wanted to do a ambitious multi-site comparaitve study on white-faced capuchin monkeys in 20 years and wants to see all department data/projects that involves capuchins.

Imagine someone want to see all the projects/papers that were funded by a particular gran or performed by a person.

This will able us to connect the dots over the years and make sense of the data without needing to go to that researcher directly.

## Where does it go
A central Github repository TBD and/or on the server.

## Project Metadata Types
1. Project Name
	Projects should have name(s) associate with them. This should be the name on the server folders. 

2. People
For each person we should have:
	1. Name
	2. Institution 
	3. Email
	4. Role 
		1. PI
		2. Collaborators
		3. HIWIs
		4. Field Assistants 
		5. Lab Assistant 
		6. Analyst
	5. Dates in Field

It might be worth considering have  a website, twitter, email or other means of contacts as institutions change or if working with folks locally (i.e. WhatsApp or Address)

3. Species
	1. common name in English
	2. local name at field site
	3. Scientific name (*Genus species*)

4. Locations
	1. Country
	2. State/Province/Region
	3. Name of protected area or research station if applicable
	4. Lat/Long

5. Data Overview
Data should have some ideal file format name *which group 1 is discussing*, and an inventory of raw data files by name. This can be in the document, or linked to another file. Having yyyy_mm_dd  of day collected/deployed in filename might be a standard we use for all files (if applicable). Each file should have an name followed by an extension, and a description of what it is

	1. Example File Types (use extensions)
		1. .txt
		2. .csv
		3. .md
		4. .yaml
		5. .json
		6. .gpx
		7. .tiff (or other spatial formats)
		8. .mp4 (or other video formats)
		9. .mp3 (or other audio formats)
		10. .pdf (i.e. scans)
		11. .tex
	2. Data Type Description
		1. Behavioral (focal follows, scans, etc., annotations)
		2. Movement (gps collar, telemetry data, accelerometer)
		3. Vocalizations
		4. Ecological (i.e. species, plant surveys, soil samples)
		5. Climatic 
		6. Camera Trap
		7. Spatial (i.e. GPS)
		8. Drone Imagery
		
6. Dates
	1. Field Trip Duration
	2. Data Collection Duration
	
7. Funding sources
	1. Grants and Fellowships that contributed to paying for this project or giving researchers salaries.	


