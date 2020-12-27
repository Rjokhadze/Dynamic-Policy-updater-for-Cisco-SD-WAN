[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/sdwan-policy-automation)

# Cisco SD-WAN Policy automation with REST API

This Github repo contains python code that can be used to interact with the SD-WAN vManage. Using this code, networks advertised from vEdge/cEdges to the vSmart controller can be automatically populated to create dynamic ACL, which will be provisioned back to cEdge/vEdges to filter or steer traffic using the information written in ACL.


# Requirements

To use this code you will need:

* Python 3.7+
* vManage credentials.
* vManage API Token 

# Install and Setup

- Clone the code to local machine.

```
git clone https://github.com/Rjokhadze/Dynamic-Policy-updater-for-Cisco-SD-WAN.git
```

## Example:
Modify the {vmanage_host} with a correct IP address of the vManage controller
Modify the {vsmart-RID} with a correct Router-ID of the vSmart controller
Search for the (Range of Site-ID) in the code and modify with desired range
Modify the {datalistID} with a correct data prefix list ID
Modify the {PolicyID} with a correct vSmart data policy ID



## Scenarios

Link to the blogpost to see the code in action - https://packetstack.wordpress.com/2020/01/28/cisco-sd-wan-policy-automation-with-rest-api/
