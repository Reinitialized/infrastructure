# Overview
This document defines the bare minimal features and requirements for reinitialized.net to be usable.

# Plan
- [ ] Setup the following Services:
	- [ ] **Authentik**: account management/sso
	- [ ] **Hudu**: credentials/documentation manager for infrastructure
	- [ ] **Vaultwarden**: credentials manager for personal use
	- [ ] **Nextcloud**: files/life management
	- [ ] **Gitea**: project and source code management
- [ ] Define and implement a Disaster Recovery Plan:
	- [ ] Infrastructure Backups:
		- [ ] Equipment Configuration Backups
		- [ ] Container/Virtual Machine Backups
		- [ ] Offsite Backups
		- [ ] Periodic testing of backups
	- [ ] UPS monitoring:
		- [ ] Automated clean shutdowns when main power is lost
		- [ ] Monitoring health of batteries
- [ ] Setup and implement GPS-backed NTP server