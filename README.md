# 🐧 Travaux Pratiques Linux – Ynov B2 Informatique

Bienvenue sur ce dépôt regroupant l'ensemble des TP Linux réalisés dans le cadre de ma formation en 2e année B2 Informatique à Ynov Campus.  
Chaque TP couvre une thématique précise liée à l'administration système Linux : gestion du stockage, services réseau, RAID, sockets, LVM, et bien plus.

## 🧠 Réalisé par :
**Arthur Chessé**

---

## 📂 Sommaire

- [🧱 TP Formatage et Partitionnement](#-tp-formatage-et-partitionnement)
- [📦 TP LVM – Gestion de volumes logiques](#-tp-lvm--gestion-de-volumes-logiques)
- [🛡️ TP RAID – Tolérance aux pannes & XFS](#-tp-raid--tolérance-aux-pannes--xfs)
- [🔌 TP Sockets – Services TCP avec Systemd](#-tp-sockets--services-tcp-avec-systemd)
- [🌐 TP Services Réseau – DHCP, DNS, HTTPS, SSH](#-tp-services-réseau--dhcp-dns-https-ssh)
- [🧩 TP Modules – Création de modules pour le noyau Linux](#-tp-modules--création-de-modules-pour-le-noyau-linux)

---

## 🧱 TP Formatage et Partitionnement

> Ajout d’un disque, partitionnement GPT, formatage EXT4, montage automatique via `/etc/fstab`, configuration de swap, et vérification via `lsblk`, `df`, `tune2fs`.

📄 [`Voir le rapport`](./TP%20Linux%20Formatage.pdf)

---

## 📦 TP LVM – Gestion de volumes logiques

> Création de volumes physiques, groupes de volumes, et volumes logiques en EXT4/FAT32. Gestion de l’espace disque, ajout de RAID comme PV, retrait de disques défectueux avec `pvmove`.

📄 [`Voir le rapport`](./TP%20Linux%20LVM.pdf)

---

## 🛡️ TP RAID – Tolérance aux pannes & XFS

> Mise en place d’un RAID 5 avec disque spare, montage XFS, automatisation via `/etc/fstab`, manipulation à chaud (HotSwap), résilience du RAID, extension de FS avec `xfs_growfs`.

📄 [`Voir le rapport`](./TP%20Linux%20Raid.pdf)

---

## 🔌 TP Sockets – Services TCP avec Systemd

> Création d’un service TCP personnalisé via systemd socket/service (`daytime`), test avec Netcat et Telnet, visualisation avec `ss`, scan avec Nmap, mise en place d’un mini service de messagerie Netcat.

📄 [`Voir le rapport`](./TP%20Linux%20Sockets.pdf)

---

## 🌐 TP Services Réseau – DHCP, DNS, HTTPS, SSH

> Mise en réseau de 2 VMs (client/serveur), configuration d’un DHCP via systemd, d’un serveur DNS avec BIND9, hébergement HTTPS avec Apache + certificats CA, pare-feu `firewalld`, accès distant SSH & Cockpit.

📄 [`Voir le rapport`](./TP%20Linux%20Service%20Réseau.pdf)

---

## 🧩 TP Modules – Création de modules pour le noyau Linux

> Écriture et compilation d’un module kernel basique (`hello.c`), utilisation de `insmod`, `lsmod`, `modinfo`, et retrait avec `rmmod`.  
> Test d’un module webcam virtuel (`v4l2loopback`) avec `ffmpeg` et `ffplay`.

📄 [`Voir le rapport`](./TP%20Linux%20Modules.pdf)

---

## 🛠️ Technologies utilisées

- Ubuntu / Debian
- Bash / Shell scripting
- LVM, RAID, XFS, EXT4, FAT32
- Apache2, BIND9, OpenSSH, Cockpit
- Systemd (socket/service)
- Netcat, Nmap, Telnet
- Virtualisation (UTM, VirtualBox)

---

## 📬 Contact

> Pour toute question ou collaboration, retrouvez-moi sur [mon portfolio](#https://arthur-chesse.vercel.app/) ou via [mon Linkedin](#https://www.linkedin.com/in/arthur-chesse/).  
Merci pour votre visite 👋

