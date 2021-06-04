# CustomActivities
Custom Activity to capture the latest files metadata on a SFTP host

* The custom activity will capture the metadata of the latest delivered file to an SFTP host directory and write the metadata back to an Azure SQL table.

* This was written as a workaround for the Azure Data Factory off-the-shelf metadata activity, which cannot capture the metadata of the latest delivered file on the SFTP host. 
Subsequently, this data can be looked up by a Lookup activity and consume the relevant file using a Copy activity
