I saw this project going on, and figured I could help, if it's written in python.  Nothing against PHP - actually everything against PHP.  It's just so frought with issues, python is a much more stable, mature language.  I'm willing to donate you the base of a multi-threaded server implementaiton, and help you with the crud implementation.  Let me know if you like this idea - it's a faster, proven, cross-platform solution.  Not that PHP can't be; I just don't like monitoring solutions that have this heavy webserver they are dragging around to do their bidding.

All the best,

Jason "jabreity" Breitwieser
jason@ori.net


groundcontrol
=============

A basic html5/php/mysql interface for monitoring, graphing and controlling wireless and other devices (ubiquiti, mikrotik, cambium, etc.)

After Ubiquiti released airCRM and forced all of their device command/control to be done using their cloud, a group of experienced WISP professionals decided to get together and create their own solution. Service Providers need direct responsibility for monitoring and managing their network, and vendor-lock in for C&C systems is always a problem.

This project is about removing vendor lock-in from management interfaces, and giving C&C back to network operators on a simple to use system that is brand and product diverse.

Initially we want to be able to:
* poll devices
* collect historic data
* mass change configs
* save config backups
* log and timestamp config changes
* ubnt, mikrotik, cambium ePmP support
* group radios by AP MAC
* schedule upgrades / mass-upgrades

Eventually, we'd like to be able to:
* Map subscribers to their APs using google maps (or similar)
* create a well documented API, device template, and theming/branding system
* allow other people to create/submit device templates for linux/windows hosts, routers, switches, etc
* allow custom SNMP OID polling
* custom ssh scripts/agents
