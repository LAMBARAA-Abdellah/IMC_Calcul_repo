# 📱 IMC For II-Master BDCC

Bienvenue dans l'application **IMC For II-Master BDCC**, un outil simple et intuitif conçu pour vous aider à comprendre votre état de santé à travers le calcul de votre **Indice de Masse Corporelle (IMC)**.

---

## 🧠 Pourquoi cette application ?

Dans un monde où la santé est une priorité, connaître son IMC est un indicateur utile pour évaluer sa corpulence.  
Cette application a été pensée pour :

- Vous permettre d’entrer vos données facilement
- Vous donner un résultat instantané
- Vous guider avec une **image adaptée à votre catégorie**

---

## 🔍 Comment ça fonctionne ?

1. Vous entrez votre **poids (en kg)**
2. Vous entrez votre **taille (en cm)**
3. Vous appuyez sur **"Calculer IMC"**
4. L’application vous affiche :
  - 🎯 **Votre IMC** (ex: 27.77)
  - 🧍‍♂️ Une **image** selon votre catégorie
  - 🗣️ Un **texte** (ex : "Surpoids", "Normal", etc.)

---

## 📊 Classification des IMC

| Catégorie         | Valeur IMC           |
|-------------------|----------------------|
| Maigreur          | Moins de 18.5        |
| Poids normal      | 18.5 à 24.9          |
| Surpoids          | 25 à 29.9            |
| Obésité modérée   | 30 à 39.9            |
| Obésité sévère    | 40 et plus           |

---

## 🖼️ Aperçu visuel

| Catégorie | Capture |
|-----------|---------|
| Maigreur | ![maigreur](captures/maigre1.png) |
| Normal | ![normal](captures/normal1.png) |
| Surpoids | ![surpoids](captures/surpoid1.png) |
| Obésité | ![obesite](captures/obesite1.png) |

---

## ⚙️ Technologies

- Kotlin & XML
- Android SDK 33+
- `EditText`, `ImageView`, `Button`, `TextView`, `ConstraintLayout`

---

## 🛠 Détails techniques

- Calcul de l’IMC :
  \[
  \text{IMC} = \frac{\text{Poids}}{(\text{Taille} / 100)^2}
  \]
- Résultat arrondi à **2 chiffres**
- Traitement logique côté `MainActivity.kt`

---

## 👨‍🎓 Réalisé par

**Abdellah Lambaraa**  
_Master II Big Data & Cloud Computing – ENSET Mohammedia_

---

## 📁 Structure du dossier `captures/`

---

## 📄 Licence

Ce projet est fourni dans le cadre d’un exercice académique.  
Toute réutilisation publique doit mentionner l’auteur.

---
