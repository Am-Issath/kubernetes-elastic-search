# Kubernetes Elastic Search Deployment

This repository contains manifests and Helm charts for deploying Elasticsearch and Kibana on a Kubernetes cluster. The deployment is configured to be scalable and easily manageable.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Manifests and Helm Charts](#manifests-and-helm-charts)
- [Configuration](#configuration)
- [Automated Backups](#automated-backups)
- [Using Helm](#using-helm)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Helm](https://helm.sh/docs/intro/install/)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/Am-Issath/kubernetes-elastic-search.git
   cd kubernetes-elastic-search
   

2. Follow the instructions in the [`Tasks.md`](Tasks.md) file to deploy Elasticsearch and Kibana.

## Manifests and Helm Charts

- **Manifests:** Kubernetes YAML manifests for Elasticsearch.
- **Helm Charts:** Helm charts for Elasticsearch deployment.
- **Kibana Helm Charts:** Helm charts for Kibana deployment.

## Configuration

Customize your deployment by modifying configuration files. Check the [`Configuration.md`](Configuration.md) file for details.

## Automated Backups

Configuring automated backups for Elasticsearch involves creating snapshot repositories and policies. Refer to [`AutomatedBackups.md`](AutomatedBackups.md) for detailed instructions.

## Using Helm

### Create Helm charts

1. Create Helm chart for Elasticsearch:

   bash
   mkdir elasticsearch-chart
   cd elasticsearch-chart
   helm create elasticsearch
   

2. Edit generated files in `elasticsearch-chart/elasticsearch` to match your Elasticsearch deployment.

3. Repeat the same process for Kibana.

### Install Helm charts

1. Install Helm chart for Elasticsearch:

   bash
   helm install elasticsearch ./elasticsearch-chart/elasticsearch
   

2. Install Helm chart for Kibana.

## Contributing

Feel free to contribute by opening issues for suggestions or improvements. You can also create pull requests to contribute directly to the project.

## License

This project is licensed under the MIT License.

