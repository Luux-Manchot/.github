# 🐧 LyuX — Opération Manchot

> **Infrastructure libre, centralisée et automatisée pour la migration des lycées vers Linux.**

LyuX est un écosystème complet pensé pour les établissements scolaires : un serveur unique (Samba-AD, GLPI, LAM, Cockpit, API FastAPI), des postes identiques et remplaçables, et un déploiement piloté par Ansible.

## 🧱 Les dépôts de l'organisation

| Dépôt | Rôle | Documentation | Suivi des travaux |
| :--- | :--- | :---: | :---: |
| [**lyux-server**](https://github.com/Luux-Manchot/lyux-server) | Infrastructure & API centrale : FastAPI, Samba-AD, Docker, GLPI, Cockpit | [Wiki](https://github.com/Luux-Manchot/lyux-server/wiki) | [Issues](https://github.com/Luux-Manchot/lyux-server/issues) |
| [**lyux-desktop**](https://github.com/Luux-Manchot/lyux-desktop) | Postes clients : KDE Plasma, SDDM, OOBE, Veyon, profils Kiosk | [Wiki](https://github.com/Luux-Manchot/lyux-desktop/wiki) | [Issues](https://github.com/Luux-Manchot/lyux-desktop/issues) |
| [**lyux-os-builder**](https://github.com/Luux-Manchot/lyux-os-builder) | Générateur d'ISO universelle, SquashFS, Calamares, clé USB OOBE | [Wiki](https://github.com/Luux-Manchot/lyux-os-builder/wiki) | [Issues](https://github.com/Luux-Manchot/lyux-os-builder/issues) |
| [**lyux-import-siecle**](https://github.com/Luux-Manchot/lyux-import-siecle) | Import des exports SIÈCLE / Pronote CSV vers Samba-AD | [Wiki](https://github.com/Luux-Manchot/lyux-import-siecle/wiki) | [Issues](https://github.com/Luux-Manchot/lyux-import-siecle/issues) |
| [**lyux-applications**](https://github.com/Luux-Manchot/lyux-applications) | Applications bureau : Welcome, Station, Report, Kiosk, enrôlement | [Wiki](https://github.com/Luux-Manchot/lyux-applications/wiki) | [Issues](https://github.com/Luux-Manchot/lyux-applications/issues) |

## 📚 Documentation

Le **wiki historique** reste consultable sur [Luux-Manchot/LyuX/wiki](https://github.com/Luux-Manchot/LyuX/wiki). Son contenu sera progressivement réparti dans le wiki de chaque dépôt spécialisé, avec des liens croisés entre les pages.

La [roadmap](https://github.com/Luux-Manchot/LyuX/wiki/Roadmap) et la [feuille de route des issues](https://github.com/Luux-Manchot/LyuX/issues) sont les points de suivi transitoires.

## 🚀 Démarrage rapide

- Lancer le portail **LyuX Hub** : `http://localhost:8000`
- Depuis Windows : double-clic sur `Lancer-LyuX.bat`
- Déployer un poste : clé USB universelle générée par `lyux-os-builder`, choix de la salle puis enrôlement OTP.

## 🤝 Contribution

Les issues sont réparties par dépôt : merci d'ouvrir chaque demande dans le composant concerné (serveur, poste, ISO, import SIÈCLE ou application bureau).

---

Projet conçu et développé par **FlowCreativeStudio** · Florian ([@NayrolfRdgs](https://github.com/NayrolfRdgs)) · contact@flowcrea.fr  
*Opération Manchot — Système d'exploitation & infrastructure libre pour lycées et collèges.*
