# Project Metadata for MPI-AB Ecology of Animal Societies Projects
***
Here is an overview of the basic project metadata that our department requires for researchers going out into the "field".
For many of us this means trips where we travel away from Konstanz, but for some of us it may mean things we do in the Barn in Möggigen, captivity, or locally.
Those projects may have some additional requirements which we can address at a later time, or with input from those who work in these contexts.

## What is project metadata?
Project metadata is data about the project that will be used in an overall database to link related projects, and allow researchers to access resources, data, methods, and information about projects so we know about where they will overlap. 
It is different, but related, to "File Metadata" which is metadata extracted from particular files types (i.e. creation date, file length, camera setrial number) that can be extracted using something like 'exiftool'.

## How will we use Project Metadata
Projects will be tagged with metadata available from a specified list available on a Github repository.
If new metadata needs to be added to a project, that can be passed to Angie(?) and uploaded additionally. 
It will be key to make sure metadata id from a specified list to that indexing is consistent across file types.

## Where does it go
A central Github repository. This one perhaps, in a folder.

## Project Metadata Types
1. People
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

2. Species
	1. common name in English
	2. local name at field site
	3. Scientific name (*Genus species*)

3. Locations
	1. Country
	2. State/ Province/Region
	3. Name of protected area or research station if applicable
	4. Lat/Long

4. Data 
Data should have some ideal file format name, and an inventory of data files by name. Having yyyy_mm_dd  of day collected/deployed in filename might be a standard we use for all files (if applicable). 

	1. File Types (use extensions)
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
	2. Data Types
		1. Behavioral (focal follows, scans, etc., annotations)
		2. Movement (gps collar, telemetry data, accelerometer)
		3. Vocalizations ()
		4. Ecological (i.e. species, plant surveys, soil samples)
		5. Climatic 
		6. Camera Trap
		7. Spatial (i.e. GPS)
		8. Drone Imagery
		9. ...Add more...

	3. ReadMe MetaData (to go with files and explain what each column is.

5. Hardware
Having an idea of who used what in the field might be ideal to know what things were collected with. 
I am thinking of models of devices (i.e. consider accuracy of GPS changing oer the years. 
This matters for analysis.
If this equipment gets checked out from Angie, we can link to that info. 
Otherwise we case have researchers add details.
	1. Device Manufacturer and Version (i.e. Reconyx Hyperfire 2 or Garmin Inreach GPSs60)
	2. Serial No or internal code (if this matters...)
6. Software
	If special proprietary software or code was used for data collection in the field, info on it should be provided (or links to source code).
6. Project Name
	Projects should have name(s) associate with them. This should be the name on the server folders. 
7. Dates
	1. Field Trip Duration
	2. Data Collection Duration
8. Methods
	A document describing methods for data collection might be worthwhile including, so we know how data came into existence. 
	This can go in your paper anyway, and writing it up now will save headache down the line in 10 years once you finally get around to writing these papers we think will just take "a few weeks."
9. Field Notes
	Having a text file of field notes would be a good idea. 
	This can also include helpful contacts (i.e. cab drivers, friends), places(safe places to stay, restaurants), stores (where to get the weird equipment you need in a city).
	Perhaps things related to "the field" vs, the logistics in getting to the field could be separated.
10. Funding sources
	1. Grants and Fellowships that contributed to paying for this project	


