
Netzwerkname: ServerNetzwerk
Netzwerkkürzel: srvNet
Subnet: 10.123.100.0/24
Gateway: 10.123.100.1
Beschreibung:

| ip             | hostname  | domain             | service        | beschreibung          | port |     |
| -------------- | --------- | ------------------ | -------------- | --------------------- | ---- | --- |
| 10.123.100.4   | apt-cache | srv.mm-homelab.org | apt cache      |                       |      |     |
| 10.123.100.11  | gotify    | srv.mm-homelab.org | gotify         | notifications         |      |     |
| 10.123.100.12  | uptime    | srv.mm-homelab.org | uptime kuma    | monitoring            |      |     |
| 10.123.100.13  | n8n       | srv.mm-homelab.org | n8n            |                       | 5678 |     |
| 10.123.100.14  | nodered   | srv.mm-homelab.org | node red       |                       | 1880 |     |
| 10.123.100.15  | paperless | srv.mm-homelab.org | paperless      | document management   | 8000 |     |
| 10.123.100.50  | docker1   | srv.mm-homelab.org | docker1        | dockerhost            |      |     |
| 10.123.100.50  | docker1   | srv.mm-homelab.org | docker1        | dockerhost            |      |     |
| 10.123.100.201 | nuc1      | srv.mm-homelab.org | proxmox        | Proxmox PVE Node1     |      |     |
| 10.123.100.202 | nuc2      | srv.mm-homelab.org | proxmox        | Proxmox PVE Node2     |      |     |
| 10.123.100.205 | backup    | srv.mm-homelab.org | proxmox backup | Proxmox Backup Server |      |     |
| 10.123.100.250 | adminvm   | srv.mm-homelab.org | Admin VM       | Ubuntu Linux          |      |     |
| 10.123.100.251 | nas1      | srv.mm-homelab.org | NAS / Storage  | UGreen NAS            |      |     |
| 10.123.100.252 | backup2   | srv.mm-homelab.org | proxmox backup | Proxmox Backup Server |      |     |
| 10.123.100.252 | backup2   |                    |                |                       |      |     |


Netzwerkname: DMZ Netzwerk
Netzwerkkürzel: DMZ
Subnet: 10.123.200.0/24
Gateway: 10.123.200.1
Beschreibung:

| ip             | hostname | domain             | service | beschreibung | port |     |
| -------------- | -------- | ------------------ | ------- | ------------ | ---- | --- |
| 10.123.200.200 | pihole   | srv.mm-homelab.org | PiHole  | q-device     |      |     |



Netzwerkname: privatesNetzwerk
Netzwerkkürzel: privNet
Subnet: 192.168.10.0/24
Gateway: 192.168.10.1
Beschreibung:

| ip            | hostname  | domain | service | beschreibung |
| ------------- | --------- | ------ | ------- | ------------ |
| 192.168.10.10 | DesktopMM |        |         | Desktop PC   | 

Netzwerkname: DMZ2
Netzwerkkürzel: DMZ2
Subnet: 192.168.178.0/24
Gateway: 192.168.178.1
Beschreibung:

| ip              | hostname | domain              | service   | beschreibung      |
| --------------- | -------- | ------------------- | --------- | ----------------- |
| 192.168.178.100 | revproxy | rsrv.mm-homelab.org | rev Proxy | nginx on LXC      | 
| 192.168.178.210 | traefik  | mm-homelab.org      | rev Proxy | Traefik on Docker |
|                 |          |                     |           |                   |


Netzwerkname: AdminBackendNetzwerk
Netzwerkkürzel: backendNet
Subnet: 172.30.250.0/24
Gateway: 
Beschreibung:

| ip            | hostname | domain          | service         | beschreibung | port |
| ------------- | -------- | --------------- | --------------- | ------------ | ---- |
| 172.30.250.1  | sun      | net.malzahn.lan | backbone switch |              |      |
| 172.30.250.4  | jupiter  | net.malzahn.lan | edge switch     |              |      |
| 172.30.250.10 | fw1      | net.malzahn.lan | Firewall 1      |              |      |
| 172.30.250.11 | fw2      | net.malzahn.lan | Main Firewall   |              |      |
| 172.30.250.20 | ap1      | net.malzahn.lan | wlan AP1        |              |      |
| 172.30.250.21 | ap2      | net.malzahn.lan | wlan AP2        |              |      |
| 172.30.250.21 | ap2      | net.malzahn.lan | wlan AP2        |              |      |
|               |          |                 |                 |              |      |



| ip  | hostname | domain | service | beschreibung | 
| --- | -------- | ------ | ------- | ------------ |
|     |          |        |         |              |
