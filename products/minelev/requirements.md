### Krav

Før du går i gang med installasjonen av MinElev, må du ha på følgende på plass:
* Linux-server
  * [Docker](docker.io) installert
  * [Docker-compose](https://docs.docker.com/compose) installert
  * [Nginx](http://nginx.org) eller annen webserver installert
  * Evt. SSL-sertifikater (anbefaler [letsencrypt](https://letsencrypt.org))
* [SvarUt](https://svarut.ks.no) tilgang
  * Brukernavn
  * Passord
* [Public 360](http://www.software-innovation.com) webservice *(SIF – Generic Web Service Layer)*
  * URL til webservicens endepunkt
  * Brukernavn som har tilgang til webservice, og har rollen *administrator*
  * Passord
* [DSF](https://www.infotorg.no)
  * Tilgang til metoden *hentForeldre*
  * Tilgang til å søke med kun personnummer
* AD/LDAP(s)-server
   * URL til LDAP(s) server
   * DN til bruker med leserettigheter
   * Passord
   * OU-sti til søkebase
   * Sertifikat (hvis LDAP**S**)
* [Buddy](http://buddysamarbeidet.no)
  * Domenenavn til buddydatabase
  * Lokal MSSQL-bruker
  * Passord
  * Navn på orden- og adferdsgrupper i IST Extens

