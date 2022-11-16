# Background

Seabee have a split infrastructure with compute and storage on [NIRD](https://documentation.sigma2.no/files_storage/nird.html#) and a project on [google cloud](https://console.cloud.google.com/welcome?project=seabee) that is currently used for a managed database. The infrastructure is handled from the [seabee-iac](https://github.com/SeaBee-no/seabee-iac) repository.

# Access to seabee project space

For access to the Seabee project create an issue on this repository explaining your use case. We can then give access to Seabee on Dataporten. Additionally to deploy new apps, as described below, an account on [MAS](https://www.metacenter.no/user/application/form/norstore/) is also needed.

## Deploying applications

Applications on the NIRD toolkit can be found [here](https://documentation.sigma2.no/nird_toolkit/package-usage.html), these can be deployed following the manual for [NIRD Toolkit](https://documentation.sigma2.no/nird_toolkit/package-usage.html). These applications can be extended with custom tools by creating a new image on [seabee dockerfiles](https://github.com/SeaBee-no/dockerfiles)(note that push to a public repo needs to be setup) following instructions for a [custom docker image](https://documentation.sigma2.no/nird_toolkit/custom-docker-image.html).

## Advanced usage

To deploy applications that are not available on [apps.sigma2.no](https://apps.sigma2.no/) we need access to the nird kubernetes api. For this we need two tools:

1. [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl) - for deploying and controlling the applications
2. [kubed](https://github.com/UNINETTSigma2/kubed) - for authentication and kubectl configuration
