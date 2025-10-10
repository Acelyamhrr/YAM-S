# 🎲 Projet Yam's (C# + Web)

## 📝 Description courte
Projet réalisé dans le cadre du cours de programmation à l’IUT.  
Il s’agit d’un **jeu de Yam’s** développé en **C# (console)**, avec une **interface web** permettant d’afficher les résultats à partir d’un fichier **JSON** généré automatiquement à la fin de la partie.

---

## 💻 Technologies utilisées
- C# (console)
- HTML / CSS / JavaScript
- JSON pour la sauvegarde des résultats

---

## ⚙️ Fonctionnalités

### 🧩 Côté C# (jeu console)
- Lancers de dés et gestion des tours  
- Calcul automatique des scores par joueur  
- Sauvegarde automatique des résultats dans un fichier `res.json`  
- Partie jouable intégralement dans le terminal  

### 🌐 Côté Web (HTML / CSS / JS)
- Lecture du fichier `res.json` généré par le jeu  
- Affichage clair et dynamique des scores  
- Fonctionne **autonomement en local**  
- Compatible initialement avec le site du professeur *(aujourd’hui probablement inactif)* :  
  👉 [yams.iutrs.unistra.fr:3000](http://yams.iutrs.unistra.fr:3000)

> 💡 Même sans le site du prof, il suffit d’ouvrir la page web `index.html` et d’y importer ton fichier `res.json` pour visualiser les résultats localement.

---

## 🚀 Installation & lancement

### 🎮 Lancer le jeu C#
1. Ouvrir le projet dans **Visual Studio**, **VS Code**, ou tout autre IDE compatible C#.  
2. Compiler puis exécuter :
   ```bash
   csc main.cs
   main.exe
