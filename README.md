# kust-app

This is an app example using Kustomize the customize an environment (prod and staging)

You can run from the root folder using the below commands:

    - kustomize build ../base

For customized prod and staging:

    - kustomize build overlay/prod
    - kustomize build overlay/staging
