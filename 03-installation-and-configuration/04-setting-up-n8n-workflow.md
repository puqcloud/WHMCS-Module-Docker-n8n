# Setting up n8n workflow

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Overview

The n8n workflow serves as the API interface between WHMCS and the Docker server. It receives commands from the WHMCS module and executes corresponding Docker actions via SSH.

## Prerequisites

- Self-hosted n8n instance or n8n cloud account
- SSH access to the Docker server

## Installation Options

### Option 1: n8n Marketplace

Use the latest n8n Marketplace templates from the PUQcloud creator profile.

### Option 2: Manual Import

Each module version includes a workflow template file (`puq_docker_n8n_deploy.json`) for manual import into n8n.

---

## n8n Workflow Configuration

### 1. Create Credentials

- **Basic Auth Credential** — For the Webhook API block (used by WHMCS to authenticate)
- **SSH Credential** — For Docker server access

### 2. Configure Template Parameters

In the **Parameters** block, modify the following:

| Parameter | Description |
|-----------|-------------|
| `server_domain` | Must match the **hostname** in WHMCS server settings |
| `clients_dir` | Storage location for user Docker data |
| `mount_dir` | Container disk mount point (typically unchanged) |

> **Important:** Do not modify `screen_left` and `screen_right` — these are technical parameters.

### 3. Docker Compose Configuration

The **deploy-docker-compose** element contains the Docker Compose configuration used for service creation, unlock, and update operations. This can be customized to match your requirements.

### 4. Nginx Configuration

The **nginx** element contains proxy server settings. Key sections:

- `main` — Primary server block
- `main_location` — Location rules for the main block

### 5. Bash Scripts

All bash scripts are generated within n8n and connected to the SSH element. They are fully controllable and return JSON or string responses.
