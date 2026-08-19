# 🗺️ RigFlowOS — Fonctionnalités & Roadmap

Cette roadmap présente les fonctionnalités actuellement disponibles, celles en cours de développement et les idées prévues pour les futures versions de RigFlowOS.

> **L'ordre des fonctionnalités peut changer en fonction du développement et des limites du matériel.**

---

## 📟 RFOS — micro

### 🟢 Fonctionnalités disponibles

* [x] Interface RFOS personnalisée
* [x] Système de scènes
* [x] Navigation dans les menus
* [x] Menu Settings
* [x] Gestion du mode Speed
* [x] Gestion du Sound
* [x] Support OLED 128×64
* [x] Support des boutons
* [x] Support du joystick
* [x] Utilisation des GPIO
* [x] Affichage d'informations système
* [x] Système adapté au micro V2

---

## 🟡 En développement

* [ ] Optimisation des performances
* [ ] Réduction de l'utilisation mémoire
* [ ] Amélioration de l'interface OLED
* [ ] Amélioration de la navigation
* [ ] Amélioration du système de paramètres
* [ ] Meilleure gestion des périphériques
* [ ] Tests et correction de bugs
* [ ] Documentation hardware complète

---

## 🔵 Fonctionnalités prévues pour RFOS micro

* [ ] Davantage d'outils GPIO
* [ ] Support de nouveaux capteurs
* [ ] Nouveaux modes d'affichage OLED
* [ ] Système de diagnostics hardware
* [ ] Outils de test du joystick
* [ ] Outils de test des boutons
* [ ] Davantage de personnalisation
* [ ] Optimisation avancée du code

> Certaines fonctionnalités pourront être déplacées vers RigFlow Desktop si elles dépassent les capacités du micro.

---

# 🖥️ RigFlowOS Desktop

> 🟠 **EN COURS DE DÉVELOPPEMENT**

RigFlowOS Desktop est la future déclinaison PC de l'écosystème RigFlow.

Il ne s'agit **pas encore d'une version stable ou complète**.

### 🧪 Première phase

* [ ] Base de RigFlow Desktop
* [ ] Terminal / CLI
* [ ] Système de commandes
* [ ] Détection de la micro
* [ ] Communication série
* [ ] Informations sur RFOS
* [ ] Serial Monitor
* [ ] Logs

### 🔧 Phase hardware

* [ ] Monitoring de la micro
* [ ] Lecture des GPIO
* [ ] Lecture du joystick
* [ ] État des boutons
* [ ] Outils OLED
* [ ] Diagnostics hardware
* [ ] Flash / mise à jour de RFOS

### 🧠 Phase écosystème

* [ ] Système d'applications
* [ ] Support de RigFlow.App
* [ ] Gestion des outils RigFlow
* [ ] Configuration centralisée
* [ ] Communication Desktop ↔ RFOS
* [ ] API / protocole RigFlow

---

# 🔮 Futur hardware

Les futures versions pourront également explorer d'autres plateformes.

### 🟣 ESP32

* [ ] Portage expérimental de RFOS
* [ ] Wi-Fi
* [ ] Bluetooth
* [ ] Communication réseau
* [ ] Support de nouveaux périphériques

### 🟠 Raspberry Pi

* [ ] Expérimentation RFOS Linux
* [ ] GPIO
* [ ] Outils système avancés
* [ ] Serveur RigFlow
* [ ] Communication avec les autres appareils

---

# 🚀 Vision à long terme

L'objectif final n'est pas simplement de créer plusieurs programmes indépendants.

RigFlow doit progressivement devenir un **écosystème connecté** :

```text
                 RIGFLOW
                    │
       ┌────────────┼────────────┐
       │            │            │
   📟 RFOS      🖥️ Desktop   💰 RigFlow.App
   micro:bit         │            │
       │             └─────┬──────┘
       │                   │
       └───────────┬───────┘
                   │
              🧠 RigFlow Core
```

Le micro reste la plateforme hardware compacte.

Desktop devient progressivement le centre d'outils et de communication.

RigFlow.App et les futurs logiciels pourront ensuite rejoindre le même écosystème.

---

## 📌 Légende

* 🟢 **Disponible**
* 🟡 **En développement**
* 🔵 **Prévu**
* 🟠 **Projet / expérimental**
* 🔮 **À long terme**
