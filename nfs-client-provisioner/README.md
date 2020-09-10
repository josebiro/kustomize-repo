# NFS Client Provisioner

This directory contains a kustomize deployment for the nfs-client-provisioner

## Installation
* Clone this repo
* Replace values in `overlays/prod{kustomization.yaml, deployment-volume-patch.yaml}` with values that suit your environment.
* run `kubectl apply -k overlays/prod`
