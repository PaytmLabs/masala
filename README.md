
Masala is a set of high-level chef cookbooks (wrappers, a base, and provisioning) and a cli tool, and a set of conventions. These are used together to describe clusters of systems as JSON data, and then run the provisioning of those systems. There is also tooling for creating images for vagrant/virtualbox and AWS AMIs, including incremental building.

This will eventually be the top-level project for Masala,  This project will include the front-end tooling used for working with the cookbooks.

For now, This README will document the cookbook components released so far, until the tooling component has been released:

- [masala_base](https://github.com/PaytmLabs/masala_base) - a "base" cookbook, focusing on basic system configuration and ensuring certain facilities are available for other cookbooks (IE: logstash, sysctl, etc)
- [masala_ldap](https://github.com/PaytmLabs/masala_ldap) - a weapper cookbook for openldap and sssd_ldap, providing simple providers to populate posix user/group and sudo entries, and the client-side authentication integration.

