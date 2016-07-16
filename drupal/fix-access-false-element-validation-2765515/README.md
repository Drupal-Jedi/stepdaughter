# Patch summary

Bt default Drupal core invoke #element_validate even if element has #access = FALSE. Which has no sense.  
See https://www.drupal.org/node/2765515 for details.
