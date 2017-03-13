# Favicon Bugfix

Bugfix for favicon `.ico` format in Magento 2.
`We don't recognize or support this file extension type`

Run from Magento 2 root directory:

for enable module:
```
php -f bin/magento module:enable SpringImport_FaviconBugfix
```

for update system:
```
php -f bin/magento setup:upgrade
```