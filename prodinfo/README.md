## Production information


### Dockerfiles for all the applications running in production

* Find all the base Dockerfiles for applications used on OSIO at [EL-Dockerfiles](https://github.com/rhdt/EL-Dockerfiles)

* For the respective application there are Dockerfiles in the respective repository, for e.g. [fabric8-auth](https://github.com/fabric8-services/fabric8-auth) has a [Dockerfile.deploy](https://github.com/fabric8-services/fabric8-auth/blob/master/Dockerfile.deploy) for CentOS base and for RHEL base there is [Dockerfile.deploy.rhel](https://github.com/fabric8-services/fabric8-auth/blob/master/Dockerfile.deploy.rhel).

* There are other artifacts and configurations of the services we consume like Mattermost, Sentry, etc. from outside in the organization [rhdt](https://github.com/rhdt).

* More info about the images and transformation from CentOS to RHEL can be found in openshiftio/openshift.io #3321


### Various OpenShift clusters that form OSIO

* All the applications that form OSIO are hosted on [DSAAS cluster](http://console.dsaas.openshift.com/console/) which is a dedicated OpenShift cluster and is prod environment for OSIO.

* All the user applications are deployed on OpenShift online clusters which are called 1A, 1B, 2, 2A.

* And the prod preview is hosted on [RH-IDEV](https://console.rh-idev.openshift.com/console/).

* All the user applications are deployed on OpenShift online clusters which are called Free-stg, 2A.


### DSAAS in depth

* DSAAS is composed of three parts viz. OSIO, Analytics, Launcher.

* All the services that form OSIO viz. Auth, WIT, Tenant, etc are running under OSIO.

* Launcher a.k.a. getting started experience is taken care of by middleware team.

* [Github repository](https://github.com/openshiftio/saas-openshiftio) for DSAAS.
