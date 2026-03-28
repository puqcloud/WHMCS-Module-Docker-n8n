# Add server

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Add a new server to the system WHMCS

Navigate to: **System Settings → Servers → Add New Server**

- Enter the correct **Name** and **Hostname**

> **Attention: Important Information**
> The **hostname** field represents the actual domain of the server running Docker and must match the **server_domain** parameter in the **n8n workflow**. If they do not match, communication will not function correctly.
> Additionally, this domain must be configured so that all its subdomains resolve to the IP address of the server running Docker.

---

## Module settings

In the **Server Details** section, select the **"PUQ Docker n8n"** module and enter the correct **username** and **password** for the **API endpoint** in the n8n workflow.

> Additionally, in the **Access Hash** field, insert the **URL of the API entry point** for the n8n workflow.
