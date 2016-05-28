# Patch summary

Fix the problem with detection of triggering element of form with multiple submit buttons.
Symptoms: submit callback is not invoked, $form_state['triggering_element'] has wrong value.
See https://www.drupal.org/node/2546700 for details.
