# Chroma Database

The Chroma database Containerfile is a simple wrapper that gives group permission to the `/chroma` directory for [supporting arbitrary user ids](https://docs.openshift.com/container-platform/4.16/openshift_images/create-images.html#use-uid_create-images) on the OpenShift Container Platform and also addresses the [DockerHub rate limits](https://docs.docker.com/docker-hub/download-rate-limit/).

## Quay Repository

This image is uploaded to the quay repository `quay.io/repository/redhat-ai-dev/chroma`.

## Versioning

The version of Chroma used in this Container should match the dependency version located in the [sample application](https://github.com/redhat-ai-dev/ai-lab-samples/blob/main/rag/requirements.txt#L3).