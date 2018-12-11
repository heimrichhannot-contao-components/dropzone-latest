# Dropzone Contao component
A shim repositoy for [Dropzone](https://www.dropzonejs.com/) as [Contao Component](https://github.com/contao-components/installer).

## Install

```
composer require heimrichhannot-contao-components/dropzone-latest
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```php
$GLOBALS['TL_JAVASCRIPT']['dropzone'] = 'assets/dropzone-latest/dist/min/dropzone.min.js|static';
$GLOBALS['TL_CSS']['dropzone'] = 'assets/dropzone-latest/dist/min/dropzone.min.css|static';
```

### Contao 3

```php
$GLOBALS['TL_JAVASCRIPT']['dropzone'] = 'assets/components/dropzone-latest/dist/min/dropzone.min.js|static';
$GLOBALS['TL_CSS']['dropzone'] = 'assets/components/dropzone-latest/dist/min/dropzone.min.css|static';
```