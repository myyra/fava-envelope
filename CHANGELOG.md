# Changelog

### [0.5.3](https://github.com/polarmutex/fava-envelope/compare/v0.5.2...v0.5.3) (2022-05-19)

### Features

* Added negative rollover option
* Add rudimentary ability to see future months

### Bug Fixes

* replace url_for_current with url_for (for compatibility with fava 1.20 and up) ([910b3ad](https://github.com/polarmutex/fava-envelope/commit/910b3ad742683e747660c09430e56415ee44d8c3))

### [0.5.2](https://github.com/polarmutex/fava-envelope/compare/v0.5.1...v0.5.2) (2021-07-19)

### Bug Fixes

* bug where tables were not displaying on the latest fava

### [0.5.1](https://github.com/polarmutex/fava-envelope/compare/0.5...v0.5.1) (2021-01-29)

### Features

* Adding multiple budgets in multiple currencies capacity to fava_envelope

### Bug Fixes

* bug where it would not load page for month selected
* add checks for lastest fava which changed querytable api
* Fixed a typo in get_currencies()
* probably should not hard code 2020
* allow months with no income by setting the default to 0
* use beancounts operating_currency if available