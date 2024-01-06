# Automated Backups Configuration

## Overview

This document provides guidance on configuring automated backups for Elasticsearch in a Kubernetes environment.

## 1. Snapshot Repositories

- Create a snapshot repository in Elasticsearch to store backups.
- Ensure proper permissions for the repository.

### Example:

```yaml
PUT _snapshot/my_backup
{
  "type": "fs",
  "settings": {
    "location": "/mnt/data/backups"
  }
}
