Nagios Core 5 README
====================

Nagios is a host/service/network monitoring program written in C and
released under the GNU General Public License, version 2. CGI programs
are included to allow you to view the current status, history, etc via
a web interface if you so desire.

Visit the Nagios homepage at https://www.nagios.org for documentation,
new releases, bug reports, information on discussion forums, and more.


https://www.nagios.org/about/features/[Features]
-----------------------------------------------
* Monitoring of network services (via SMTP, POP3, HTTP, PING, etc).
* Monitoring of host resources (processor load, disk usage, etc.).
* A plugin interface to allow for user-developed service monitoring
  methods.
* Ability to define network host hierarchy using "parent" hosts,
  allowing detection of and distinction between hosts that are down
  and those that are unreachable.
* Notifications when problems occur and get resolved (via email,
  pager, or user-defined method).
* Ability to define event handlers for proactive problem resolution.
* Automatic log file rotation/archiving.
* Optional web interface for viewing current network status,
  notification and problem history, log file, etc.


Changes
-------
See the
https://raw.githubusercontent.com/NagiosEnterprises/nagioscore/master/Changelog[Changelog]
for a summary of important changes and fixes, or the
https://github.com/NagiosEnterprises/nagioscore/commits/master[commit history]
for more detail.


Download
--------
Latest releases can be downloaded from https://www.nagios.org/download/


Installation
------------
http://nagios.sourceforge.net/docs/nagioscore/4/en/quickstart.html[Quickstart installation guides]
are available to help you get Nagios up and monitoring.


Documentation & Support
-----------------------
* http://nagios.sourceforge.net/docs/nagioscore/4/en/[User Guide]
* https://library.nagios.com/library/products/nagioscore/[Nagios Core Documentation Library]
* https://support.nagios.com/forum/viewforum.php?f=7[Support Forums]
* https://www.nagios.org/support/[Additional Support Resources]


Contributing
------------
The Nagios source code is hosted on GitHub:
https://github.com/NagiosEnterprises/nagioscore

Do you have an idea or feature request to make Nagios better? Join or
start a discussion on the
https://support.nagios.com/forum/viewforum.php?f=34[Nagios Core Development forum].
Bugs can be reported by
https://github.com/NagiosEnterprises/nagioscore/issues/new[opening an
issue on GitHub]. If you have identified a security related issue in
Nagios, please contact security@nagios.com.

Patches and GitHub pull requests are welcome. Pull requests on GitHub
link commits in version control to review and discussion of the
changes, helping to show how and why changes were made, in addition to
who was involved.

Created by Ethan Galstad, the success of Nagios has been due to the
fantastic community members that support it and provide bug reports,
patches, and great ideas. See the
https://raw.githubusercontent.com/NagiosEnterprises/nagioscore/master/THANKS[THANKS file]
for some of the many who have contributed since 1999.
