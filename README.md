# Hydra's Deployment on Fabric testbed 

This repository contains the notebook for the Farbic environment configuration, Fabric slice requestion and setup for Hydra's deployment.
[Fabric](https://fabric-testbed.net/) is a nationwide scale network testbed that has significant storage and compute resources. 

For researchers who want to join Fabric, it's easy to sign up [here](https://portal.fabric-testbed.net/) 


There are four steps for Hydra's deployment on Fabric:
1. set up the Fabric environment variables with bastion keypair, project ID, tokens, Bastion username. 
2. define the resources for the Fabric slice and submit the request
3. Install necessary library packages for Hydra
4. Build Layer 2 connection between each VM ( create face and route)
