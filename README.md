# monica-k8s
files for deploying and managing monicahq in k8s with ArgoCD

this is just for playing around with minikube and ArgoCD. Note that I stripped out the volumes, so all of the data is lost every time these containers are rebuilt

The main monica project can be found here https://github.com/monicahq/monica

I built this environment by hand in minikube using these docker instructions and then backed into the k8s yaml files once it got it up and running

https://hub.docker.com/_/monica 

Also note that on my old laptop (Thinkpad T420, 16GB RAM), it takes 7 full minutes after deployment with ArgoCD before the login screen appears

Copyright © 2022

Licensed under [the AGPL License](/LICENSE.md).
