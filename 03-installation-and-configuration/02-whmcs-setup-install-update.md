# WHMCS setup (install/update)

### Docker n8n module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-docker-n8n.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

## System requirements

The module uses ionCube encoding. Your server must meet the following requirements:

| Requirement | Minimum                 |
|-------------|-------------------------|
| PHP | 8.1 or 8.2              |
| WHMCS | 9+ or higher            |
| ionCube Loader | v13 or newer (v14, v15) |

> **Note:** Module is coded with ionCube v13

> To install and update a module, you must perform one and the same action.

---

## Step 1 — Download the latest version of the module

PHP 8.2

```bash
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/php82/PUQ_WHMCS-Docker-n8n-latest.zip
```

All versions are available via link: [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-n8n/)

---

## Step 2 — Unzip the archive with the module

```bash
unzip PUQ_WHMCS-Docker-n8n-latest.zip
```

---

## Step 3 — Copy and Replace

Copy the `puqDockerN8N` directory from the extracted `PUQ_WHMCS-Docker-n8n` archive to your WHMCS installation:

```
WHMCS_WEB_DIR/modules/servers/
```

> **Note:** To install and update a module, you must perform one and the same action — download and copy the latest version over the existing files.
