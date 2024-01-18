# bootstrap-sass

`bootstrap-sass` is a SASS library for developing themes for average websites.

## Modules

- [Core](./src/sass/core): Core modules required by all implementations.
- [Optional](./src/sass/optional): Optional modules.
- [Platform Support](./src/sass/platform-support): Support for various CMS platforms.

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
