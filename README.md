# 🎲 Projet Yam's (C# + Web)

Projet réalisé dans le cadre du cours de programmation à l’IUT.  
Il s’agit d’un **jeu de Yam’s** développé en **C# (console)**, avec une **interface web** permettant d’afficher les résultats à partir d’un fichier **JSON** généré automatiquement à la fin de la partie.

---

## Fonctionnalités

### Côté C# (jeu console)
- Lancers de dés et gestion des tours
- Calcul des scores par joueur
- Sauvegarde automatique des résultats dans un fichier `res.json`
- Partie jouable intégralement dans le terminal

### Côté Web (HTML / CSS / JS)
- Lecture du fichier `res.json` généré par le jeu
- Affichage clair et dynamique des scores
- Fonctionne **autonomement en local**
- Compatible initiallement avec le site du professeur *(aujourd’hui probablement inactif)* :  
  👉 [yams.iutrs.unistra.fr:3000](http://yams.iutrs.unistra.fr:3000)

> Même sans le site du prof, il suffit d’ouvrir la page web `index.html` et d’y importer ton fichier `res.json` pour visualiser les résultats localement.

---

## Utilisation

### Lancer le jeu C#
1. Ouvrir le projet dans **Visual Studio** ou **VS Code** (ou autre ide de votre choix)
2. Exécuter :
   ```bash
   csc main.cs
   main.exe
   ```
3. À la fin de la partie, un fichier res.json est créé avec tous les résultats.

### Visualiser les résultats

1. Ouvrir index.html dans ton navigateur
2. Importer le fichier res.json généré
3. Les scores et détails de la partie s’affichent automatiquement

### Exemple de fichier res.json
```
{
  "joueurs": [
    { "nom": "Alice", "score_total": 247 },
    { "nom": "Bob", "score_total": 198 }
  ],
  "partie": {
    "date": "2025-10-09T15:00:00",
    "nb_tours": 13
  }
}
```
