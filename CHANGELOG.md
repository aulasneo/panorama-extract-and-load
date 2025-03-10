# Change log

## Version 0.3.2 (2025-02-19)
Fix bug that crashes when there is no data in a problem

## Version 0.3.1 (2024-03-04)
Fix requirements versions

## Version 0.3.0 (2023-09-26)
Add problem weight to course structures

## Version 0.2.4 (2023-09-04)
Refactor get_structures to fix a bug that impacts courses reruns
## 0.2.3
Fix bug that prevented the first course to be considered
## 0.2.2
Fix bug to consider course structure records with empty active version id.
## 0.2.1
Fix small bug
## 0.2
Use `split_modulestore_django_splitmodulestorecourseindex` table
to get the list of active versions of the courses, instead of mongodb.
## 0.1.6
Fix a bug in date parsing
## 0.1.5
Allow "value" key in the fields definition to override the field with a constant value.
The field will not be queried, but will be filled with the constant value. 
E.g., can be set to 'null' if a field is missing the the DB but still needed in the datalake.

Fix bug
## 0.1.4
Fix bug in date parsing
Fix connection to MongoDB: use direct connection and secondaryPreferred to avoid issues in certain clusters
Reorganize packages
Create and document Dockerfile
## 0.1.3
Add support for xls file datasources
Add set-tables command to query the datasources for existing tables and update the settings
## 0.1.2
Add support for csv file datasource
## 0.1.1
Complete refactor of the modules and the settings file.
Now datasource and datalake settings are more clearly decoupled.
## 0.0.1
Initial version
