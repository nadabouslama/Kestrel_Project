# Simulation d’attaques sur des environnements virtuels avec Kestrel

Ce projet vise à simuler des attaques sur un environnement virtuel et à analyser les traces post-attaque à l’aide de la plateforme Kestrel, en s'appuyant sur des techniques documentées par le framework MITRE ATT&CK.

---

## Objectifs
- Simuler une attaque sur une machine cible via une machine Kali Linux
- Utiliser **Nmap** et **Wireshark** pour analyser le réseau
- Convertir les traces Wireshark en **STIX**
- Installer et configurer **Kestrel** avec **ElasticSearch**
- Identifier les tactiques MITRE ATT&CK mises en œuvre
- Analayse Post attaque

---

## Environnement technique
- **Oracle VirtualBox** – Virtualisation 
  
https://www.oracle.com/ca-en/virtualization/technologies/vm/downloads/virtualbox-downloads.html

- **Kali Linux 2023.3** – Machine d’attaque
  
https://www.kali.org/get-kali/#kali-platforms

- **Jupyter Notebook** –

  https://jupyter.org/

- **Kestrel** (dernière version, via virtualenv `huntingspace`)
  
https://kestrel.readthedocs.io/en/latest/index.html

- **Nmap** – Scan réseau
  
  https://www.stationx.net/nmap-cheat-sheet/
  
- **Wireshark** – Analyse des paquets
  
  https://www.wireshark.org/download.html
  
- **ElasticSearch** – Backend de données
  
https://www.elastic.co/

---

## Scénario d'attaque simulée

Technique MITRE ATT&CK :  
 **T1046 – Network Service Scanning**
