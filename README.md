#  Analyse de Trafic Réseau avec Wireshark

**Auteur :** Yacine SEHLI  
**Type :** Analyse Forensique Réseau / Packet Sniffing  
**Outil :** Wireshark  

---

##  Résumé du Projet
Ce dépôt contient un rapport d'analyse technique approfondie de captures réseau réalisées dans différents contextes (Loopback, Ethernet, Wi-Fi). L'objectif est de démontrer la capacité à intercepter, décoder et interpréter les flux de données pour identifier les comportements normaux et les anomalies potentielles.

##  Compétences Démontrées
* **Capture de Paquets :** Maîtrise de l'interface Wireshark et de la sélection d'interfaces.
* **Filtrage Avancé :** Utilisation de filtres d'affichage (ex: `http`, `tls`, `ip.addr`) pour isoler le trafic pertinent.
* **Analyse Protocolaire :**
    * **HTTP/DNS :** Analyse de trafic en clair.
    * **TLS :** Inspection du handshake SSL/HTTPS.
    * **ICMP :** Diagnostic de connectivité.
* **Statistiques :** Utilisation des outils statistiques de Wireshark (I/O Graphs, Protocol Hierarchy) pour visualiser la répartition du trafic.

##  Contenu du Dépôt
* **`Rapport_Analyse_Wireshark.pdf`** : Le rapport complet détaillant l'analyse de trois scénarios de capture.
* **`evidence/`** : Captures d'écran illustrant l'interface d'analyse et les flux interceptés.

##  Points Clés du Rapport
Le rapport analyse trois types de trafic :
1.  **Loopback :** Trafic inter-processus local (diagnostic).
2.  **Ethernet :** Trafic utilisateur standard (Web, DNS, SSH).
3.  **Wi-Fi :** Analyse des spécificités sans fil (trames de management, retransmissions).

---
*Projet réalisé dans le cadre de mon apprentissage en cybersécurité.*