# Hello Application example on redis

> [!IMPORTANT]  
> This sample has now moved to the `quickstarts/` directory.
> Do not update this now deprecated directory, it will eventually be removed.

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https://github.com/GoogleCloudPlatform/kubernetes-engine-samples&cloudshell_tutorial=README.md&cloudshell_workspace=hello-app-redis)

This example shows how to build and deploy a containerized Go web server
application on redis using [Kubernetes](https://kubernetes.io).

This directory contains:

- `main.go` The HTTP server uses Redis as a cache database, counts the number of requests it receives, and prints out the number on the website. If the Redis service works, the number should keep increasing.
- `Dockerfile` is used to build the Docker image for the application.

The container image for this directory is publicly available at `us-docker.pkg.dev/google-samples/containers/gke/hello-app-redis:1.0`

