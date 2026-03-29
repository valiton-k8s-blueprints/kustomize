# Kustomizations for the Kubernetes Blueprint

Besides helm charts in our charts repository we maintain kustomizations here for cases 
where creating an extra helm chart would be too much.

## machine-controller

This kustimazation patches upstream yaml from https://github.com/kubermatic/machine-controller/blob/main/examples/machine-controller.yaml
for a given version.
