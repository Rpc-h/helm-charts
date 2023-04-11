# helm-charts

This repository contains Helm charts for various RPCh related applications. These Helm charts are also referenced by ArgoCD applications (https://github.com/Rpc-h/applications) and then deployed in the cluster.

## Updating helm charts

Feel free to update your Helm chart to fit your needs. With any change in your Helm chart, (e.g. in templates or values), make sure you update `version` field in the respective chart's `Chart.yaml`.
