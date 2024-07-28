# ANCT sandbox project

## Pre-requisites

- [ddev](https://ddev.readthedocs.io/en/stable/)

## Installation

- Clone this repository
- Run `ddev start`
- Run `ddev composer install`
- Run `ddev drush site-install --existing-config -y`
- Run `ddev drush content:import themes/custom/anct/content/content.zip`
- Run `ddev drush uli` to connect to BO (or to launch website `ddev launch`)

This should give you a working Drupal 10 site with the ANCT Themes installed.

The zip contains :
- one content page make as homepage
- items main menu
