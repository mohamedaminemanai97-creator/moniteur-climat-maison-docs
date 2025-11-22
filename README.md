# Smart House Climate Monitor (ESP32 + MicroPython)
<svg width="100%" height="90" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Bannière Smart House Climate Monitor">
  <defs>
    <linearGradient id="grad-sh" x1="0" x2="1" y1="0" y2="0">
      <stop offset="0%" stop-color="#00a58f" />
      <stop offset="100%" stop-color="#2c3e50" />
    </linearGradient>
  </defs>
  <rect width="100%" height="90" fill="url(#grad-sh)" />
  <text x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" fill="#ffffff" font-size="24" font-family="Segoe UI, Roboto, Arial, sans-serif">Smart House Climate Monitor — ESP32 + MicroPython</text>
</svg>
<p align="center"><a href="https://wokwi.com/projects/447990912768428033" style="display:inline-block;padding:10px 16px;background:#00a58f;color:#fff;text-decoration:none;border-radius:8px;font-weight:600">▶ Voir la simulation Wokwi</a></p>

[![Wokwi](https://img.shields.io/badge/Simulate-Wokwi-00a58f?logo=wokwi)](https://wokwi.com/projects/447990912768428033)
[![MicroPython](https://img.shields.io/badge/MicroPython-ESP32-2c3e50?logo=micropython)](https://micropython.org/)
[![Licence](https://img.shields.io/badge/Licence-Éducatif-blue)](#licence)

🏠🌡️ Pitch: suivez en temps réel le climat de la maison (température, humidité, luminosité), affichez les mesures et traitez/publiez les données – le tout en MicroPython sur ESP32, prêt à simuler.

## Points forts
- Lecture multi-capteurs (environnement)
- Affichage immédiat et scripts de publication/traitement
- Architecture simple pour apprendre à structurer un projet MicroPython
- Simulation Wokwi pour tester sans matériel

## Démarrer en 60 secondes
1. Ouvrir la simulation Wokwi: https://wokwi.com/projects/447990912768428033
2. Lancer “Run” et explorer les capteurs (modifier les valeurs dans la simu)
3. Observer l’affichage et tester les scripts `publisher.py` / `simple.py`

## Cas d’usage
- Monitorer le confort domestique
- Démo éducative (capteurs + affichage + scripts)
- Base pour automatisation: alerte humidité/température, régulation d’éclairage, etc.

## Démonstration
<div>
  <img src="smart-house-demo-01.jfif" alt="Figure 1 — Smart House Climate Monitor — Démo" width="32%" />
  <img src="smart-house-demo-02.jfif" alt="Figure 2 — Smart House Climate Monitor — Démo" width="32%" />
  <img src="smart-house-demo-03.jfif" alt="Figure 3 — Smart House Climate Monitor — Démo" width="32%" />
  <p align="center"><em>Figures 1–3 — Écrans et capteurs du moniteur de climat domestique</em></p>
</div>

## Schéma & Simulation
- Schéma de câblage : voir `diagram.json` (export Wokwi)
- Simuler ce projet : https://wokwi.com/projects/447990912768428033 (voir aussi `wokwi-project.txt`)

## Fonctionnalités
- Lecture de capteurs environnementaux
- Affichage des mesures et états
- Publication/traitement (selon `publisher.py` et `simple.py`)

## Fichiers
- `main.py` : boucle principale
- `publisher.py` : publication/traitement des données
- `simple.py` : démonstration simple
- `diagram.json` : schéma Wokwi
- `wokwi-project.txt` : source/lien Wokwi

## Améliorations possibles
- Alertes (notifs) en cas de dépassement de seuil
- Historique de données et tableaux de bord
- Automatisation (piloter relais/lampe selon luminosité)

## Déploiement (ESP32 + MicroPython)
1. Flasher MicroPython sur l’ESP32.
2. Copier les scripts nécessaires (`main.py`, etc.) sur la carte.
3. Redémarrer la carte : `main.py` s’exécute automatiquement.

## Licence
Projet éducatif publié par Mohamed Amine Manai.