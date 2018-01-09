![Kako](docs/images/kako.png?raw=true)

This project provides Kako honeypot simulation files for a number of well known and deployed embedded device vulnerabilities.

## Simulations

Simply put, simulations provide data light-weight 'emulation' of a given target. These are defined as YAML inside of the root directory of this repository, and will be linted, loaded and provisioned during Kako startup.

The following simulations are currently included:

* `000-LinuxTelnet.yaml` - Generic Telnet
  * Simulates a vulnerable telnet service (default credentials).
* `001-CPEServer.yaml` - CPEServer SOAP
  * Simulates a vulnerable CPEServer SOAP service (command injection).
* `002-NetGear.yaml` - NetGear HTTPS
  * Simulates a vulnerable NetGear router HTTPS web interface.
* `003-D-Link.yaml` - D-Link HTTP
  * Simulates a vulnerable D-Link router HTTP web interface.
* `004-Rompager.yaml` - Unknown RomPager
  * Simulates a vulnerable router RomPager HTTP interface.
* `005-Huawei.yaml` - Huawei uPnP
  * Simulates a vulnerable Huawei uPnP interface.
* `006-Realtek.yaml` - Realtek SDK uPnP
  * Simulates a vulnerable Realtek SDK uPnP / SOAP interface.
* `007-Generic-uPnP.yaml` - Generic uPnP
  * Simulates a generic `miniupnpd` service.
* `008-Linux-uPnP.yaml` - Linux uPnP
  * Simulates a generic Linux `uPnP/1.0` service.
* `009-Linksys.yaml` - Linksys HTTP web interface.
  * Simulates a Linksys `mini_httpd` service.
* `010-TPLink.yaml` - TPLink HTTP web interface.
  * Simulates a TPLink `Router Webserver` service.

## Additional Reading

The Kako project can be found at the following URL:

* https://www.github.com/darkarnium/kako/
