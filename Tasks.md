# Tasks

## Task 1: Setting Up the Kubernetes Cluster

1. Install Minikube and Kubectl on your local machine.
2. Start a Minikube cluster.
3. Ensure that Minikube is running successfully.

## Task 2: Deploying Elasticsearch

1. Navigate to the `elasticsearch-chart/elasticsearch` directory.
2. Review and edit the `values.yaml` file for Elasticsearch configurations.
3. Deploy Elasticsearch using Helm: `helm install elasticsearch .`

## Task 3: Deploying Kibana

1. Navigate to the `kibana-chart/kibana` directory.
2. Review and edit the `values.yaml` file for Kibana configurations.
3. Deploy Kibana using Helm: `helm install kibana .`

## Task 4: Verify Deployments

1. Check the status of Elasticsearch and Kibana pods.
2. Ensure services are exposed correctly.

## Task 5: Additional Configuration

1. Customize any additional configurations based on your requirements.
2. Update Helm charts or manifests accordingly.

## Task 6: Contributing

1. Open issues for suggestions or improvements.
2. Contribute by creating pull requests.
