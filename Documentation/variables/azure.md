<!-- DO NOT EDIT. THIS FILE IS GENERATED BY THE MAKEFILE. -->
# Terraform variables
This document gives an overview of the variables used in the different platforms of the Tectonic SDK.

## Inputs

| Name | Description | Type | Default |
|------|-------------|:----:|:-----:|
| tectonic_azure_config_version | (internal) This declares the version of the Azure configuration variables. It has no impact on generated assets but declares the version contract of the configuration. | string | `1.0` |
| tectonic_azure_create_dns_zone | If set to true, create an Azure DNS zone | string | `true` |
| tectonic_azure_dns_resource_group |  | string | `tectonic-dns-group` |
| tectonic_azure_etcd_vm_size | Instance size for the etcd node(s). Example: Standard_DS2. | string | `Standard_DS2_v2` |
| tectonic_azure_external_rsg_name | Pre-existing resource group to use as parent for cluster resources. | string | `` |
| tectonic_azure_external_vnet_id | ID of an existing Virtual Network to launch nodes into. Example: VNet1. Leave blank to create a new Virtual Network. | string | `` |
| tectonic_azure_external_vnet_name | Pre-existing virtual network to create cluster into. | string | `` |
| tectonic_azure_image_reference | The image ID as given in `azure image list`. Specifies the OS image of the VM. | map | `<map>` |
| tectonic_azure_location |  | string | - |
| tectonic_azure_master_vm_size | Instance size for the master node(s). Example: Standard_DS2_v2. | string | `Standard_DS2_v2` |
| tectonic_azure_ssh_key | Name of an Azure ssh key to use joe-sfo | string | - |
| tectonic_azure_vnet_cidr_block | Block of IP addresses used by the Resource Group. This should not overlap with any other networks, such as a private datacenter connected via ExpressRoute. | string | `10.0.0.0/16` |
| tectonic_azure_worker_vm_size | Instance size for the worker node(s). Example: Standard_DS2_v2. | string | `Standard_DS2_v2` |
| tectonic_ssh_key |  | string | `` |

