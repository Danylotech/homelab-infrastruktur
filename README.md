# Homelab Infrastruktur

Hier dokumentiere ich den grundlegenden Aufbau meines Homelabs, das ich als praxisnahe Testumgebung für Virtualisierung und Systemadministration nutze.

## Hardware & Basis
* Host-System: MacBook Air M1
* Hypervisor: Proxmox VE

## Laufende Services
* Ubuntu Server: Virtuelle Maschine als Basis für meine Docker-Container.
* Pi-hole: Netzwerkweiter DNS-Server zum Filtern von Werbung.
* WireGuard: VPN-Tunnel für den sicheren Remote-Zugriff von unterwegs.

Mein aktueller Fokus liegt darauf, die Administration dieser Umgebung nach und nach über eigene Bash-Skripte zu automatisieren.
