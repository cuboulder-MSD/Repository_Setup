# Repository_Setup
Notes on repository input and use.
## File structure:
### Repository name: digColl_collectionName
#### digColl_ 
 • repositories containing digital collections metadata. Use camel case for collection name. Collections in LUNA have a repository in GitHub, but new ones will have to be added as they come in. Prefix for digital collections metadata repositories is always digColl¬¬_ to distinguish them from whatever else might be in there. 
#### geolibrary 
 • metadata in the GeoLibrary
#### dp_  
 • prefix for other code used for some process in the digital projects workflow, including python processing tools, XMl conversion tools, and code for other projects.
#### ad_ 
 • prefix for code contributed by Access & Discovery folks. 
### README.md (created directly on the GitHub page)
metadata
###                csv
###                xml
 • Our objective is to keep this organized, but pretty flat so it’s easy to understand and access.
 
## File naming policy
### CSV: digColl_collectionName_YYYYMMDD.csv
 • Follows naming convention in GitHub so it’s easy to tell what and where from which it came.

• Date of metadata creation/export from LUNA is in the file name for version tracking.
### XML: Will document later.
 • Erik has a method he’s using, and we’ll document this at a later point after we get the ARK server running and a workflow embedded in our processes.
 
## README contents:
### Collection Title
 • Same as used for the collection in the digital collections platform (LUNA)
### Description
 • Pulled from the collection description in LUNA, which is provided by Collection managers in archives.

• If there is another finding aid out there that you’re aware of, it’s good to add a link below the description.

o   ArchiveSpace link (to the top level of the collection)

o   Other finding aids – example: Maps built a map-based finding aid for the Aerial Photographs collection.  
### Metadata
 • Go field by field and provide a brief description so folks know what’s what. Stuff like “Title” will be standard across collections. 

  Let’s start by coming up with descriptions for each field in the MODS template we’re using for new collections: https://docs.google.com/spreadsheets/d/13IA6klq5Ri5F2Or0aNXvzlmYYgcedf7lfNMGN2wKJg4/edit#gid=0

• A more specific note can be provided after the standard one if you deem it appropriate for the data set to explain nuances in how the data might have been acquired or entered for this particular set.

o   This is a kind of almost gold-standard data dictionary that has been insanely useful in interpreting a data set I used on a project for a museum some time ago. It’s WAAAAAAAAY beyond what we need to do, but it’s good to keep some of what they do in mind (see page 8 for data fields descriptions. We won’t number ours, but it’s a great example for the kind of short descriptions we’re aiming for.) https://data.world/datamil/thor-data-dictionary
### Resources
 • Links and resources used in the creation of the metadata. Provide these if a special controlled vocabulary was used in the creation of the metadata. Likewise, if a book or other website was used heavily to figure out what was what inside the metadata (people, places, or things), provide the information with a brief description of how it was used.
### Notes
 • Broad notes about the subject content, or additional background to the topic. Keep it fairly high level, unless there’s something very notable in the collection. Use this field to augment the Description if you feel the need.

• Good place to point out surprising original content we have in a collection.
