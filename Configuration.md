# Configuration

## Overview

This document provides an overview of key configuration files and settings for the Kubernetes Elastic Search deployment.

## 1. Elasticsearch Configuration

### `elasticsearch-chart/elasticsearch/values.yaml`

- `replicaCount`: Number of Elasticsearch replicas.
- `resources`: Resource requests and limits.
- `service`: Service configuration for Elasticsearch.

### `elasticsearch-chart/elasticsearch/templates/deployment.yaml`

- Elasticsearch deployment specifications.
- Container image, environment variables, and volume mounts.

## 2. Kibana Configuration

### `kibana-chart/kibana/values.yaml`

- `replicaCount`: Number of Kibana replicas.
- `resources`: Resource requests and limits.
- `service`: Service configuration for Kibana.

### `kibana-chart/kibana/templates/deployment.yaml`

- Kibana deployment specifications.
- Container image, environment variables, and volume mounts.
