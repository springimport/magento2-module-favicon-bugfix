# Favicon Bugfix
Bugfix for favicon `.ico` format in Magento 2. Necessary for Magento `<= 2.1.7`. [Fixed in 2.1.8](http://devdocs.magento.com/guides/v2.1/release-notes/ReleaseNotes2.1.8CE.html).

`We don't recognize or support this file extension type`

Enable module:
```
php -f bin/magento module:enable SpringImport_FaviconBugfix
```

Disable module:
```
php -f bin/magento module:disable SpringImport_FaviconBugfix
```

Update system:
```
php -f bin/magento setup:upgrade
```
