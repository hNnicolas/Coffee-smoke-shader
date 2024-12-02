# Coffee Smoke Shader ☕ 

**Coffee Smoke Shader** est un projet d'animation 3D qui simule l'effet visuel réaliste de la vapeur qui s'échappe d'un mug de café. Ce projet se concentre sur l'interaction entre la chaleur du café et l'environnement, en générant une animation fluide et dynamique qui combine des shaders et des effets visuels réalistes. Grâce à l'utilisation de **Perlin Noise** pour simuler la fumée et un calcul précis des ombres dynamiques basées sur la chaleur corporelle, ce projet crée une ambiance immersive et esthétique autour d'une scène quotidienne.

L'animation commence avec un simple mug rempli de café, et à mesure que la chaleur monte, de la vapeur s'échappe en formant des ondulations. Le shader applique des effets de chaleur, avec des ombres qui évoluent en fonction de la vapeur générée. L'effet visuel se fait en temps réel à l'aide de **WebGL** et **Three.js**, des technologies permettant de créer des animations 3D interactives dans un navigateur web. 

Ce projet démontre la puissance de l'interaction entre les shaders et l'environnement physique simulé dans une scène 3D.

## 🛠 **Technologies utilisées**

Voici un aperçu des technologies et outils utilisés dans le projet :

| Technologie      | Description                                              | Icone                                                                                                        |
|------------------|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| **Three.js**     | Bibliothèque JavaScript pour créer des scènes 3D.        | ![Three.js](https://threejs.org/favicon.ico)                                                                 |
| **WebGL**        | API graphique pour le rendu interactif 2D et 3D.         | ![WebGL](https://img.icons8.com/ios-filled/50/000000/webgl.png)                                              |
| **GLSL**         | Langage de shading pour les effets visuels.              | ![GLSL](https://img.icons8.com/color/50/000000/code.png)                                                     |
| **Perlin Noise** | Génération procédurale pour la simulation de la fumée.   | <img src="https://github.com/hNnicolas/raging-sea-project/raw/main/3dperlinnoise-variant2.jpeg" width="50" />|
| **Blender**      | Logiciel de modélisation 3D pour créer des assets.       | <img src="https://www.blender.org/favicon.ico" width="50" />                                                 |

## 🌟 **Caractéristiques du projet**

- **Animation réaliste de la vapeur** : La fumée qui s'échappe du mug est générée à l'aide de bruit Perlin, créant un effet fluide et naturel.
- **Effets de chaleur et d'ombre** : L'intensité de la chaleur du café est simulée, influençant les ombres dynamiques qui se projettent autour du mug.
- **Shaders personnalisés** : Utilisation de **GLSL** pour créer des effets de lumière, de couleur et de mouvement, garantissant une expérience visuelle immersive.
- **Interaction 3D** : La scène est construite avec **Three.js**, permettant de visualiser et d'interagir avec l'animation de manière fluide et en temps réel.
- **Simulation physique de la chaleur** : Le projet intègre des concepts de simulation physique, comme l'échauffement du café et la diffusion de la vapeur.


## 📚 **Installation**  

1. **Téléchargez le projet** :  
   Téléchargez ou clonez ce dépôt sur votre machine locale.  

2. **Installez les dépendances** :  
   Ouvrez un terminal dans le répertoire du projet et exécutez :  
   ```bash
   npm install

3. **Lancez le projet** :
   Ouvrez un terminal dans le répertoire du projet et exécutez :
   ```bash
   npm run dev
