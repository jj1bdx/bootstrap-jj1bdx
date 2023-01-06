# bootstrap-jj1bdx

Customized [Bootstrap](https://getbootstrap.com) for JJ1BDX sites

## Installation

### Package dependencies

* bootstrap@5.3.0-alpha1
* sass (aka dart-sass)
* autoprefixer

### How to setup

```sh
npm install
```

## How to experiment

* edit `custom_scss/bootstrap-jj1bdx.scss`
* do `npm run compile:sass`
  - This command runs watching the changes of the source file
* Output: `custom_assets/bootstrap-jj1bdx.css`

## Generating production CSS file

* For generating minified files: do `npm run compile:min`
* Output: `custom_assets/bootstrap-jj1bdx.min.css`

