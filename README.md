# example-edc-setup

This is an example setup to provide two EDCs for testing purposes.
The setup is based on the umbrella helm chart and uses parts of it.
https://github.com/eclipse-tractusx/tractus-x-umbrella

This setup includes following components:
- central idp
- two data-provides (EDC provider and consumer)
- bdrs-server-memory
- iatpmock

The iatpmock is included in this repository and needs to be build and the 
image pushed into registry where it then can be accessed for the deployment.

