UBC CLF 7.0.4 DRUPAL 8/9 THEME
=======================================

CLF is a *child theme* for the Drupal 8 base theme, [Galactus](https://github.com/ubc-web-services/galactus). This theme provides UBC-branded units with the basic structure of the UBC CLF ([Common Look and Feel](http://clf.ubc.ca)) and is intended to be modified and customized. For tips on how to modify the theme to suit your needs, see [the official Drupal 8 Theme Guide](https://www.drupal.org/docs/8/theming).

Created by the UBC IT Web Services Department.

# Composer Builds
As this theme is meant to be modified, it should not be installed via Composer. Doing so weould overwrite your customizations.

However, you can (and should) add the base theme, [Galactus](https://github.com/ubc-web-services/galactus), by running `composer require ubc-web-services/galactus`.

# Drupal 7 Support
_________________

If you're looking for the Drupal 7 version of this theme, it can be found in the [drupal-7 branch](https://github.com/ubc-web-services/clf/tree/drupal-7).

# SASS

Optionally, CSS changes can be made with SASS through `sass`.


Install the node packages with this command:
```
npm install
```

You can build your CSS changes with this command:
```
npm run build:css
```

OR

You can watch changes to your SASS files with this command:
```
npm run watch:css
```
