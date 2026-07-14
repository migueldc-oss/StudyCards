# Manuel Utilisateur StudyCards

**Version 1.1**  
**Plateformes :** iOS 18+ • macOS 16+

---

## Table des matières

1. [Bienvenue](#1-bienvenue)
2. [Premiers pas](#2-premiers-pas)
3. [Organisation et tri](#3-organisation-et-tri)
4. [Mode d'étude](#4-mode-détude)
5. [Importer et exporter](#5-importer-et-exporter)
6. [Partager les flashcards](#6-partager-les-flashcards)
7. [Réglages](#7-réglages)
8. [Conseils](#8-conseils)

---

## 1. Bienvenue

Bienvenue dans **StudyCards** — une application de flashcards puissante et élégante pour iOS et macOS. Créez, gérez et étudiez vos flashcards avec support des formules LaTeX, des images et des fonctionnalités d'import/export fluides.

<img src="screenshots/ios/main.png" alt="StudyCards — iOS" width="500">
<img src="screenshots/macos/main.png" alt="StudyCards — macOS" width="500">

**Fonctionnalités principales :**

- **Groupes de flashcards :** organisez vos cartes par thème ou par matière.
- **Flashcards complètes :** chaque carte possède un recto et un verso avec support du texte, des formules LaTeX et des images.
- **Réorganisation manuelle :** glissez les flashcards pour modifier leur ordre dans un groupe.
- **Édition de groupes :** modifiez ou supprimez des groupes depuis le menu contextuel (appui long).
- **Tri et recherche :** triez et recherchez des groupes par nom, date ou nombre de flashcards.
- **Mode d'étude :** évaluez vos connaissances avec Facile/Dudé/Je ne savais pas.
- **Import et export :** transférez vos cartes via des fichiers CSV ou JSON (avec images base64 intégrées).
- **Partage :** envoyez vos flashcards par email, WhatsApp, AirDrop, et plus encore.
- **Réglages personnalisables :** apparence, langue et ordre d'étude.
- **Design adaptatif :** s'adapte automatiquement à l'iPhone, l'iPad et le Mac.

### Prérequis

- iOS 18.0 ou ultérieur / macOS 16.0 ou ultérieur.
- Connexion Internet uniquement requise pour le rendu des formules LaTeX (MathJax).

---

## 2. Premiers pas

### 2.1 Créer un groupe

Les groupes vous aident à organiser vos flashcards par thème, matière ou catégorie.

**Étapes :**

1. Ouvrez StudyCards.
2. Appuyez sur le bouton **+** sur l'écran principal.
3. Saisissez un nom pour votre groupe (par ex. « Vocabulaire espagnol », « Formules de mathématiques »).
4. Optionnellement, ajoutez une description pour identifier le contenu du groupe.
5. Appuyez sur **Enregistrer** pour confirmer.

<img src="screenshots/ios/create_group.png" alt="Créer un groupe" width="500">

<img src="screenshots/macos/create_group.png" alt="Créer un groupe - macOS" width="500">

**Conseils pour organiser les groupes :**

- Utilisez des noms descriptifs pour une identification facile.
- Envisagez de créer des groupes par matière, chapitre ou niveau de difficulté.
- Vous pouvez créer autant de groupes que nécessaire.

### 2.2 Modifier ou supprimer un groupe

Vous pouvez modifier ou supprimer un groupe directement depuis la liste.

**Sur iOS :**

1. Appuyez longuement sur le nom du groupe jusqu'à l'apparition du menu contextuel.
2. Sélectionnez **Modifier** pour changer le nom ou la description.
3. Sélectionnez **Supprimer** pour retirer le groupe et toutes ses flashcards.

**Sur macOS :**

1. Faites un clic droit sur le nom du groupe.
2. Sélectionnez **Modifier** ou **Supprimer**.

> **Avertissement :** La suppression d'un groupe supprime définitivement toutes ses flashcards. Assurez-vous de les exporter d'abord si vous avez besoin d'une sauvegarde.

### 2.3 Créer une flashcard

Une fois dans un groupe, vous pouvez commencer à ajouter des flashcards.

**Étapes :**

1. Ouvrez un groupe en appuyant dessus.
2. Appuyez sur le bouton **+**.
3. Saisissez le texte du **recto** (la question ou l'invite).
4. Saisissez le texte du **verso** (la réponse ou l'explication).
5. Optionnellement, ajoutez une **image** en appuyant sur **Sélectionner une image**.
6. Optionnellement, ajoutez une **formule LaTeX** en utilisant `$...$` (en ligne) ou `$$...$$` (bloc).
7. Appuyez sur **Enregistrer**.

<img src="screenshots/ios/create_card.png" alt="Créer une flashcard" width="500">

<img src="screenshots/macos/create_card.png" alt="Créer une flashcard - macOS" width="500">

### 2.4 Ajouter des formules LaTeX

StudyCards supporte le rendu LaTeX via MathJax pour la notation mathématique et scientifique.

| Type | Syntaxe | Exemple |
|------|---------|---------|
| En ligne | `$f(x) = x^2$` | La fonction est $f(x) = x^2$ |
| Bloc | `$$\int_0^1 x^2 \, dx$$` | Formule sur une ligne séparée |

**Exemples LaTeX :**

- **Équation quadratique :** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Théorème de Pythagore :** `$a^2 + b^2 = c^2$`
- **Intégrale définie :** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Note :** Les formules sont automatiquement rendues lors de l'enregistrement de la carte et pendant les sessions d'étude.

### 2.5 Ajouter des images

Vous pouvez joindre des images à vos flashcards pour un apprentissage visuel.

**Étapes :**

1. Lors de la création ou de la modification d'une flashcard, appuyez sur **Sélectionner une image**.
2. Choisissez de prendre une nouvelle photo ou de sélectionner dans votre bibliothèque.
3. L'image sera attachée à la flashcard.

<img src="screenshots/ios/add_image.png" alt="Ajouter une image" width="500">

<img src="screenshots/macos/add_image.png" alt="Ajouter une image - macOS" width="500">

> **Note :** Les images sont automatiquement redimensionnées à un maximum de 1024 pixels pour optimiser le stockage. Lors de l'export en JSON, les images sont incluses au format base64.

### 2.6 Supprimer une flashcard

Vous pouvez supprimer une flashcard en balayant vers la gauche.

**Étapes :**

1. Dans la liste des flashcards, balayez la carte vers la gauche.
2. Un bouton rouge **Supprimer** apparaîtra.
3. Appuyez sur **Supprimer** pour confirmer.

<img src="screenshots/ios/swipe_delete.png" alt="Balayage pour supprimer" width="500">

<img src="screenshots/macos/swipe_delete.png" alt="Balayage pour supprimer - macOS" width="500">

> **Avertissement :** La suppression est définitive. Assurez-vous d'exporter vos cartes avant de supprimer si vous n'avez pas de sauvegarde.

---

## 3. Organisation et tri

### 3.1 Réorganiser manuellement les flashcards

Vous pouvez modifier l'ordre des flashcards dans un groupe en les glissant.

**Sur iOS :**

1. Ouvrez le groupe contenant les flashcards que vous souhaitez réorganiser.
2. Appuyez sur **Modifier** dans la barre d'outils (coin supérieur gauche).
3. Des poignées de glissement ⟟ apparaîtront à côté de chaque flashcard.
4. Glissez la flashcard vers la position souhaitée.
5. Appuyez sur **Terminé** pour enregistrer le nouvel ordre.

**Sur macOS :**

1. Ouvrez le groupe contenant les flashcards que vous souhaitez réorganiser.
2. Appuyez sur le bouton **Réorganiser** (icône ↕) dans la barre d'outils.
3. Glissez la flashcard vers la position souhaitée.
4. Appuyez sur **Terminé** pour quitter le mode réorganisation.

> **Note :** L'ordre manuel est conservé lors de l'export et de l'import des flashcards.

### 3.2 Trier les groupes

Vous pouvez trier la liste des groupes selon différents critères.

**Étapes :**

1. Appuyez sur le bouton de tri (icône ↕) dans la barre d'outils.
2. Sélectionnez l'un des critères de tri :

| Critère | Description |
|---------|-------------|
| **Nom (A-Z)** | Ordre alphabétique croissant |
| **Nom (Z-A)** | Ordre alphabétique décroissant |
| **Plus récents** | Les groupes créés en premier |
| **Plus anciens** | Les plus anciens groupes en premier |
| **Nombre de flashcards** | Les groupes avec le plus de flashcards en premier |

> **Note :** Le tri s'applique aux sections **Groupes** et **Étude**.

### 3.3 Rechercher des groupes

**Sur iOS :**

1. Faites glisser vers le bas sur la liste des groupes pour afficher la barre de recherche.
2. Saisissez le nom du groupe recherché.

**Sur macOS :**

1. Utilisez la barre de recherche en haut de la barre latérale.
2. Saisissez le nom du groupe recherché.

---

## 4. Mode d'étude

Le mode d'étude est le cœur de StudyCards. Il vous permet de réviser vos flashcards de manière interactive et d'évaluer votre niveau de connaissances.

### 4.1 Commencer une session d'étude

**Étapes :**

1. Sélectionnez l'onglet **Étude** dans la barre de navigation.
2. Trouvez et sélectionnez le groupe que vous souhaitez étudier.
3. La première flashcard apparaîtra à l'écran.

<img src="screenshots/ios/start_study.png" alt="Commencer l'étude" width="500">

<img src="screenshots/macos/start_study.png" alt="Commencer l'étude - macOS" width="500">

### 4.2 Naviguer entre les cartes

Pendant une session d'étude :

1. Lisez le **recto** de la carte (la question).
2. Réfléchissez à la réponse.
3. Appuyez sur **Afficher la réponse** ou appuyez sur la carte pour révéler le **verso** (la réponse).
4. Évaluez vos connaissances avec l'un des trois boutons :

| Bouton | Signification | Description |
|--------|---------------|-------------|
| 🟢 **Facile** | Vous le saviez bien | La carte sera marquée comme maîtrisée. Elle apparaîtra moins fréquemment. |
| 🟡 **Dudé** | Vous vous en souvenez difficilement | La carte réapparaîtra bientôt pour renforcement. |
| 🔴 **Je ne savais pas** | Vous ne le saviez pas | La carte sera répétée davantage jusqu'à ce que vous l'appreniez. |

**Raccourcis clavier (macOS) :**

| Touche | Action |
|--------|--------|
| **Espace** | Retourner la carte |
| **1** | Évaluer comme Facile |
| **2** | Évaluer comme Dudé |
| **3** | Évaluer comme Je ne savais pas |

<img src="screenshots/ios/study_session.png" alt="Mode d'étude" width="500">

<img src="screenshots/macos/study_session.png" alt="Mode d'étude - macOS" width="500">

### 4.3 Terminer une session d'étude

Lorsque vous avez révisé toutes les cartes du groupe :

1. Un résumé de fin apparaîtra.
2. Vous verrez combien de cartes vous avez évaluées comme *Facile*, *Dudé* et *Je ne savais pas*.
3. Appuyez sur **Étudier à nouveau** pour répéter ou **Retour aux groupes** pour quitter.

<img src="screenshots/ios/study_summary.png" alt="Résumé d'étude" width="500">

<img src="screenshots/macos/study_summary.png" alt="Résumé d'étude - macOS" width="500">

---

## 5. Importer et exporter

StudyCards vous permet de transférer des flashcards entre des appareils ou de créer des sauvegardes à l'aide de fichiers CSV et JSON.

### 5.1 Exporter des flashcards

**Étapes :**

1. Ouvrez le groupe que vous souhaitez exporter.
2. Appuyez sur le menu d'actions et sélectionnez **Exporter**.
3. Sélectionnez le format d'export :
   - **CSV :** Format tableur. Idéal pour ouvrir dans Excel, Numbers, etc. N'inclut pas les images.
   - **JSON :** Format complet. Inclut le texte, les formules LaTeX et les images base64.
4. Choisissez où enregistrer le fichier (Fichiers, iCloud Drive, etc.).

<img src="screenshots/ios/export.png" alt="Exporter" width="500">

<img src="screenshots/macos/export.png" alt="Exporter - macOS" width="500">

### 5.2 Structure du fichier JSON

Le fichier JSON exporté possède la structure suivante :

```json
{
  "groupName": "Vocabulaire espagnol",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "Quelle est la capitale de la France ?",
      "back": "Paris.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "chaîne_base64...",
      "backImage": null
    }
  ]
}
```

### 5.3 Structure du fichier CSV

Le fichier CSV utilise les colonnes suivantes :

```csv
front,back,frontLatex,backLatex,difficulty,frontImage,backImage
"Quelle est la capitale de la France ?","Paris.","","","0","",""
```

> **Note :** Les images au format CSV sont exportées sous forme de chaînes base64 dans les colonnes `frontImage` et `backImage`.

### 5.4 Importer des flashcards

**Étapes :**

1. Dans la liste des flashcards d'un groupe, appuyez sur le menu d'actions et sélectionnez **Importer**.
2. Sélectionnez un fichier CSV ou JSON depuis votre appareil.
3. StudyCards importera les flashcards dans le groupe courant.

<img src="screenshots/ios/import.png" alt="Importer" width="500">

<img src="screenshots/macos/import.png" alt="Importer - macOS" width="500">

> **Note :** Si vous importez un fichier JSON avec des images base64, les images seront correctement affichées dans les flashcards.

### 5.5 Erreurs d'import courantes

| Erreur | Cause | Solution |
|--------|-------|----------|
| *Format non reconnu* | Le fichier n'est pas un CSV ou JSON valide | Vérifiez que le fichier a la bonne extension et n'est pas corrompu |
| *Fichier vide* | Le fichier ne contient aucune carte | Vérifiez que le fichier contient au moins une ligne de données |

---

## 6. Partager les flashcards

StudyCards facilite le partage de vos flashcards avec d'autres personnes.

### 6.1 Partager un groupe en JSON

**Étapes :**

1. Ouvrez le groupe que vous souhaitez partager.
2. Appuyez sur le menu d'actions et sélectionnez **Partager**.
3. La feuille de partage système s'ouvrira.
4. Choisissez l'application ou la méthode d'envoi :
   - **AirDrop** — pour les appareils Apple à proximité.
   - **Mail** — envoyez le fichier JSON en pièce jointe.
   - **WhatsApp** — envoyez le fichier JSON en tant que document.
   - **Messages** — envoyez via iMessage.
   - **Autres applications** — toute application acceptant les pièces jointes.

<img src="screenshots/ios/share.png" alt="Partager" width="500">

<img src="screenshots/macos/share.png" alt="Partager - macOS" width="500">

### 6.2 Recevoir des flashcards partagées

Lorsque quelqu'un vous envoie un fichier JSON StudyCards :

1. Ouvrez le fichier sur votre appareil.
2. Sélectionnez **Ouvrir dans StudyCards** ou **Importer**.
3. Le groupe sera automatiquement ajouté à votre collection.

---

## 7. Réglages

Personnalisez StudyCards selon vos préférences.

### 7.1 Apparence

Contrôlez le thème visuel de l'application.

| Option | Description |
|--------|-------------|
| **Système** | Adapte automatiquement le thème à celui de votre appareil (clair ou sombre). |
| **Clair** | Utilise toujours le mode clair. |
| **Sombre** | Utilise toujours le mode sombre. |

**Étapes :**

1. Allez dans l'onglet **Réglages**.
2. Dans la section **Apparence**, l'une des trois options.
3. Le changement est appliqué immédiatement.

<img src="screenshots/ios/appearance.png" alt="Réglages d'apparence" width="500">

<img src="screenshots/macos/appearance.png" alt="Réglages d'apparence - macOS" width="500">

### 7.2 Langue

StudyCards est disponible en 8 langues. Vous pouvez forcer une langue spécifique ou utiliser celle du système.

| Langue | Code |
|--------|------|
| **Système** | Sélectionne automatiquement la langue de l'appareil |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Étapes :**

1. Allez dans l'onglet **Réglages**.
2. Dans la section **Langue**, sélectionnez la langue souhaitée.
3. Le changement est appliqué immédiatement sans redémarrage.

<img src="screenshots/ios/language.png" alt="Réglages de langue" width="500">

<img src="screenshots/macos/language.png" alt="Réglages de langue - macOS" width="500">

### 7.3 Ordre d'étude

Définissez l'ordre par défaut dans lequel les flashcards sont affichées pendant le mode d'étude.

| Option | Description |
|--------|-------------|
| **Séquentiel** | Les cartes sont affichées dans l'ordre de création (ou l'ordre manuel si vous les avez réorganisées). |
| **Aléatoire** | Les cartes sont mélangées à chaque session. |

**Étapes :**

1. Allez dans l'onglet **Réglages**.
2. Dans la section **Ordre d'étude**, sélectionnez votre préférence.
3. Le changement s'appliquera à toutes les sessions d'étude futures.

<img src="screenshots/ios/study_order.png" alt="Réglages d'ordre d'étude" width="500">

<img src="screenshots/macos/study_order.png" alt="Réglages d'ordre d'étude - macOS" width="500">

---

## 8. Conseils

### Organisation

- **Créez un groupe pour chaque sujet ou thème.** Cela vous aidera à trouver rapidement ce que vous devez étudier.
- **Utilisez des noms clairs et courts** pour les groupes et les flashcards. Évitez les textes trop longs pour l'écran.
- **Réorganisez manuellement les flashcards** pour placer les plus importantes en premier.
- **Révisez vos groupes régulièrement.** Supprimez les cartes maîtrisées et ajoutez-en de nouvelles pour suivre vos progrès.

### Étude

- **Utilisez la répétition espacée.** Étudiez les mêmes cartes à différents jours pour consolider la mémoire à long terme.
- **N'ignorez pas les cartes difficiles.** Si vous évaluez une carte comme *Je ne savais pas*, étudiez ce groupe à nouveau bientôt.
- **Mélangez les modes d'étude.** Alternez entre l'ordre séquentiel et aléatoire pour éviter de mémoriser les positions des cartes.
- **Utilisez les raccourcis clavier** sur macOS pour étudier plus rapidement (Espace, 1, 2, 3).
- **Étudiez en sessions courtes.** 10 à 20 minutes suffisent pour une session productive.

### Contenu

- **Rédigez des questions claires et concises.** Évitez l'ambiguïté.
- **Une idée par carte.** Ne surchargez pas le recto ou le verso avec trop d'informations.
- **Utilisez des images.** Un schéma ou une image peut être plus efficace qu'un paragraphe de texte.
- **Utilisez les formules LaTeX** pour le contenu mathématique ou scientifique. Elles sont précises et ont un rendu professionnel.

### Sauvegardes

- **Exportez vos groupes régulièrement.** Enregistrez des copies sur iCloud Drive ou votre ordinateur.
- **Utilisez le format JSON** si vous souhaitez conserver les images. Le CSV ne sauvegarde que le texte.
- **Partagez vos flashcards** avec des camarades de classe ou des collègues pour collaborer sur l'étude.

### Performance

- **Fermez les autres applications** pendant l'étude pour que StudyCards fonctionne sans interruptions.
- **Maintenez l'application à jour** pour bénéficier des dernières fonctionnalités et corrections de bogues.
- **Si les formules LaTeX ne s'affichent pas**, vérifiez votre connexion Internet. MathJax doit télécharger les ressources la première fois.

---

## Informations légales

- **StudyCards** est une application développée de manière indépendante.
- L'utilisation de MathJax est soumise à sa licence Apache 2.0.
- Vos données sont stockées uniquement sur votre appareil. StudyCards ne collecte ni ne partage d'informations personnelles.

---

*Manuel Utilisateur StudyCards — Version 1.1 — Juillet 2026*
