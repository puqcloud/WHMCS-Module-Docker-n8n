# Email Template — Disk Limit Notification

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Template Details

| Parameter | Value |
|-----------|-------|
| **Email Type** | Product/service |
| **Unique Name** | `puqDockerN8N Notification disk limit` |

---

## Subject

```
Disk space usage {$disk_used_percentage}%
```

## Body

```
Dear {$client_name},

We would like to inform you that your n8n service ({$service_product_name})
has reached a high disk space usage level.

Service domain: {$service_domain}
Total disk space: {$disk_total}
Used disk space: {$disk_used}
Usage percentage: {$disk_used_percentage}%

We recommend reviewing your data or upgrading your plan to ensure
uninterrupted service.

Thank you for choosing our services!

{$signature}
```
