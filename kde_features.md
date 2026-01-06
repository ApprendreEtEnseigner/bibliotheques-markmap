Parfait — **KDE Connect** 👍  
Je vous fais une **fiche pratique “comme un pavé tactile”** avec des **gestes + exemples concrets** (Windows/PC), et je clarifie aussi un point important : **le “pinch-to-zoom” (pincer/écarter) n’est pas une fonction standard fiable dans KDE Connect pour zoomer tout le bureau** (il y a même des demandes de fonctionnalité pour l’ajouter). [\[techcommun...rosoft.com\]](https://techcommunity.microsoft.com/blog/microsoft-security-blog/gesture-list-for-the-touch-and-mouse-pointer-input-modes-for-the-remote-desktop-/248596), [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

---

# 1) Où se trouve le “pavé tactile” dans KDE Connect ?

Sur le téléphone :

1.  Ouvrez **KDE Connect**
2.  Touchez votre PC (le nom de l’appareil)
3.  Ouvrez **Remote Input / Entrée à distance**
4.  Vous verrez un **grand pavé** (zone tactile) + parfois un **clavier** (icône clavier)

✅ KDE Connect annonce bien la fonction **Virtual Trackpad** (pavé tactile virtuel). [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

---

# 2) Gestes de base (les 80% qui servent tout le temps)

## A) Déplacer le curseur (comme un trackpad)

**Geste :** glisser **1 doigt** sur la zone tactile  
**Effet :** le curseur bouge sur l’écran du PC

**Exemple pratique :**

- Ouvrir le menu Démarrer : glissez vers le bouton Windows → cliquez.

---

## B) Clic gauche (sélectionner / ouvrir)

**Geste :** **tap 1 fois** avec 1 doigt  
**Effet :** clic gauche

**Exemples :**

- **Ouvrir un dossier** : placez le curseur → tap
- **Cliquer un bouton** (“OK”, “Suivant”) : placez le curseur → tap

---

## C) Double-clic (ouvrir rapidement)

**Geste :** **tap 2 fois** rapidement (comme un double-clic souris)  
**Effet :** ouvre un fichier / application

**Exemple :**

- Double-clic sur “Chrome” ou sur un fichier PDF pour l’ouvrir.

---

## D) Clic droit (menu contextuel)

Selon les versions/phones, c’est souvent :

- **tap à 2 doigts** **ou** un **appui long** (1 doigt)

**Exemple :**

- Sur le Bureau Windows, clic droit → “Nouveau” → “Dossier”
- Sur un fichier, clic droit → “Renommer”

> ℹ️ KDE Connect fournit une “entrée à distance” type souris/trackpad (Virtual Trackpad). [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

---

## E) Défilement (scroll)

**Geste courant :** glisser **2 doigts** vers le haut/bas  
**Effet :** scroll dans une page web, PDF, liste…

**Exemples :**

- Sur une page web : 2 doigts vers le bas → la page descend
- Dans un long dossier Windows : 2 doigts → vous naviguez dans la liste

---

# 3) Gestes avancés (super utiles)

## A) Glisser-déposer (drag & drop)

C’est le geste le plus “technique” au début.

### Méthode 1 (la plus fréquente)

1.  Placez le curseur sur l’icône/fichier
2.  **Appui long** (comme pour “attraper”)
3.  Sans relâcher, **glissez** vers l’endroit cible
4.  **Relâchez**

**Exemple :**

- Déplacer un fichier du Bureau vers un dossier :  
  “Fichier” → appui long → glisser vers le dossier → relâcher.

### Méthode 2 (si l’app propose un bouton “drag”)

Certaines interfaces KDE Connect affichent des boutons (clic gauche/droit).  
Vous maintenez “clic gauche” actif + vous déplacez.

---

## B) Sélectionner du texte (comme à la souris)

1.  Placez le curseur au début du texte
2.  **Appui long** (ou “drag”) pour maintenir le clic
3.  Glissez jusqu’à la fin du texte
4.  Relâchez

**Exemple :**

- Sélectionner une phrase dans Word / navigateur pour la copier.

---

## C) Ouvrir le clavier du téléphone pour taper sur le PC

Dans **Remote Input**, appuyez sur l’icône **clavier** (si disponible).  
**Exemple :**

- Ouvrir “Exécuter” sur Windows (Win+R) puis taper `notepad` (si vous avez un moyen d’envoyer Win+R via raccourci/commande — voir section zoom/commandes ci-dessous).

---

# 4) Zoom / Dézoom avec KDE Connect : ce qui marche “en vrai”

### ⚠️ Important

Le geste **pincer/écarter** pour zoomer “le bureau” **n’est pas garanti** dans KDE Connect (demande de fonctionnalité “Pinch Zoom”). [\[techcommun...rosoft.com\]](https://techcommunity.microsoft.com/blog/microsoft-security-blog/gesture-list-for-the-touch-and-mouse-pointer-input-modes-for-the-remote-desktop-/248596), [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

👉 Donc je vous donne **3 méthodes fiables** selon ce que vous voulez zoomer.

---

## Méthode 1 — Zoom dans le navigateur / PDF (la plus simple)

Dans Chrome/Edge (ou PDF), utilisez les raccourcis clavier :

- **Zoom +** : `Ctrl` + `+`
- **Zoom -** : `Ctrl` + `-`
- **Retour à 100%** : `Ctrl` + `0`

✅ **Exemple :**

- Vous lisez un PDF : au lieu de “pinch”, faites `Ctrl` + `+` 2 fois pour agrandir.

> Si KDE Connect vous affiche un clavier, vous pouvez appuyer sur `Ctrl` puis `+` (selon l’interface/clavier). KDE Connect met en avant le trackpad et des fonctions de contrôle (Virtual Trackpad). [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

---

## Méthode 2 — Zoom Windows (Loupe / Magnifier) (très efficace)

Windows a une loupe intégrée :

- **Activer la loupe** : `Win` + `+`
- **Dézoomer** : `Win` + `-`
- **Quitter** : `Win` + `Esc`

✅ **Exemple :**

- Sur un écran TV ou de loin : `Win`+`+` → vous voyez tout plus gros immédiatement.

_(Si vous n’arrivez pas à envoyer la touche Windows depuis KDE Connect, passez à la Méthode 3.)_

---

## Méthode 3 — Utiliser “Run Commands / Commandes personnalisées” (le hack pro)

KDE Connect permet des **commandes personnalisées** (“Run Commands”) pour exécuter des actions.  
➡️ Sur Windows, on peut s’en servir pour déclencher un script ou une action qui fait zoom + / zoom - (selon votre configuration). [\[lorenzobettini.it\]](https://www.lorenzobettini.it/2017/02/touchpad-gestures-in-linux-kde-with-libinput-gestures/)

**Exemple d’idée :**

- Créer 2 commandes :
  - “Zoom +”
  - “Zoom -”
- Et les lancer depuis le téléphone en 1 tap.

📌 Si vous me dites votre **version de KDE Connect sur Windows** (et si vous voyez “Run Commands”), je vous propose une configuration simple adaptée.

---

# 5) Exercices rapides (2 minutes) pour maîtriser

Faites ces mini-tests et vous serez à l’aise :

### Exercice 1 : précision

- Ouvrez **Paramètres Windows**
- Essayez de cliquer exactement sur une petite flèche/menu
  → Objectif : micro-glissements + clic

### Exercice 2 : scroll

- Ouvrez une page web longue
- Faites 10 scrolls vers le bas puis 10 vers le haut

### Exercice 3 : drag & drop

- Créez un dossier sur le Bureau
- Glissez un fichier dedans (appui long → glisser → relâcher)

---

# 6) Dites-moi juste 2 infos pour que je vous fasse une “fiche gestes” parfaitement exacte

1.  Vous êtes sur **Android ou iPhone** ?
2.  Dans KDE Connect → Remote Input, est-ce que vous voyez :
    - un **bouton clavier** ?
    - des **boutons clic gauche/droit** ?
    - une section **Run Commands / Commandes** ?

Avec ça, je vous décris **exactement** les gestes qui marchent sur _votre_ interface (et je vous propose la meilleure méthode pour le zoom selon votre usage : web/PDF ou loupe Windows).
