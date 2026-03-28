# Product Information

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Overview

The admin panel provides comprehensive tools for managing Docker n8n services, structured in two main sections with control buttons.

---

## Module Commands

| Command | Description |
|---------|-------------|
| **Create** | Provision a new n8n container |
| **Suspend** | Suspend the service |
| **Unsuspend** | Reactivate a suspended service |
| **Terminate** | Remove the service completely |
| **Change Package** | Modify resource allocation |
| **Container Start** | Start the Docker container |
| **Container Stop** | Stop the Docker container |
| **Mount Disk** | Attach the container's disk to the host system |
| **Unmount Disk** | Detach the container's disk from the host system |

---

## API Connection Status

Displays the connection status to the n8n workflow API:

- **Green** — API Connection OK
- **Red** — API connection problem with error details

---

## Container Status & Resource Monitoring

Real-time monitoring of the Docker container:

| Metric | Description |
|--------|-------------|
| **Status** | Container state (Running, Exited, Paused, etc.) |
| **Name** | Container name and ID |
| **CPU Usage** | Processor load with progress bar |
| **Memory Usage** | RAM consumption |
| **Disk IO** | Disk read/write statistics |
| **Disk Mounted** | Mounted disk usage (used/total) |
| **Disk File** | Disk image file size |
| **Network IO** | Network traffic statistics |

Additional controls:
- **Refresh** — Reload container statistics
- **Log** — View container logs for troubleshooting

---

## Application Information

| Field | Description |
|-------|-------------|
| **Version** | Installed n8n version |
| **Users** | List of users with system access |

---

## Metric Statistics

If metric billing is enabled, the admin area displays:

| Metric | Description |
|--------|-------------|
| **Traffic IN (GB)** | Incoming network traffic |
| **Traffic OUT (GB)** | Outgoing network traffic |

---

![Admin area product information](../img/03-admin-area-1.png)
