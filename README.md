# Blankz

A skeleton for creating applications with [CakePHP](https://cakephp.org) 4.x.

The skeleton source code can be found here: [abarkhuysen/blankz](https://github.com/abarkhuysen/blankz).

## Installation

1. Clone the repository `git clone git@github.com:abarkhuysen/blankz.git`.
2. Update Composer `composer self-update`.
3. Install required packages with composer `composer install`.

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server
bin/cake server -p 8765
```

Then visit `http://localhost:8765` to see the welcome page.

## Updates

Since this skeleton is a starting point for your application and various files
would have been modified as per your needs, there isn't a way to provide
automated upgrades, so you have to do any updates manually.

## Configuration

Read and edit the environment specific `config/app_local.php` and setup the
`'Datasources'` and any other configuration relevant for your application.
Other environment agnostic settings can be changed in `config/app.php`.

## Layout

The app skeleton uses [Milligram](https://milligram.io/) (v1.3) minimalist CSS
framework by default. You can, however, replace it with any other library or
custom styles.
