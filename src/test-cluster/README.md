
# o7studios/test-cluster (test-cluster)

A feature for automatically installing o7studios test-cluster-environment tools

## Example Usage

```json
"features": {
    "ghcr.io/o7studios/features/test-cluster:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| octopusVersion | Select or enter an Octopus Helm chart version | string | latest |
| cheetahVersion | Select or enter an Cheetah Helm chart version | string | latest |
| installOctopus | Install Octopus Helm chart inside the test-cluster | boolean | true |
| installCheetah | Install Cheetah Helm chart inside the test-cluster | boolean | true |
| clusterName | Select or enter a name for the test-cluster | string | test-cluster |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/o7studios/features/blob/main/src/test-cluster/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
