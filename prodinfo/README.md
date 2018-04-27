## Production information


### Dockerfiles for all the applications running in production

* Find all the base Dockerfiles for applications used on OSIO at [EL-Dockerfiles](https://github.com/rhdt/EL-Dockerfiles)

* For the respective application there are Dockerfiles in the respective repository, for e.g. [fabric8-auth](https://github.com/fabric8-services/fabric8-auth) has a [Dockerfile.deploy](https://github.com/fabric8-services/fabric8-auth/blob/master/Dockerfile.deploy) for CentOS base and for RHEL base there is [Dockerfile.deploy.rhel](https://github.com/fabric8-services/fabric8-auth/blob/master/Dockerfile.deploy.rhel).

* There are other artifacts and configurations of the services we consume like Mattermost, Sentry, etc. from outside in the organization [rhdt](https://github.com/rhdt).

* More info about the images and transformation from CentOS to RHEL can be found in openshiftio/openshift.io #3321
