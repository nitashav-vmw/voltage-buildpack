# Voltage Buildpack

This is a intermediate buildpack for Cloud Foundry that provides integration with the voltage.

```sh
foo@bar:my-app$ cf push my-app --no-start
foo@bar:my-app$ cf v3-push my-app -b voltage-builpack -b <final_buildpack>

```

See https://docs.cloudfoundry.org/buildpacks/understand-buildpacks.html for buildpack basics. This is an 
intermediate buildpack using only the bin/supply script.

See https://docs.cloudfoundry.org/buildpacks/use-multiple-buildpacks.html#Specifying%20Buildpacks%20with%20the%20cf%20CLI
for information about pushing an application with multiple buildpacks.