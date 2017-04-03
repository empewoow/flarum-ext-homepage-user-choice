# Flarum extension: Homepage User Choice

## Introduction

With this plugin you can let users change their default homepage to either all discussions or labels.

Please note that this plugin is still a work in progress.

## Screenshot

![Flarum extension settings](/resources/docs/flarum_user_settings.png)

## During development

Run in (js/forum):

```
npm install

gulp watch
```

When it is compiled, run in Flarum root:

```
composer update
```

Also, whenever you changed the source code, run `php flarum cache:clear` and reload the page.

## Installation through Packagist

The extension will also be on [Packagist](https://packagist.org/packages/empewoow/flarum-ext-homepage-user-choice), so you should be able to install it using:

```
composer require empewoow/flarum-ext-homepage-user-choice
```
