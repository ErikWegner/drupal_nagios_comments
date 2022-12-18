# Nagios_Comments

This Drupal module is an extension to the [nagios module](https://www.drupal.org/project/nagios).

It queries the number of published comments as performance data. It issues a warning if there are any unpublished comments.

## Installation

1. Do one of the following options
    1. Add this repository to the `composer.json` file and install with `composer require erikwegner/drupal_nagios_comments:dev-master`
    2. Clone into modules/nagios_comments or
    3. Download archive and extract into modules/nagios_comments
2. Enable module _Nagios comments monitoring_ at `/admin/modules`
3. Configure nagios module at `/admin/config/system/nagios`: enable _Nagios Comments_ in the _MODULE_ section. Save settings.
4. Check status page for performance data and status information
