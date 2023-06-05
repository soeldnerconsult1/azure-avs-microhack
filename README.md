![AVS MicroHack](/img/MicroHack_Logo.png)

# Migrating to Azure VMware Solution (AVS) and integration of cloud-native services


## Goals of this microhack

This microhack will enable you to:

- understand Azure VMware solutions (AVS) networking
- migrate on-prem applications to AVS using HCX
- integrate Azure cloud-native services with AVS

## Scenario

In this microhack, you will work with a hybrid environment based on AVS as well as an on-premises environment containing workloads which will be migrated to AVS. After exploring the AVS environment, you will complete the necessary networking and HCX configuration which allows to migrate workloads from on-prem to AVS. Furthermore, you will integrate Azure managed services (such as ...) with your workloads running on AVS in order to build a modern, cloud-native application.

## Instructions

### AVS Labs

1. [Review the lab environment](/docs/ReviewTheLabEnvironment.md)
2. [Create an NSX segment](/docs/2CreateAnNSXSegment.md)
3. [Create VM based on template](/docs/3CreateVMBasedOnTemplate.md)
4. [Publish VM on the internet](/docs/4PublishVMOnTheInternet.md)
5. [Create VPN connection](/docs/5CreateVPNConnection.md)
6. Configure HCX\
	a. [Site Pairing](/docs/6aHCXSitePairing.md)\
	b. [Compute Profile](/docs/6bHCXComputeProfile.md)\
	c. [Network Profile](/docs/6HCXNetworkProfile.md)\
	d. [Service Mesh](/docs/6dHCSServiceMesh.md)
7. [Migrate VM](/docs/7MigrateVM.md)

### Integration with native Azure services

1. Connect to Azure File Share 
2. Using Azure Load Balancer with AVS