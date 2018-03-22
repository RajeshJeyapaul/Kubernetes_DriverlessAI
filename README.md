# Kubernetes_DriverlessAI
<b><u>Deploy H2oAI driver onto Kubernetes created through IBM Cloud</u></b>

The objective of this exercise is to deploy a container image which is more than a hello world so that the complexity involved in publishing a locally deployed image to cloud based Kubernetes cluster can be understood.

Also,  another objective is to have a scalable and stable environment while dealing with Deep learning based data modelling. In that aspect, the container image of H2O.ai is considered. Post deployment to Kubernetes, explore the feature of H2O.ai with your own data set

Architecture flow:

Local Docker Environment ------>  Install H2O.ai driver

Local IBM Cloud CLI &
Local Kubernetes CLI    -----> Tag & Publish ------> Kubernetes cluster

Kubernetes cluster ---> Public IP & NodePort . --> access the application

<b> Steps: </b>

(1) Configure local Docker environment and (2) Install and configure H2O.ai driver

(Refer the file docker_h2oai_installation.pdf file)

(3)Create IBM Cloud based Kubernetes cluster and (4)Configure IBM Cloud CLI and Kubernetes CLI

(Refer the file Kubernetes_Cluster_creation.pdf file)

5)Tag and publish the local docker image to cluster. Play around with the deployed application

(Refer the file Kubernetes_Cluster_creation.pdf file)
