# 🎶 Diesis-Fidelity  
**High-Fidelity Audio OS based on Debian Bullseye & Bookworm**  

<p align="center">
  <img src="https://your-logo-url" alt="Diesis-Fidelity Logo" width="250"/>
</p>

---

### 🔥 About Diesis-Fidelity  
Diesis-Fidelity est un système d'exploitation optimisé pour la lecture audio **audiophile**, basé sur **Debian 11/12**, conçu pour offrir une restitution sonore **pure et analogique**.  

Il intègre une pile audio minimaliste et ultra-optimisée incluant :  
- **MPD** (Music Player Daemon)  
- **myMPD** (interface Web avancée)  
- **upmpdcli** (UPnP/DLNA renderer)  
- Gestion des flux **Qobuz**, **UPnP**, **DLNA**  

---

### ✅ Features  
✔️ Optimisations **temps réel (RT Kernel)**  
✔️ **DAC USB** gérés automatiquement via ALSA  
✔️ **API REST** pour intégration Android/iOS  
✔️ Compatibilité **NAS / NFS / CIFS**  
✔️ **Menu interactif** pour réglages audio (DSD, SOXR, Upsampling)  
✔️ Système **headless** (sans interface graphique inutile)  

---

### 🛠 Technologies  
- **Base** : Debian Bullseye / Bookworm  
- **Audio Engine** : MPD 0.23.17  
- **Interfaces** : myMPD, upmpdcli  
- **API** : Flask REST API  
- **Optimisation CPU** : xxx ;-)  

---

### 📦 Components  
| Component      | License |
|---------------|---------|
| MPD           | GPLv2   |
| myMPD         | GPLv3   |
| upmpdcli      | GPLv2   |

---

### 📸 Screenshots  
*(Coming soon)*  

---
```bash
# Exemple : installer MPD custom
sudo dpkg -i mpd_0.24.0-diesis_amd64.deb
