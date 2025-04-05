# Simulation d’attaques sur des environnements virtuels avec Kestrel

Ce projet vise à simuler des attaques sur un environnement virtuel et à analyser les traces post-attaque à l’aide de la plateforme Kestrel, en s'appuyant sur des techniques documentées par le framework MITRE ATT&CK.

---

## Objectifs
- Simuler une attaque sur une machine cible via une machine Kali Linux
- Utiliser **Nmap** et **Wireshark** pour analyser le réseau
- Convertir les traces Wireshark en **STIX**
- Installer et configurer **Kestrel** avec **ElasticSearch**
- Identifier les tactiques MITRE ATT&CK mises en œuvre

---

## Environnement technique
- **Oracle VirtualBox** – Virtualisation
- **Kali Linux 2023.3** – Machine d’attaque
- **Kestrel** (dernière version, via virtualenv `huntingspace`)
- **Nmap** – Scan réseau
- **Wireshark** – Analyse des paquets
- **ElasticSearch** – Backend de données

---

##Scénario d'attaque simulée

Technique MITRE ATT&CK :  
 **T1046 – Network Service Scanning**
