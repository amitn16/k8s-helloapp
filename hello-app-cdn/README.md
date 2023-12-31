# Hello Application with CDN example

> [!IMPORTANT]  
> This sample has now moved to the `quickstarts/` directory.
> Do not update this now deprecated directory, it will eventually be removed.

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https://github.com/GoogleCloudPlatform/kubernetes-engine-samples&cloudshell_tutorial=README.md&cloudshell_workspace=hello-app-cdn)

> **Note:** This application is a copy of [hello-app](../hello-app) sample.
> See that directory for more details on this sample.

This sample web application is designed to be compatible with the Cloud CDN.
It responds to requests with the `Cache-Control` HTTP header to ensure the responses
are cached.

The container image for this directory is publicly available at
`us-docker.pkg.dev/google-samples/containers/gke/hello-app-cdn:1.0`.
