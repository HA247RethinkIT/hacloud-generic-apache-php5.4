# Change Log
All notable changes to this project will be documented in this file.

##
## [0.0.2]
### Fix
- Disable session.upload_progress by default to mitigate PHP2Shell (CVE-2026-109618 / CVE-2026-109619). Set PHP_session.upload_progress.enabled=1 to re-enable
- Only read environment variables that start with PHP_ followed by a lowercase ini directive

##
## [0.0.1]
### Add
- First release of the project. Intended for use with HA Cloud forked from https://github.com/HA247RethinkIT/hacloud-generic-apache-php5.3
