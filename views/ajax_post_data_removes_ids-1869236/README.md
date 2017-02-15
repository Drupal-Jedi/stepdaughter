# Patch summary

There are exists problem with views_ajax() function. It removes ajax_html_ids from $_POST. It causes that drupal_html_id()
can't properly build new HTML element identifier.
See https://www.drupal.org/node/1869236 for details.
