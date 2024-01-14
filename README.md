# laravel-sample
Sample laravel for testing deployments


# Credentials
Azure app service credentials can be found under the publish profile and needs to be referenced with:
publish-profile: ${{ secrets.AZURE_WEBAPP_PUBLISH_PROFILE }}
Ensure you copy all of the publish profile details into the file not just the password