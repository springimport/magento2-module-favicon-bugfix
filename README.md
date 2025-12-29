# Favicon Bugfix for Magento 2

Bugfix for favicon .ico format upload error in Magento 2.

> **⚠️ DEPRECATED - This module is only for Magento <= 2.1.7**
>
> Bugfix for favicon `.ico` format in Magento 2 - fixes error: `We don't recognize or support this file extension type`
>
> This bug was [fixed in Magento 2.1.8](http://devdocs.magento.com/guides/v2.1/release-notes/ReleaseNotes2.1.8CE.html) and later versions.
> **DO NOT use this module with Magento 2.2+ or 2.4+**

## Version Compatibility

| Magento Version | PHP Version | Status |
|-----------------|-------------|--------|
| 2.1.8 - 2.4.x | 7.0+ | ❌ **Incompatible** |
| **2.0.x - 2.1.7** | **5.6 - 7.1** | **✅ Compatible** |

## Installation

```bash
composer require springimport/magento2-module-favicon-bugfix
php bin/magento module:enable SpringImport_FaviconBugfix
php bin/magento setup:upgrade
```
