UBC CLF 7.0.4 DRUPAL 8 THEME
=======================================

CLF is a *child theme* for the Drupal 8 base theme, [Galactus](https://github.com/ubc-web-services/galactus). This theme provides UBC-branded units with the basic structure of the UBC CLF ([Common Look and Feel](http://clf.ubc.ca)) and is intended to be modified and customized. For tips on how to modify the theme to suit your needs, see [the official Drupal 8 Theme Guide](https://www.drupal.org/docs/8/theming).

Created by the UBC IT Web Services Department.

# Composer Builds
If you're using composer, add the project with:
```
composer require ubc-web-services/clf:v1.0.3 
```
We want to include the *exact* version so that running `composer update` will not overwrite your theme customizations.

This will also add the base theme, [Galactus](https://github.com/ubc-web-services/galactus) as a dependency. Running `composer update` will still update the base theme.

# Drupal 7 Support
_________________

If you're looking for the Drupal 7 version of this theme, it can be found in the [drupal-7 branch](https://github.com/ubc-web-services/clf/tree/drupal-7).

# SASS

Optionally, CSS changes can be made with SASS through node-sass.

Ensure that you have `yarn` installed.
```
https://yarnpkg.com/lang/en/docs/install/
```

Install the node packages with this command:
```
yarn install
```

You can build your CSS changes with this command:
```
yarn run build-css
```

OR

You can watch changes to your SASS files with this command:
```
yarn run watch-css
```
