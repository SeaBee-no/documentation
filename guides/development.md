# Background

Seabee have a split infrastructure with compute and storage on [NIRD](https://documentation.sigma2.no/files_storage/nird.html#) and a project on [google cloud](https://console.cloud.google.com/welcome?project=seabee) that is currently used for a managed database. Some of the seabee infrastructure is handled from the [seabee-iac](https://github.com/SeaBee-no/seabee-iac) repository.

# Access to seabee project space

To get access to the Seabee project create an issue on this repository explaining your use case.

## Deploying applications

A list of default supported applications on the NIRD toolkit can be found [here](https://documentation.sigma2.no/nird_toolkit/package-usage.html), these can be deployed following the manual for [NIRD Toolkit](https://documentation.sigma2.no/nird_toolkit/package-usage.html). These applications can in many cases be extended with custom tools by creating an new image on [seabee dockerfiles](https://github.com/SeaBee-no/dockerfiles)(note that push to a public repo needs to be setup)

## Advanced usage

For applications not default supported on the NIRD toolkit app platform, we need to build a custom deployment. This needs to be evaluated based on the application in question.
