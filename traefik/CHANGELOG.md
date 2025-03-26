# Change Log
## Versionining Notes
First three digits are Traefik's version number.
The letter & number are bug fixe releases where said issue is not with Traefik, but with this template.

## 3.3.4.d
* Adjusted nginx for dashboard sub-filters to fix rendering issue on sidebar.

## 3.3.4.c
* Fixed log level issues with (most) log levels.
* Edited base template for LE to include all needed variables for CF.
  
## 3.3.4.b
* Fixed `Unknown Level String` when setting log level.
* Added 8080/tcp to ports to allow direct access to Traefik Dashboard (http://IP_Address:8080/dashboard/)
* Added notes and references to original fork/dev.

## 3.3.4.a
* Updated docs and guidance that displays in HA.
* Updated references to old repo.
* Updated name of entrypoints to match Traefik default standards.

## 3.3.4 (Initial Release)
* 📈 Traefik v3.3.4
* 📈 HASSIO Base v17.2.2
* Change Log versioning changed to match upstream Traefik versioning.
