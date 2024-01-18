# bootstrap-sass

A SASS library for constructing typical websites.

## Modules

- [Core](./src/sass/core): Core modules required by all implementations.
- [Optional](./src/sass/optional): Optional modules.
- [Platform Support](./src/sass/platform-support): Support for various CMS platforms.

## Installation

### PHP
```
composer require --dev logicbrush/bootstrap-sass
```

## Getting Started

Include either `core.scss` or a specific platform support module:

```scss
// For a generic site:
@import "“bootstrap-root”/src/sass/core.scss";

// For SilverStripe:
@import "“bootstrap-root”/src/sass/platform-support/silverstripe.scss";

// For WordPress:
@import "“bootstrap-root”/src/sass/platform-support/wordpress.scss";
```
