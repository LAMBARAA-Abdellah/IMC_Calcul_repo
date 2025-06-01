# 📱 IMC For II-Master BDCC

Bienvenue dans l'application **IMC For II-Master BDCC**, un outil mobile intuitif permettant de calculer votre **Indice de Masse Corporelle (IMC)** à partir de votre poids et taille.

---

## 🧠 Objectif de l’application

Cette application permet à l’utilisateur de :

- Entrer son **poids** (en kilogrammes)
- Entrer sa **taille** (en centimètres)
- Calculer automatiquement son **IMC**
- Obtenir :
  - ✅ la **valeur de l’IMC**
  - 🧍‍♂️ la **catégorie correspondante**
  - 🖼️ une **image illustrative**

---

## 🔍 Comment ça marche ?

1. Saisissez votre poids et votre taille
2. Cliquez sur **"Calculer IMC"**
3. Le système calcule :
   \[
   IMC = \frac{\text{Poids (kg)}}{(\text{Taille (m)})^2}
   \]
4. Et vous affiche :
  - 🎯 Le résultat numérique
  - 👤 La catégorie : maigreur, normal, surpoids ou obésité
  - 🖼️ Une image représentative

---

## 📊 Classification des IMC

| Catégorie         | IMC                  |
|-------------------|----------------------|
| Maigreur          | Moins de 18.5        |
| Poids normal      | 18.5 à 24.9          |
| Surpoids          | 25 à 29.9            |
| Obésité modérée   | 30 à 39.9            |
| Obésité sévère    | 40 et plus           |

---

## 🖼️ Aperçu visuel

### 🔹 Maigreur

| Interface | Résultat |
|-----------|----------|
| ![](./screenshots/maigreurScrenn.png) | ![](./screenshots/maigre1.png) |

---

### 🟢 Poids normal

| Interface | Résultat |
|-----------|----------|
| ![](./screenshots/normalSc.png) | ![](./screenshots/normal1.png) |

---

### 🟡 Surpoids

| Interface | Résultat |
|-----------|----------|
| ![](./screenshots/surpoidSc.png) | ![](./screenshots/surpoid1.png) |

---

### 🔴 Obésité

| Interface | Résultat |
|-----------|----------|
| *(Non fourni)* | ![](./screenshots/obesite1.png) |
---


| Exemple d'interface (Maigreur) |
|--------------------------------|
| ![IMC Maigreur](./screenshots/maigre1.png) |

---

| Exemple d'interface (Poids normal) |
|-----------------------------------|
| ![IMC Normal](./screenshots/normal1.png) |

---

| Exemple d'interface (SurPoids) |
|-----------------------------------|
| ![IMC Normal](./screenshots/surpoid1.png) |
### 🎮 Interface principale
<img src="screenshots/surpoid1.png" width="300" /> <img src="screenshots/surpoid1.png" width="300" />
---

| Exemple d'interface (obésité) |
|-----------------------------------|
| ![IMC Normal](./screenshots/obesite1.png) |

## ⚙️ Technologies utilisées

- **Langage** : Kotlin
- **Interface** : XML
- **IDE** : Android Studio
- **SDK cible** : 33+
- **Composants UI** :
  - `EditText`
  - `Button`
  - `ImageView`
  - `TextView`
  - `ConstraintLayout`

---

## 🛠 Structure du projet
---

## 👤 Réalisé par

**Abdellah Lambaraa**  
_Master II Big Data & Cloud Computing – ENSET Mohammedia_

---

## 📄 Licence

Projet académique développé dans un but pédagogique.  
Toute réutilisation publique doit mentionner l’auteur.