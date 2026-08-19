# 📟 RigFlowOS V1.2 — « NERD UPDATE »

**RigFlowOS (RFOS)** est un environnement logiciel expérimental conçu principalement pour **BBC micro:bit**, avec pour objectif de transformer cette petite carte en une véritable mini-plateforme interactive.

Malgré les ressources limitées du micro:bit, RFOS exploite son écran LED, ses boutons, ses broches GPIO et ses périphériques externes afin de proposer une expérience proche d'un petit système embarqué.

La **V1.2 « NERD UPDATE »** marque une étape importante dans le développement du projet avec l'arrivée de **RigFlowOS Desktop**, une version destinée au PC venant compléter l'expérience RFOS sur micro:bit.

---

## 🧠 RFOS sur micro:bit

La version micro:bit reste le **cœur historique de RigFlowOS**.

RFOS fonctionne directement sur la carte et permet notamment d'utiliser :

* 📟 Un écran OLED externe pour l'interface
* 🔘 Les boutons de la micro:bit
* 🕹️ Des joysticks et contrôleurs externes
* 🎮 Des matrices de boutons
* 🔌 Les GPIO pour connecter différents modules
* 🔊 Des fonctions sonores
* ⚙️ Un système de paramètres
* 🚀 Différents modes de fonctionnement
* 📂 Plusieurs scènes et interfaces
* 🧩 Des fonctionnalités expérimentales ajoutées progressivement

L'objectif est simple : **faire le maximum avec un minimum de matériel**.

Le micro:bit devient ainsi une petite machine capable d'exécuter son propre environnement logiciel, de communiquer avec des périphériques et d'afficher une interface personnalisée.

---

# 🆕 V1.2 — « NERD UPDATE »

La V1.2 introduit une évolution majeure dans l'architecture du projet.

### 🖥️ RigFlowOS Desktop

L'ancien concept de **MP** devient désormais une option du système et est renommé :

> **RigFlowOS Desktop**

Cette version permet de retrouver l'univers RigFlowOS directement sur PC et sert également de plateforme pour développer des fonctionnalités qui dépasseraient les capacités du micro:bit.

RFOS dispose donc désormais de deux environnements complémentaires :

**📟 RigFlowOS → micro:bit**
Le système embarqué, compact et orienté hardware.

**🖥️ RigFlowOS Desktop → PC**
L'environnement Desktop permettant d'étendre l'écosystème et d'expérimenter avec des fonctionnalités plus avancées.

---

# 🔧 Prérequis — Version micro:bit

### Minimum

Pour utiliser RFOS sur micro:bit, il faut :

* **BBC micro:bit V2**
* Un ordinateur ou appareil permettant de programmer la micro:bit
* Une connexion USB ou un moyen compatible pour transférer le programme
* **MakeCode** pour compiler et transférer RFOS

### Configuration recommandée

Pour profiter pleinement des fonctionnalités actuelles :

* 📟 **Écran OLED 128×64 I²C**
* 🔌 **Shield / breakout GPIO pour micro:bit**
* 🕹️ Joystick compatible
* 🔘 Matrice ou boutons externes
* 🧵 Câbles jumper
* 🔋 Une alimentation adaptée lorsque plusieurs périphériques sont utilisés

Les périphériques supplémentaires ne sont pas obligatoires pour démarrer RFOS, mais certaines fonctionnalités de l'interface et certains outils nécessitent du matériel externe.

---

# 🖥️ Prérequis — RigFlowOS Desktop

RigFlowOS Desktop nécessite :

* 💻 Un PC compatible
* 🧠 Un environnement capable d'exécuter la version Desktop
* 📦 Les fichiers de la version correspondante de RFOS Desktop

La configuration matérielle exacte dépend des fonctionnalités utilisées.

Contrairement à la version micro:bit, **RigFlowOS Desktop n'est pas limité aux ressources extrêmement réduites du microcontrôleur**, ce qui permet d'expérimenter avec des interfaces et des systèmes plus complexes.

---

# 🧪 État du projet

RFOS est actuellement un **projet expérimental en développement actif**.

La version micro:bit constitue toujours la partie la plus importante du projet. RigFlowOS Desktop vient désormais compléter cette base et ouvre la porte à un écosystème plus large.

Certaines fonctionnalités restent expérimentales et peuvent changer au fil des mises à jour.

La **V1.2 « NERD UPDATE »** représente donc moins une simple mise à jour de fonctionnalités qu'une évolution de l'architecture du projet.

---

## 🚀 Objectif de RigFlowOS

Le but de RFOS est de montrer qu'un matériel vendu pour quelques dizaines d'euros peut devenir une plateforme étonnamment complète lorsqu'on exploite correctement ses capacités.

**Micro:bit + OLED + GPIO + logiciel personnalisé = RigFlowOS.**

Et maintenant :

**RigFlowOS + PC = RigFlowOS Desktop.**

Le projet continue d'évoluer avec une philosophie simple :

> **Petit matériel. Gros système.**
