# 📟 RigFlowOS V1.2 — « NERD UPDATE »

**RigFlowOS (RFOS)** est un environnement logiciel expérimental développé principalement pour **BBC micro:bit V2**.

Son objectif est de pousser au maximum les capacités d'une petite carte électronique afin d'en faire une véritable mini-plateforme interactive.

RFOS propose une interface personnalisée, plusieurs scènes, des paramètres et la prise en charge de périphériques externes comme un écran OLED, un joystick ou des boutons.

La **V1.2 « NERD UPDATE »** marque également le début du développement de **RigFlowOS Desktop**, la future déclinaison PC de l'écosystème RigFlowOS.

> ⚠️ **Important : RigFlowOS Desktop est actuellement EN COURS DE DÉVELOPPEMENT.**
>
> Il ne s'agit pas encore d'une version PC complète et finalisée de RFOS. La version micro:bit reste actuellement la version principale et fonctionnelle du projet.

---

# 📟 1. RigFlowOS sur micro:bit

La version micro:bit constitue actuellement **le cœur de RigFlowOS**.

RFOS fonctionne directement sur une **BBC micro:bit V2** et peut utiliser différents périphériques connectés à ses GPIO.

### Fonctionnalités actuelles

Selon la configuration matérielle utilisée, RFOS peut notamment exploiter :

* 📟 Écran OLED 128×64 I²C
* 🔘 Boutons externes
* 🕹️ Joystick
* 🎮 Matrice de boutons
* 🔌 GPIO de la micro:bit
* 🔊 Fonctions sonores
* ⚙️ Paramètres du système
* 🚀 Modes de vitesse
* 📂 Différentes scènes et menus
* 🧩 Fonctions expérimentales

L'objectif est de construire une expérience de type **mini-système embarqué**, tout en restant compatible avec les contraintes matérielles du micro:bit.

---

# 🖥️ 2. RigFlowOS Desktop

**RigFlowOS Desktop est actuellement en développement.**

Il s'agit de la future branche PC du projet.

Son objectif est de permettre à l'écosystème RigFlowOS de dépasser les limites du micro:bit et d'expérimenter avec des fonctionnalités qui seraient trop lourdes ou complexes à exécuter sur le matériel embarqué.

### 🚧 État actuel

**Statut : 🟠 EN DÉVELOPPEMENT**

Desktop n'est donc pas encore considéré comme une version stable ou complète de RFOS.

Pour le moment :

* 📟 **RFOS micro:bit** → version principale et fonctionnelle
* 🖥️ **RigFlowOS Desktop** → branche en développement
* 🧪 Les fonctionnalités Desktop peuvent encore changer
* ⚠️ Il ne faut pas considérer Desktop comme un remplacement de la version micro:bit

La V1.2 marque surtout **le lancement officiel de cette branche**.

---

# 🔧 3. Prérequis

## 📟 Pour RigFlowOS micro:bit

### Obligatoire

* **BBC micro:bit V2**
* Un ordinateur pour programmer la micro:bit
* Une connexion USB ou Bluetooth compatible
* **Microsoft MakeCode**

### Recommandé

Pour profiter pleinement de l'interface actuelle :

* 📺 **OLED 128×64 I²C**
* 🔌 Shield / breakout GPIO
* 🕹️ Joystick
* 🔘 Boutons ou matrice de boutons
* 🧵 Câbles jumper

Les périphériques supplémentaires ne sont pas indispensables pour démarrer RFOS, mais certaines fonctionnalités nécessitent du matériel externe.

---

# 🛠️ 4. Tutoriel : installer RigFlowOS

## Étape 1 : préparer la micro:bit

Prenez votre **BBC micro:bit V2** et connectez-la à votre ordinateur avec un câble USB compatible données.

Votre ordinateur doit détecter la micro:bit comme un périphérique.

---

## Étape 2 : ouvrir MakeCode

Ouvrez **Microsoft MakeCode** et créez un nouveau projet compatible avec la **micro:bit**.

RFOS étant développé avec l'environnement MakeCode, celui-ci permet de compiler le programme et de le transférer vers la carte.

---

## Étape 3 : importer le programme RFOS

Importez le projet ou le code source correspondant à la version de RigFlowOS que vous souhaitez utiliser.

⚠️ Vérifiez toujours que vous utilisez une version prévue pour **micro:bit V2**.

---

## Étape 4 : connecter l'OLED

