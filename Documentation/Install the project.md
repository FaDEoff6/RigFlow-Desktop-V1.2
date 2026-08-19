# 📥 Installation de RigFlowOS V1.2

Ce guide explique comment installer **RigFlowOS V1.2** sur une BBC micro:bit V2.

---

## 🧰 Prérequis

### Obligatoire

- BBC micro:bit **V2**
- Câble USB compatible données
- Ordinateur
- Le fichier `.hex` de RigFlowOS V1.2

### Matériel recommandé

Pour utiliser toutes les fonctionnalités actuelles de RFOS :

- 📟 OLED 128×64 I²C
- 🕹️ Joystick
- 🔘 Boutons / matrice de boutons
- 🔌 Câbles jumper
- 🧩 Shield ou breakout pour micro:bit

Les périphériques supplémentaires ne sont pas nécessaires pour installer RFOS, mais certaines fonctionnalités peuvent nécessiter leur présence.

---

# 1. Télécharger RigFlowOS

Téléchargez le fichier :

`microbit-RigFlow-Deck-V12.hex`

depuis la page principale du dépôt GitHub.

---

# 2. Connecter la micro:bit

Connectez votre **micro:bit V2** à votre ordinateur avec un câble USB.

La micro:bit devrait apparaître comme un périphérique de stockage.

---

# 3. Transférer RFOS

Faites glisser le fichier :

`microbit-RigFlow-Deck-V12.hex`

sur la micro:bit.

Le transfert démarre automatiquement.

La micro:bit redémarrera ensuite avec RigFlowOS installé.

---

# 4. Connecter l'OLED

Si vous utilisez l'écran OLED 128×64 :

- Connectez `GND`
- Connectez `VCC`
- Connectez `SDA`
- Connectez `SCL`

Vérifiez que les broches utilisées correspondent à la configuration actuelle de RFOS.

L'OLED constitue l'écran principal de l'interface RFOS.

---

# 5. Connecter les périphériques

Vous pouvez ensuite connecter les périphériques compatibles avec votre configuration.

### 🕹️ Joystick

Le joystick permet notamment de récupérer :

- Axe X
- Axe Y
- Bouton

### 🔘 Boutons

Les boutons peuvent être utilisés pour naviguer dans les différents menus et contrôler RFOS.

### 🎮 Matrice de boutons

Une matrice permet d'ajouter plusieurs commandes tout en utilisant un nombre limité de broches.

---

# 6. Premier démarrage

Une fois RFOS installé :

1. Vérifiez les branchements.
2. Allumez la micro:bit.
3. Attendez le démarrage de RFOS.
4. L'interface apparaît sur l'OLED si celui-ci est connecté.
5. Utilisez les boutons ou périphériques configurés pour naviguer.

---

# ⚠️ Problèmes courants

### L'OLED ne s'allume pas

Vérifiez :

- `VCC`
- `GND`
- `SDA`
- `SCL`
- Les broches utilisées par RFOS

### Le joystick ne fonctionne pas

Vérifiez son alimentation et les broches `X`, `Y` et `SW`.

### La micro:bit ne démarre pas correctement

Essayez de transférer à nouveau le fichier `.hex`.

Si le problème persiste, vérifiez que vous utilisez bien une **micro:bit V2**.

---

# 🖥️ RigFlowOS Desktop

> 🟠 **EN COURS DE DÉVELOPPEMENT**

RigFlowOS Desktop n'est actuellement pas une version PC finalisée.

Cette branche est encore en développement et son fonctionnement ainsi que ses fonctionnalités peuvent changer.

La version micro:bit reste actuellement la version principale de RigFlowOS.

---

## 📚 Documentation supplémentaire

- [🏠 README](../README.md)
- [🗺️ Roadmap](./ROADMAP.md)
