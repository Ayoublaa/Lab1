# Lab 1 – HelloToast 🍞

## Description

HelloToast est une application Android simple développée dans le cadre du **Lab 1**. Elle permet d'afficher un message Toast personnalisé et de compter le nombre de clics effectués.

---

## Fonctionnalités

- **Bouton TOAST** : affiche un message Toast `"Bonjour Ayoub!"` en bas de l'écran
- **Bouton COUNT** : incrémente un compteur affiché au centre de l'écran
- Le compteur augmente à chaque appui sur le bouton COUNT

---

## Démonstration

> 📹 Vidéo de démonstration : [Lab1.mp4](./Lab1.mp4)

---

## Aperçu de l'application

| Élément | Description |
|---|---|
| Bouton TOAST | Affiche `"Bonjour Ayoub!"` |
| Compteur | Nombre affiché en grand au centre |
| Bouton COUNT | Incrémente le compteur de 1 |

---

## Structure du projet

```
HelloToast/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/hellotoast/
│   │       │   └── MainActivity.java
│   │       ├── res/
│   │       │   ├── layout/
│   │       │   │   └── activity_main.xml
│   │       │   └── values/
│   │       │       ├── strings.xml
│   │       │       └── themes.xml
│   │       └── AndroidManifest.xml
│   └── build.gradle
├── build.gradle
├── settings.gradle
└── gradle.properties
```

---

## Technologies utilisées

- **Langage** : Java
- **IDE** : Android Studio
- **Émulateur** : Pixel 6 Pro – API 33
- **Android Gradle Plugin** : 8.1.0
- **Gradle** : 8.5
- **minSdk** : 24
- **targetSdk** : 34

---

## Comment exécuter le projet

1. Cloner ou télécharger le projet
2. Ouvrir le dossier dans **Android Studio**
3. Attendre la synchronisation Gradle
4. Lancer l'émulateur ou connecter un appareil Android
5. Cliquer sur ▶️ **Run**

---

## Résultat attendu

- L'application s'ouvre avec deux boutons et un compteur à `0`
- Appuyer sur **COUNT** → le chiffre s'incrémente
- Appuyer sur **TOAST** → le message `"Bonjour Ayoub!"` apparaît en bas de l'écran

---

## Auteur

**Ayoub**  
Lab 1 – Développement Mobile Android
