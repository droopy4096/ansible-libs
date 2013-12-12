Note
====

this repo is under heavy construction and things most likely don't work as advertised, once stable state is reached this note will disappear


ansible-libs
============

Extra modules for ansible.

Current modules:

rpm_query - lightweight substitute for "yum" module indended only for confirmation of package install status

cpacman[2] - sibling of "yum" module in a way. Some code was taked from Yum module and expanded to handle cpacman usecases, other code was dropped as incompatible with cpacman

xml - xml find/replace akin to lineinfile...
