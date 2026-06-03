
# 🚀 JetBackup Administration Notes

A collection of useful JetBackup resources, troubleshooting guides, and storage destination documentation.

---

# 📦 Installation

## JetBackup Installation

* Documentation:

  * https://docs.jetbackup.com/v5.3/adminpanel/generalInformation.html

---

# 🔑 License Management

## License Transfer

* https://billing.jetbackup.com/knowledgebase/120/

## License Verification

Verify a license using an IP address:

```text
https://billing.jetbackup.com/verify.php?ip=SERVER_IP
```

Example:

```text
https://billing.jetbackup.com/verify.php?ip=192.168.1.100
```

---

# 🛠️ Troubleshooting

## Partial Backup Completion Investigation

* https://www.perplexity.ai/search/when-goted-partally-coleted-fo-EvLLKQmUTjGJRdy6mGmFrQ#0

## Hook Issues

### Backup Job Aborted From Hook

* https://billing.jetbackup.com/knowledgebase/83/Backup-Job-Aborted-From-Hook---JBMC-Backward-Compatible-Plugin.html

## MongoDB Connection Timeout Error

### Error:

```text
Fatal error: Uncaught MongoDB\Driver\Exception\ConnectionTimeoutException
```

### Reference:

* https://pcx3.com/cp/how-to-fix-jetbackup-general-error-fatal-error-uncaught-mongodbdriverlexceptionconnectiontimeoutexception-no-suitable-servers-found/

---

# ☁️ Cloud Storage Destinations

## Microsoft OneDrive

### Plugin Manager

* https://docs.jetbackup.com/v5.3-EDGE/adminpanel/Plugins/plugins.html#pluginmanager

### OneDrive Destination Setup

* https://docs.jetbackup.com/v5.3-EDGE/adminpanel/Destinations/DestinationType/OneDriveDestination.html

---

## Wasabi Storage

### Wasabi Documentation

* https://docs.wasabi.com/docs/working-with-buckets-and-objects

### JetBackup Documentation

* https://docs.jetbackup.com/v5.3/adminpanel/generalInformation.html

### Configure JetBackup with Wasabi

* https://docs.wasabi.com/docs/how-do-i-use-jetbackup-with-wasabi#how-do-i-use-jetbackup-with-wasabi

---

## Amazon S3

### Destination Configuration

* https://docs.jetbackup.com/linux/manual/Destinations/DestinationType/amazonS3Destination.html

---

## Backblaze B2

### Destination Configuration

* https://docs.jetbackup.com/manual/whm/Destinations/DestinationType/backblazeB2Destination.html

### General Documentation

* https://docs.jetbackup.com/v5.3/adminpanel/generalInformation.html

### Backblaze Resource Guide

* https://docs.jetbackup.com/v5.3-RC/adminpanel/Resources/backblazeinstr.html

---

# 📋 Quick Reference Table

| Task              | Documentation                                                                                                                                            |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Install JetBackup | https://docs.jetbackup.com/v5.3/adminpanel/generalInformation.html                                                                                       |
| Transfer License  | https://billing.jetbackup.com/knowledgebase/120/                                                                                                         |
| Verify License    | https://billing.jetbackup.com/verify.php?ip=                                                                                                             |
| OneDrive Setup    | https://docs.jetbackup.com/v5.3-EDGE/adminpanel/Destinations/DestinationType/OneDriveDestination.html                                                    |
| Wasabi Setup      | https://docs.wasabi.com/docs/how-do-i-use-jetbackup-with-wasabi                                                                                          |
| Amazon S3 Setup   | https://docs.jetbackup.com/linux/manual/Destinations/DestinationType/amazonS3Destination.html                                                            |
| Backblaze Setup   | https://docs.jetbackup.com/manual/whm/Destinations/DestinationType/backblazeB2Destination.html                                                           |
| Hook Issues       | https://billing.jetbackup.com/knowledgebase/83/                                                                                                          |
| MongoDB Error     | https://pcx3.com/cp/how-to-fix-jetbackup-general-error-fatal-error-uncaught-mongodbdriverlexceptionconnectiontimeoutexception-no-suitable-servers-found/ |
|                   |                                                                                                                                                          |

---

|
**Last Updated:** 2026
