# OpenCTI-helm
OpenCTI Helm Chart

:::warning
Work in progress! templates and values.yaml currently is unstable and have issues in differents paths.
:::

## Helm chart background
During my research, there is 2 realisation of OpenCTI Charts had been written:
* [devops-ia/helm-charts](https://github.com/devops-ia/helm-charts/tree/main/charts/opencti) ([OpenCTI issue #3753](https://github.com/OpenCTI-Platform/opencti/issues/3573)). Issues: no docs, possbile security misconfigurations
* [Ascend-Technologies/OpenCTI-HELM-CHART](https://github.com/Ascend-Technologies/OpenCTI-HELM-CHART). Issues: `chart contains everything (dozens of connectors, deployments, rabbitMQ, Redis, minio, etc).` 

Now I'm working on my own helm chart to resolve issues of other.