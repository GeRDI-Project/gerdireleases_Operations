# GeRDI releases

This is the central repository to collect all assets, configuration and other things to describe a release of the GeRDI software suite.

There are three default branches
1 master: Corresponds to the testing environment
2 staging: Corresponds to the staging environment
3 production: Corresponds to the production environment.

Each branch and therefore each environment has a kubernetes cluster (information on setting up a GeRDI-compliant k8s-cluster, see [here](https://code.gerdi-project.de/projects/SYS/repos/gerdikubed/browse).
This repository describes the k8s deployments and services needed to run the GeRDI software suite.
All images should reside in a dedicated docker registry (in GeRDIs case this is docker-registry.gerdi.research.lrz.de). 
