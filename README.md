# Projet-UFW
# 🛡️ UFW-Hardening: De l'Attaque à la Remédiation

> *"Mieux vaut un pare-feu bien configuré qu'une brèche silencieuse."*

Ce projet plonge au cœur de la sécurité périmétrique Linux. Plutôt que de simplement documenter des commandes, nous avons adopté une démarche **"Red Team vs Blue Team"** : simuler des vulnérabilités réelles pour comprendre comment les neutraliser efficacement avec **UFW (Uncomplicated Firewall)**.

---

## 🎯 La Philosophie du Projet
La compétence d'un ingénieur en cybersécurité ne se résume pas à savoir appliquer des règles. Elle réside dans la capacité à **comprendre l'attaquant**, à interpréter les traces qu'il laisse, et à concevoir des contre-mesures qui tiennent la route en production.

Dans ce projet, nous avons bâti un laboratoire isolé pour :
1.  **Simuler** des vecteurs d'attaques réalistes (Kali Linux).
2.  **Analyser** les logs système pour comprendre l'impact d'une intrusion.
3.  **Durcir** le système avec des règles UFW stratégiques.

---

## 🛠️ Stack Technique
* **Systèmes :** Ubuntu 22.04 (Cible), Kali Linux (Attaquant)
* **Pare-feu :** UFW (Front-end Iptables)
* **Outils d'attaque :** Nmap (Reconnaissance), Hydra (Force brute), DVWA (Application web vulnérable)
* **Services attaqués :** SSH (Port 22), Serveur HTTP Python (Port 8080), Apache/Web (Port 80)

---

## 🚀 Les 3 Scénarios d'Attaque

| Vecteur d'attaque | Risque identifié | Solution UFW déployée |
| :--- | :--- | :--- |
| **SSH Brute Force** | Compromission de compte via Hydra | Mise en place de la règle `limit` |
| **Exposition HTTP Python** | Fuite de données / Accès non autorisé | Bloquage strict des ports non utilisés |
| **Attaque Web (DVWA)** | Injection & Vulnérabilités applicatives | Politique de sécurité "First Match Wins" |

---

## 📖 Accéder au Rapport Complet
Pour une analyse détaillée des commandes, des logs système et de la politique de sécurité finale, vous pouvez consulter le rapport complet :

👉 **[Télécharger le rapport technique PDF]([Rapport_Projet_Cybersecurité.pdf])**

---

## 👨‍💻 L'Équipe
Ce projet a été réalisé dans le cadre du module Sécurité des Réseaux & Systèmes à l'**École Mohammadia d'Ingénieurs (EMI)** sous la direction de Mme Asmae KASSIRI.

* **ABOUBAKAR Abdelaziz**
* **DIN Isaac Kaougahi**
* **KAFANDO Mohamed**
* **ZOUNGRANA Abdoul Gafarou**

---
*Ce dépôt est un témoignage de notre engagement pour une sécurité proactive et rigoureuse.*
