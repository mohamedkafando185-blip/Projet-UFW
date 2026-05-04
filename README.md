# Projet-UFW
# 🛡️ UFW-Hardening: De l'Attaque à la Remédiation

> *"Mieux vaut un pare-feu bien configuré qu'une brèche silencieuse."*

Ce projet n'est pas une simple configuration de pare-feu. C'est une immersion complète dans le cycle de vie d'une vulnérabilité : de son exploitation brutale à sa neutralisation chirurgicale. En tant qu'étudiants à l'**EMI**, nous avons relevé le défi de transformer un système poreux en une forteresse numérique.

---

## 🎯 Pourquoi ce projet me définit

Au-delà des lignes de commande, ce projet a été le terrain d'expression de mes piliers professionnels :

* **🧐 Rigueur & Analyse :** En cybersécurité, le diable est dans les détails. J'ai pris un soin particulier à l'analyse des logs et à l'ordonnancement des règles UFW. Une règle placée au mauvais endroit est une porte restée ouverte ; j'ai veillé à ce que chaque instruction réponde à une menace précise.
* **🔍 Esprit Critique :** Adopter la posture de l'attaquant (Red Team) m'a permis de ne rien laisser au hasard. Anticiper les mouvements d'un intrus pour mieux protéger l'infrastructure est, selon moi, la clé d'une sécurité proactive.
* **🤝 Intelligence Collective :** Un système complexe ne se sécurise jamais seul. Ce projet est le fruit d'une synergie d'équipe où la communication et le partage de connaissances ont été nos meilleurs alliés.

---

## 🛠️ Stack Technique & Lab
* **Systèmes :** Ubuntu 22.04 (Cible), Kali Linux (Attaquant)
* **Armement :** Nmap (Reconnaissance), Hydra (Force brute), DVWA (Audit web)
* **Défense :** UFW (Hardening), Analyse de logs `/var/log/ufw.log`

---

## 🚀 Scénarios d'Intervention

| Vecteur d'attaque | Impact Business | Remédiation Stratégique |
| :--- | :--- | :--- |
| **SSH Brute Force** | Compromission totale | Limitation dynamique des tentatives (`limit`) |
| **Shadow IT (Python HTTP)** | Fuite de données critiques | Politique "Deny by Default" & Filtrage granulaire |
| **Faille Applicative** | Défiguration / Exfiltration | Isolation des services & Priorisation des flux |

---

## 🤝 Une collaboration d'excellence
La cybersécurité est un sport d'équipe. Je tiens à saluer mes camarades de promotion avec qui j'ai eu le plaisir de confronter mes idées et de bâtir ce projet. Merci pour votre professionnalisme et votre énergie :

✨ **Abdelaziz ABOUBAKAR** | **Isaac Kaougahi DIN** | **Mohamed KAFANDO**

Un grand merci également à **Mme Asmae KASSIRI** pour son encadrement et son expertise qui nous ont poussés à l'excellence.

---

## 📖 Approfondir la réflexion
Le diable est dans l'implémentation. Pour découvrir les détails techniques, les captures d'écran des attaques et le rapport méthodologique complet :

👉 **[Consulter le Rapport Technique (PDF)](Rapport_Projet_Cybersecurité.pdf)**

---
*Ce dépôt reflète ma vision de la cybersécurité : une discipline où la technique rencontre la stratégie, portée par une rigueur constante.*
