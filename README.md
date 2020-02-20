# Batch-v3-API-Go
Golang script to send batch tasks to Prism Central 

Batch API Script golang V3 

This script sends batch v3 API calls to Prism Central to perform a set of tasks. The tasks are defined in the batch_request.json file. 

User, password  login details for Prism Central in the script need to be updated. 
You also need to edit the Prism Central VIP in the code. After the above updates are done code can be built or run directly. 

The script requires batch_request.json as file as this file contains the payload for the Batch call. 
You can leave the file in the same directory as the go binary or point the code to the file location during run time. 

Usage Image: 

 

Please note the json payload file contains a cluster reference that needs to be edited ; it needs to include Cluster uuid and cluster name for the PE cluster on which the create VM task will be executed . Cluster uuid can be obtained by running “ncli cluster info” from PE CVM or from Prism UI
