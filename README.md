# Modernizr Contao Component
A shim repositoy for [Modernizr][1] as contao component.

Please see [modernizr-config.json](dist/modernizr-config.json) for included features and options for this modernizr build.

## Usage

Add following line to your config.php:

```php
// Contao 4:
// src/Ressources/contao/config/config.php
$GLOBALS['TL_JAVASCRIPT']['modernizr'] = 'assets/modernizr/dist/modernizr-custom.js|static';

// Contao 3:
// config/config.php
$GLOBALS['TL_JAVASCRIPT']['modernizr'] = 'assets/components/modernizr/dist/modernizr-custom.js|static';
```

## Internal

[Download-Url](https://modernizr.com/download/?-applicationcache-audio-backgroundsize-borderimage-borderradius-boxshadow-canvas-canvastext-cssanimations-csscolumns-cssgradients-csspositionsticky-cssreflections-csstransforms-csstransforms3d-csstransitions-flexbox-fontface-generatedcontent-geolocation-hashchange-history-hsla-indexeddb-inlinesvg-input-inputtypes-localstorage-multiplebgs-opacity-postmessage-rgba-sessionstorage-smil-svg-svgclippaths-textshadow-touchevents-video-webgl-websockets-websqldatabase-webworkers-addtest-domprefixes-hasevent-mq-prefixed-prefixes-setclasses-shiv-testallprops-testprop-teststyles) for updating builds while keeping the config.


[1]: https://modernizr.com