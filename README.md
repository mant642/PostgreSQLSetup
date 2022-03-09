# PostgreSQLSetup
Personal walkthrough of gettting started with PostgreSQL 

## Loading Sample Database
1. Make sure PostgreSQL is installed w/ pgAdmin included, as well as a sample database downloaded 
2. Go to Servers > Databases > Create > Database. Be sure to give the database a unique name. 
3. Go to Servers > Databases > DatabaseName > Restore > and select the sample database previously downloaded. *Note: In the case of version 14, attempting to use the restore command resulted in a "Utility Not Found" error. To resolve, it was necessary to go to File > Preferences > Binary paths > PostgreSQL Binary Path and specify the path to the bin folder that contained all the necessary utilities*
