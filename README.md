# node-hosted
Package Manager for Node Packages intended to be deployed within corporate firewall

Still very much a WIP:

High level long term Plans include:
 - Read through cache, admin ability to whitelist/blacklist repositories
   - LDAP auth
 - Nice usable UI for admins to manage users and packages, and for everyone to search
   - Search possibly with elasticsearch (might be uneccesary)
 - Server should be able to be deployed behind a load balancer, should support multiple instances. Need to work out details, but I'd like to keep this as a hard requirement as things are implemented
 - Well tested and easy to read. This should be easy to extend/contribute to. People should feel confident deploying this behind a corporate firewall.
