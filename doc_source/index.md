# AWS Storage Gateway User Guide

-----
*****Copyright &copy; 2019 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is AWS Storage Gateway?](WhatIsStorageGateway.md)
   + [How AWS Storage Gateway Works (Architecture)](StorageGatewayConcepts.md)
+ [Getting Started](GettingStarted.md)
   + [Sign Up for AWS Storage Gateway](GettingStartedSignUpStep1-common.md)
   + [Regions](available-regions-intro.md)
   + [Requirements](Requirements.md)
   + [Accessing AWS Storage Gateway](WhatIsAPIIntro.md)
+ [Using the AWS Storage Gateway Hardware Appliance](HardwareAppliance.md)
   + [Setting Up Your Hardware Appliance](appliance-quick-start.md)
   + [Rack-Mount Your Hardware Appliance and Connect It to Power](appliance-rack-mount.md)
   + [Configure Network Parameters](appliance-configure-network.md)
   + [Activate Your Appliance](appliance-activation.md)
   + [Launch a Gateway](appliance-launch-gateway.md)
   + [Configure an IP Address for the Gateway](appliance-configure-ip.md)
   + [Configure Your Gateway](appliance-configure-gateway.md)
   + [Remove a Gateway](appliance-remomve-gateway.md)
+ [Creating Your Gateway](create-gateways.md)
   + [Creating a File Gateway](create-file-gateway.md)
      + [Creating a Gateway](create-gateway-file.md)
      + [Creating a File Share](GettingStartedCreateFileShare.md)
         + [Creating an NFS File Share](CreatingAnNFSFileShare.md)
         + [Creating an SMB File Share](CreatingAnSMBFileShare.md)
      + [Using Your File Share](getting-started-use-fileshare.md)
         + [Mounting Your NFS File Share on Your Client](GettingStartedAccessFileShare.md)
         + [Mounting Your SMB File Share on Your Client](using-smb-fileshare.md)
         + [Working with File Shares on a Bucket with Pre-exisiting Objects](FileSharePrexistingObjects.md)
         + [Testing Your File Gateway](GettingStartedTestFileShare.md)
         + [Where Do I Go from Here?](GettingStartedWhatsNextStep3File.md)
   + [Creating a Volume Gateway](create-volume-gateway-volume.md)
      + [Creating a Gateway](create-volume-gateway.md)
      + [Creating a Volume](GettingStartedCreateVolumes.md)
      + [Using Your Volume](GettingStarted-use-volumes.md)
      + [Backing Up Your Volumes](backing-up-volumes.md)
   + [Creating a Tape Gateway](create-tape-gateway.md)
      + [Creating a Gateway](create-gateway-vtl.md)
      + [Creating Tapes](GettingStartedCreateTapes.md)
      + [Using Your Tape Gateway](GettingStarted-create-tape-gateway.md)
         + [Using Your Backup Software to Test Your Gateway Setup](GettingStartedTestGatewayVTL.md)
            + [Testing Your Setup by Using Arcserve Backup r17.0](backup-arcserve.md)
            + [Testing Your Setup by Using Bacula Enterprise](backup-bacula.md)
            + [Testing Your Setup by Using Commvault](backup-commvault.md)
            + [Testing Your Setup by Using Dell EMC NetWorker](backup-emc.md)
            + [Testing Your Setup by Using IBM Spectrum Protect](backup-tsm.md)
            + [Testing Your Setup by Using Micro Focus (HPE) Data Protector](backup-hpdataprotector.md)
            + [Testing Your Setup by Using Microsoft System Center Data Protection Manager](backup-DPM.md)
            + [Testing Your Setup by Using NovaStor DataCenter/Network](backup-novastor.md)
            + [Testing Your Setup by Using Quest NetVault Backup](backup-netvault.md)
            + [Testing Your Setup by Using Veeam Backup & Replication](backup-Veeam.md)
            + [Testing Your Setup by Using Veritas Backup Exec](backup-BackupExec.md)
            + [Testing Your Setup by Using Veritas NetBackup](backup_netbackup-vtl.md)
         + [Where Do I Go from Here?](GettingStartedWhatsNextStep3-vtl.md)
+ [Managing Your Gateway](managing-gateway-common.md)
   + [Managing Your File Gateway](managing-gateway-file.md)
   + [Managing Your Volume Gateway](managing-volumes.md)
   + [Managing Your Tape Gateway](managing-gateway-vtl.md)
+ [Monitoring Your Gateway and Resources](Main_monitoring-gateways-common.md)
   + [Monitoring Your File Share](monitoring-file-gateway.md)
   + [Monitoring Your Volume Gateway](GatewayMetrics-common.md)
   + [Monitoring Your Tape Gateway](GatewayMetrics-vtl-common.md)
   + [Logging Storage Gateway API Calls with AWS CloudTrail](logging-using-cloudtrail.md)
