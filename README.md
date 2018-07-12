# Modernizr Contao Component
A shim repositoy for [Modernizr][1] as contao component.

Please see [modernizr-config.json](dist/modernizr-config.json) for included features and options for this modernizr build.

## Usage

You can add modernizr as component that can be deactivated in the layout settings or just as javascript. The given paths are for contao 4, if you still use Contao 3, the path changes from `assets/modernizr` to `assets/components/modernizr`.

### As component 

```php
$GLOBALS['TL_COMPONENTS']['modernizr']['js'] = ['assets/modernizr/dist/modernizr-custom.js|static'];
```

### Direct
```php
$GLOBALS['TL_JAVASCRIPT']['modernizr'] = 'assets/modernizr/dist/modernizr-custom.js|static';
```

## Internal

[Download-Url](https://modernizr.com/download/?-applicationcache-audio-backgroundsize-borderimage-borderradius-boxshadow-canvas-canvastext-cssanimations-csscolumns-cssgradients-csspositionsticky-cssreflections-csstransforms-csstransforms3d-csstransitions-flexbox-fontface-generatedcontent-geolocation-hashchange-history-hsla-indexeddb-inlinesvg-input-inputtypes-localstorage-multiplebgs-opacity-postmessage-rgba-sessionstorage-smil-svg-svgclippaths-textshadow-touchevents-video-webgl-websockets-websqldatabase-webworkers-addtest-domprefixes-hasevent-mq-prefixed-prefixes-setclasses-shiv-testallprops-testprop-teststyles) for updating builds while keeping the config.


[1]: https://modernizr.com