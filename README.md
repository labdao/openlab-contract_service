# openlab-contract_service
This repository defines the contract service within the openlab protocol. Service providers run the contract service to validate that API requests coming through the gateway service are valid. A valid request has the following properties: 
* an escrow deposit has been made by the same wallet that has signed the API request to the gateway service
* the job description JSON that was received by the gateway service matches the jobURI referenced in the escrow deposit

