Yandex Turbo Pages Change Log
=============================

Dev-master
--------------------
* Enh: added possibility to enable infinity mode for related items
* Fix: pubDate for items is not required for now

1.1.0 May 9, 2018
--------------------
* Enh: added possibility to add custom counter;
* Enh: added possibility to add turbo:topic and turbo:source attributes for Item;
* Enh: added Content helper with next methods: header, img, gallery, share, button, comments;
* Dep: TurboContentHeader marked as deprecated. Should used Content::header instead;
* Ref: refactored Channel and Item methods for best cyclomatic complexity value;
* Enh: added possibility to add yandex:full-text for compatibility with Yandex News;

1.0.4 December 22, 2017
--------------------
* Enh: added requiring for mbstring;
* Enh: added title length limitation;
* Enh: turboAdId attribute is required now for adNetwork method.

1.0.3 November 30, 2017
--------------------
* Enh: added class for generating Header for turbo content;
* Enh: added test covergae for TurboContentHeader class;
* Doc: fix some PHPDoc comments.

1.0.2 November 27, 2017
-------------------
* Enh: Added test coverage for all classes (sokolnikov911)

1.0.0 November 26, 2017
--------------------
* Initial release (sokolnikov911)

Development started November 25, 2017
----------------------------------