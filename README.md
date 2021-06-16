# Collection Beta Barrio Subtheme

This theme is a subtheme of Bootstrap Barrio theme: https://www.drupal.org/project/bootstrap_barrio - it is currently based off Bootstrap 4 (but I do not believe there are any functions that are BS4 dependent), so should handle an upgrade to BS5.

## Dependencies
* Tested with Drupal 9.x and installing Bootstrap Barrio 5.1.4.

## Things that really need some love
* Inside the `templates/layout/` folder the `html.html.twig` manually includes JS and CSS libraries - these are not being treated as dependencies in the wider Drupal installation.
* Inside the `templates/layout/` folder the `page.html.twig` manually includes an external profile from a 3rd party area, this would be better treated as a dependency rather than hardcoded into the theme.
* The CSS is not compiled from SASS and `/css/style.css` is effectively an override file.