+ [Maintaining Your Gateway](maintaining-gateway.md)
   + [Shutting Down Your Gateway VM](MaintenanceShutDown-common.md)
   + [Managing Local Disks for Your AWS Storage Gateway](ManagingLocalStorage-common.md)
   + [Managing Bandwidth for Your Gateway](MaintenanceUpdateBandwidth-common.md)
   + [Managing Gateway Updates Using the AWS Storage Gateway Console](MaintenanceManagingUpdate-common.md)
   + [Performing Maintenance Tasks on the Local Console](manage-on-premises.md)
      + [Performing Tasks on the VM Local Console (File Gateway)](manage-on-premises-fgw.md)
      + [Performing Tasks on the Amazon EC2 Local Console (File Gateway)](ec2-local-console-fwg.md)
      + [Performing Tasks on the VM Local Console (Volume and Tape Gateways)](manage-on-premises-common.md)
      + [Performing Tasks on the Amazon EC2 Local Console (Volume and Tape Gateways)](ec2-local-console-common.md)
      + [Accessing the Gateway Local Console](accessing-local-console.md)
      + [Configuring Network Adapters for Your Gateway](configure-multi-nic.md)
   + [Deleting Your Gateway by Using the AWS Storage Gateway Console and Removing Associated Resources](deleting-gateway-common.md)
+ [Performance](Performance.md)
+ [Security](security.md)
   + [Configuring CHAP Authentication for Your Volumes](GettingStartedConfigureChap.md)
   + [Encrypting Your Data Using AWS Key Management Service](encryption.md)
   + [Authentication and Access Control for AWS Storage Gateway](UsingIAMWithStorageGateway.md)
      + [Overview of Managing Access Permissions to Your AWS Storage Gateway](managing-access-overview.md)
      + [Using Identity-Based Policies (IAM Policies) for AWS Storage Gateway](using-identity-based-policies.md)
      + [AWS Storage Gateway API Permissions: Actions, Resources, and Conditions Reference](sg-api-permissions-ref.md)
+ [Troubleshooting Your Gateway](Troubleshooting-common.md)
   + [Troubleshooting On-Premises Gateway Issues](GatewayTroubleshooting.md)
   + [Troubleshooting Your Microsoft Hyper-V Setup](ResourceConfigureHostHyperV-troubleshooting.md)
   + [Troubleshooting Amazon EC2 Gateway Issues](EC2GatewayTroubleshooting.md)
   + [Troubleshooting Hardware Appliance Issues](hardware-appliance-issues.md)
   + [Troubleshooting File Share Issues](file-share-issues.md)
   + [Troubleshooting Volume Issues](troubleshoot-volume-issues.md)
   + [Troubleshooting Virtual Tape Issues](Main_TapesIssues-vtl.md)
   + [Best Practices for Recovering Your Data](recover-data-from-gateway.md)
+ [Additional AWS Storage Gateway Resources](Resources.md)
   + [Host Setup](resource-vm-setup.md)
      + [Configuring VMware for Storage Gateway](configure-vmware.md)
      + [Synchronizing Your Gateway VM Time](MaintenanceTimeSync-hyperv.md)
      + [Deploying a Volume or Tape Gateway on an Amazon EC2 Host](ec2-gateway-common.md)
      + [Deploying File Gateway on an Amazon EC2 Host](ec2-gateway-file.md)
   + [Volume Gateway](resource-volume-gateway.md)
      + [Removing Disks from Your Gateway](add-remove-disks.md)
      + [Adding and Removing Amazon EBS Volumes for Your Gateway Hosted on Amazon EC2](GatewayInstanceStorage-common.md)
   + [Tape Gateway](resource-tapegateway.md)
      + [Working with VTL Devices](resource_vtl-devices.md)
      + [Working With Tapes](managing-virtual-tapes-vtl.md)
   + [Getting an Activation Key for Your Gateway](get-activation-key.md)
   + [Connecting iSCSI Initiators](initiator-connection-common.md)
   + [Using AWS Direct Connect with AWS Storage Gateway](using-dx.md)
   + [Port Requirements](Resource_Ports.md)
   + [Connecting to Your Gateway](getting-ip-address.md)
   + [Understanding AWS Storage Gateway Resources and Resource IDs](storage-gateway-resource-id.md)
   + [Tagging Storage Gateway Resources](tagging-resources-common.md)
   + [Working with Open-Source Components for AWS Storage Gateway](AboutAWSStorageGatewaySoftware.md)
   + [AWS Storage Gateway Limits](resource-gateway-limits.md)
   + [Using Storage Classes](storage-classes.md)
+ [API Reference for AWS Storage Gateway](AWSStorageGatewayAPI.md)
+ [Document History for AWS Storage Gateway](DocumentHistory.md)