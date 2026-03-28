# Email Template — Update Email

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Template Details

| Parameter | Value |
|-----------|-------|
| **Email Type** | Product/service |
| **Unique Name** | `puqDockerN8N Update Email` |

---

## Subject

```
n8n Update Information
```

## Body

```
Dear {$client_name},

Your instance is currently being updated.
You will be able to use your n8n server again within 3 minutes.

Your n8n instance: https://{$service_domain}/

Thank you for choosing our services!

{$signature}
```
