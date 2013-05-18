skrollr-ie
==========

skrollr plugin that adds some missing features to IE < 9

The plugin makes IE understand `opacity`, `rgb()` and `hsl()` (the ones with alpha are mapped to them) and it creates a very simple `document.querySelector` polyfill which only supports ID selectors (using `getElementById`). Needed if you want to use [data-anchor-target](https://github.com/Prinzhorn/skrollr#relative-mode-or-viewport-mode).

Documentation
=====

Include `dist/skrollr.ie.min.js` after the core using conditional comments.

```html
<script type="text/javascript" src="skrollr.min.js"></script>

<!--[if lt IE 9]>
<script type="text/javascript" src="skrollr.ie.min.js"></script>
<![endif]-->
```


Changelog
====

0.1.0 (2013-05-18)
-----

* Moved skrollr-ie to a dedicated repo.