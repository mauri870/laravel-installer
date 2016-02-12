## Laravel Installer
[![Build Status](https://travis-ci.org/mauri870/laravel-installer.svg?branch=master)](https://travis-ci.org/mauri870/laravel-installer) [![Latest Stable Version](https://poser.pugx.org/mauri870/laravel-installer/v/stable)](https://packagist.org/packages/mauri870/laravel-installer) [![Total Downloads](https://poser.pugx.org/mauri870/laravel-installer/downloads)](https://packagist.org/packages/mauri870/mauri870/laravel-installer) [![Latest Unstable Version](https://poser.pugx.org/mauri870/laravel-installer/v/unstable)](https://packagist.org/packages/mauri870/laravel-installer) [![License](https://poser.pugx.org/mauri870/laravel-installer/license)](https://packagist.org/packages/mauri870/laravel-installer)

> # :warning: DISCONTINUED AND MIGRATED :construction:
> This project is discontinued and deprecated.
> I will not offer more support and bugfixes here.
> For the newer changes, support and improvements please refer to [artesaos/laravel-installer](https://github.com/artesaos/laravel-installer)

I create this laravel installer as an alternative like a symfony installer, where you could choose a specific version to install.


#### Installation
```bash
composer g require mauri870/laravel-installer
```

#### Usage

This installer works like a default laravel installer. The difference is you can choose your version.
```
laravel-installer new name version
```

Replace `name` for your project name and `version` for one of the available versions:

`4.2`

`5.0`

`5.1` - You can use `LTS` instead

`5.2` - Default version

You can use the help command for instructions:
```
laravel-installer help new
```