Si vous utilisez l'écran OLED :

1. Connectez l'alimentation du module.
2. Connectez **GND**.
3. Connectez **SDA**.
4. Connectez **SCL**.
5. Vérifiez que les broches utilisées correspondent à la configuration de RFOS.
6. Initialisez l'écran OLED dans le programme.

Une fois correctement configuré, l'écran devient l'interface principale de RFOS.

---

## Étape 5 : connecter les périphériques

Vous pouvez ensuite connecter les périphériques compatibles avec votre configuration :

🕹️ **Joystick**

Permet notamment de récupérer les valeurs X/Y et l'état du bouton.

🔘 **Boutons**

Peuvent être utilisés pour naviguer dans les menus et contrôler différentes fonctions.

🎮 **Matrice de boutons**

Permet d'ajouter plusieurs commandes avec un nombre réduit de broches.

---

# 🚀 5. Premier démarrage

Une fois le programme transféré :

1. Déconnectez puis reconnectez la micro:bit si nécessaire.
2. Allumez votre installation.
3. RFOS démarre.
4. L'interface apparaît sur l'OLED si celui-ci est connecté.
5. Utilisez les boutons ou périphériques configurés pour naviguer.
6. Explorez les différentes scènes et paramètres.

Si aucun OLED n'est connecté, certaines fonctions d'affichage peuvent évidemment ne pas être disponibles.

---

# ⚙️ 6. Configuration

RFOS possède un système de paramètres permettant de modifier certains comportements du système.

Selon la version utilisée, vous pourrez retrouver notamment des réglages comme :

### 🚀 Speed

Permet de choisir entre différents modes de fonctionnement.

### 🔊 Sound

Permet d'activer ou désactiver les fonctions sonores.

D'autres paramètres et fonctionnalités peuvent être ajoutés au fil des mises à jour.

---

# 🧪 7. Tester les périphériques

Une fois RFOS démarré, il est recommandé de tester chaque périphérique séparément.

### 🕹️ Joystick

Vérifiez :

* Axe X
* Axe Y
* Bouton du joystick

### 🔘 Boutons

Vérifiez que chaque bouton correspond bien à l'action prévue.

### 📟 OLED

Vérifiez :

* Initialisation
* Affichage
* Rafraîchissement
* Navigation dans les menus

Cette méthode permet de déterminer rapidement si un problème vient du logiciel ou du câblage.

---

# 🖥️ 8. RigFlowOS Desktop : futur du projet

La branche Desktop est destinée à devenir une extension importante de RFOS.

Cependant, **elle est encore en développement**.

Il est donc normal que :

* certaines fonctions ne soient pas disponibles ;
* l'interface évolue ;
* l'architecture change ;
* certaines idées soient encore expérimentales ;
* la version PC ne possède pas encore toutes les fonctionnalités de RFOS micro:bit.

La version Desktop doit être considérée comme un **chantier de développement**, et non comme une version finale.

---

# 🧠 9. Philosophie de la V1.2

La **NERD UPDATE** n'a pas pour objectif de transformer immédiatement RFOS en un énorme système.

Elle pose plutôt les bases de son évolution.

### Aujourd'hui

**📟 micro:bit → RFOS fonctionnel**

### Maintenant en développement

**🖥️ PC → RigFlowOS Desktop**

### À terme

**📟 + 🖥️ → un véritable écosystème RigFlowOS**

---

# 🚧 Statut de la V1.2

| Composant              | État                    |
| ---------------------- | ----------------------- |
| 📟 RFOS micro:bit      | 🟢 Fonctionnel          |
| 📟 OLED                | 🟢 Supporté             |
| 🕹️ Joystick            | 🟢 Supporté             |
| 🔘 Boutons             | 🟢 Supportés            |
| ⚙️ Paramètres          | 🟢 Fonctionnels         |
| 🖥️ RigFlowOS Desktop   | 🟠 **En développement** |
| 🧪 Nouvelles fonctions | 🟠 Expérimentales       |

---

## 🚀 RigFlowOS V1.2

**RigFlowOS V1.2 « NERD UPDATE »** représente donc une nouvelle étape du projet.

La micro:bit reste au centre de l'expérience actuelle, tandis que **RigFlowOS Desktop commence son développement en tant que future branche PC**.

> **📟 Petit hardware. 🧠 Gros potentiel. 🖥️ Et maintenant, un Desktop en construction.**
