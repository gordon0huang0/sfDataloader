# sfDataloader

Dataloader setup and scripts - Gordon, 03/23/2023

System environments settings:
DATALOADER_JAVA_HOME=E:\SalesforceDownloads\zulu19.32.13-ca-jdk19.0.2-win_x64  //reference to Java home
SAP_DATA_HOME=Y:\S4\ERQ\500\DataLoader\New    //this is SAP data inbound folder
SF_DATALDR_BASE=C:\Users\salesforceadmin\dataloader57\v57.0.1    //dataloader base folder
SF_DATALDR_SYS=ERQ500   //for QA and ERP500 for production

Above settings are required; Scripts will use all above system environment variables

Configuration files need to be reviewed carefully if upgrading to different dataloader versions

See the guide for details: https://developer.salesforce.com/docs/atlas.en-us.dataLoader.meta/dataLoader/data_loader.htm
