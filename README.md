## Example Voting App Kubernetes

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) repository from the [docker-examples](https://github.com/dockersamples) GitHub page

and modified it to work on the Kubernetes cluster.

**HELM Chart update**
This version has been modified to be deployed with a helm chart. 

To deploy with the helm chart run `helm install --namespace default voting-web-app ./test_heml.tgz `
