Running these scripts
	* GetInactiveDevices.ps1 
          * Needs to be run on a machine with SCCM database access and requires SQL Server read rights. 
          * SqlServerDatabase – required parameter that indicates the SCCM database to query for inactive devices.
	* RemoveEasIdentities.ps1 
          * Needs to be run on a machine with Exchange access and requires Exchange admin privileges, specifically the rights to execute the Remove-ActiveSyncDevice cmdlet. 
          * EasIdentitiesFile – required parameter that specifies the location of the CSV file that contains the identities of the devices to remove. 
          * ConfirmRemoval – required parameter that indicates whether to confirm the removal of devices.
