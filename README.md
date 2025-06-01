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
| ![](./captures/maigreurScrenn.png) | ![](./captures/maigre1.png) |

---

### 🟢 Poids normal

| Interface | Résultat |
|-----------|----------|
| ![](./captures/normalSc.png) | ![](./captures/normal1.png) |

---

### 🟡 Surpoids

| Interface | Résultat |
|-----------|----------|
| ![](./captures/surpoidSc.png) | ![](./captures/surpoid1.png) |

---

### 🔴 Obésité

| Interface | Résultat |
|-----------|----------|
| *(Non fourni)* | ![](./captures/obesite1.png) |
---

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