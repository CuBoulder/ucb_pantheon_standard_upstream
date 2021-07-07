# Composer-enabled Drupal template

This is the CU Boulder standard upstream for use with Pantheon.

## Site creation via Terminus

terminus site:create --org="university-of-colorado-boulder" -- <site-name> <site-name> "UCB Standard Upstream"

terminus drush <site-name>.dev -- site-install

terminus connection:set <site-name> git
