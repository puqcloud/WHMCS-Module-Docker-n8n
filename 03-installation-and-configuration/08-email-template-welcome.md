# Email Template — Welcome Email

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## Template Details

| Parameter | Value |
|-----------|-------|
| **Email Type** | Product/service |
| **Unique Name** | `puqDockerN8N Welcome Email` |

---

## Subject

```
n8n Order Information
```

## Body

```
Dear {$client_name},

Thank you for your order!

Product/Service: {$service_product_name}
Payment Method: {$service_payment_method}
Amount: {$service_recurring_amount}
Billing Cycle: {$service_billing_cycle}
Next Due Date: {$service_next_due_date}

The installation and setup of your n8n instance is in progress.
Within the next 4 minutes, you will be able to use your n8n instance.

Your n8n instance: https://{$service_domain}/

Note: When you log in for the first time, you will need to create an account.

Thank you for choosing our services!

{$signature}
```
