# Stepdaughter
Stepdaughter project is a curated list of actual per-version patches for Drupal core and modules.

Sometimes it happens that important from your point of view patch stack in waiting of RTBC. 
Maybe. maintainer have vacations in Bali and has no chance to push it.

We are don't intended to replace Drupal.org patches workflow, all patches required to be placed on Drupal.org first.
 
![Image of Stepdaughter](http://i.imgur.com/HvV4qxl.jpg)
 

# How to use
Stepdaughter project has clear structure. In the root of repository you can see all projects for which we have patches.
For each patch we have subfolder named as short-description-of-problem-#issue. It contains patch file and README.md which
gives short description of solving problem. So you can use patch or easy check Drupal.org issue status.

# How to contribute
1. Check if folder for project where you want to contribute already exists. If no you need to create it
with name as project name on drupal.org. For example if you want to contribute to project "Views Autocomplete Filters"
you should create folder named "views_autocomplete_filters" (see project page https://www.drupal.org/project/views_autocomplete_filters).
2. After creating directory if it was needed, you should create directory for the patch. Name it by next format:
short-description-of-problem-#issue, where #issue is node id of issue.
3. After creating directory for the patch you should put the patch into this directory. Name it by next format:
version-of-drupal-short-description-#issue-#comment.patch. Also you should provide README.md for the patch with
description of solving problem (please check any README.md file for existing projects).
