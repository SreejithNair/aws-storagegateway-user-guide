# Testing Your Gateway Setup<a name="GettingStartedTestGatewayVTL"></a>

You test your tape gateway setup by performing the following tasks using your backup application:

1. Configure the backup application to detect your storage devices\.
**Note**  
To improve I/O performance, we recommend setting the block size of the tape drives in your backup application to 128 KB, 256 KB, or 512 KB\. For more information, see [Use a Larger Block Size for Tape Drives](Optimizing-common.md#block-size)\.

1. Back up data to a tape\.

1. Archive the tape\.

1. Retrieve the tape from the archive\.

1. Restore data from the tape\. 

To test your setup, use a compatible backup application, as described following:

+ [Testing Your Setup by Using Arcserve Backup r17\.0](backup-arcserve.md)

+ [Testing Your Setup by Using Backup Exec](backup-BackupExec.md)

+ [Testing Your Setup by Using Commvault ](backup-commvault.md)

+ [Testing Your Setup by Using Quest NetVault Backup](backup-netvault.md)

+ [Testing Your Setup by Using Dell EMC NetWorker](backup-emc.md)

+ [Testing Your Setup by Using HPE Data Protector](backup-hpdataprotector.md)

+ [Testing Your Setup by Using Microsoft System Center 2012 R2 Data Protection Manager](backup-DPM.md)

+ [Testing Your Setup by Using Symantec NetBackup Version 7\.x](backup_netbackup-vtl.md)

+ [Testing Your Setup by Using Veeam Backup & Replication](backup-Veeam.md)

For more information about compatible backup applications, see [Supported Third\-Party Backup Applications for a Tape Gateway](Requirements.md#requirements-backup-sw-for-vtl)\.