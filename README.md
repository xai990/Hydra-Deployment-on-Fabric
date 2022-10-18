# Hydra's Deployment on Fabric testbed 

This repository contains the notebook for the Farbic environment configuration, Fabric slice requestion and setup for Hydra's deployment.

[Hydra](www.hydra-repo.io/) is an distributed data repository over Named Data Networking(NDN) that focuses on five attributes: resiliency, scalability, usability, efficiency, and security.

[Fabric](https://fabric-testbed.net/) is a nationwide scale network testbed that has significant storage and compute resources. For researchers who want to join Fabric, it's easy to sign up [here](https://portal.fabric-testbed.net/). 


There are four steps of preparations for Hydra's deployment on Fabric:
1. Set up the Fabric environment variables with Bastion keypair, project ID, tokens, Bastion username. -- This enables Fabric users to submit a Fabric Slice request. 
2. Define the resources for the Fabric slice and submit the request -- We submit a slice request with five nodes(VMs). Each node has 2 cores, 8GB ram, 50G disk memory, and basic NICs.
3. Install necessary library packages for Hydra on each VM including nfd, ndnping, python-ndn, ndn-svs, ndn-hydra and etc.
4. Build Layer 2 connection between each VM (create face and route using nfd)
