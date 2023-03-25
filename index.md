# La domotique et maisons connectées

## Contexte

Cette page a pour objectif de rendre compte de mon travail réalisé dans le cadre du Mos 'Nouvelle Technologies de l'information et de la Communication" à l'École Centrale de Lyon. Il présente plusieurs articles liés au domaine du rendu 3D.
Cette synthèse est découpée en trois parties principales présentant respectivement des technologies d'animation, de génération procédural et de rendu photoréaliste. 

## Animation
Cette partie comprends principalement des articles liés à l'animation. Utilisants par exemple des modèles physique ou de reseaux de neuronnes profonds.

### [Learning Time-Critical Responses for Interactive Character Control](https://mrl.snu.ac.kr/research/ProjectAgile/Agile.png)
Utilisation du Deeplearning pour l'animation automatique d'un personnage en interaction avec son environnement.
![](https://mrl.snu.ac.kr/research/ProjectAgile/Agile.png)

### [Scalable Muscle-actuated HumanSimulation and Control ](https://mrl.snu.ac.kr/research/ProjectScalable/Page.htm)

Simulation physique d'un corp humain présentant plusieurs handicapes par un ensemble d'environ 300 muscles/tendons rattachés à un squelette articulé. 
![](https://mrl.snu.ac.kr/research/ProjectScalable/Page.files/image002.png)

### [Lion Ziva](https://zivadynamics.com/case-study/lion)

Simulation du squelettes, des muscles, de la peau et de la graisse d'un lion pour le rendu obtenir un rendu réaliste.

### [Fast Fluid Simulations with Sparse Volumes on the GPU](https://people.csail.mit.edu/kuiwu/GVDB_FLIP/gvdb_flip_teaser.jpg)

Méthode efficace pour de grosses simulation de fluides utilisant plus de 10 millions de particules. 

![](https://people.csail.mit.edu/kuiwu/GVDB_FLIP/gvdb_flip_teaser.jpg)

### [https://visualcomputing.ist.ac.at/publications/2021/MADYPG/](Mechanics-Aware Deformation of Yarn Pattern Geometry)
![](https://visualcomputing.ist.ac.at/publications/2021/MADYPG/teaser.jpg)
Simulation de tissus prennant en compte la géometrie du tissage.

## Generation procédurale

### [Synthetic Silviculture: Multi-scale Modeling of Plant Ecosystems](https://storage.googleapis.com/pirk.io/projects/synthetic_silviculture/index.html)

Génération procédurale d'une forêt et de son évolution en fonction de la météo sur plusieurs années.
Prise en compte de plusieurs type d'arbres qui rentrent en concurence dans le même environnement.

![](https://storage.googleapis.com/pirk.io/projects/synthetic_silviculture/images/teaser.jpg)


### [Amendment for Inverse Control of Parametric Shapes](https://perso.telecom-paristech.fr/boubek/papers/DAG_Amendment/)

Paramètrisation rapide de modèles 3D avec l'usage d'apprentissage profond.

![](https://perso.telecom-paristech.fr/boubek/papers/DAG_Amendment/)


### [Multimodal Conditional Image Synthesis with Product-of-Experts GANs](https://deepimagination.cc/PoE-GAN/)

Utilisation d'un réseau de neurone du type GAN ("Generative Adversarial Networks") pour la génération de paysages photoréalistes.

![](https://deepimagination.cc/PoE-GAN/images/teaser/g_out.jpg)

### [Photorealistic Material Editing Through Direct Image Manipulation ](https://users.cg.tuwien.ac.at/zsolnai/gfx/photorealistic-material-editing/)
Génération de materiaux, à partir d'image de référence. Habituellement ce travail doit être fait par un artiste ce qui peut lui prendre un temps important.
![](https://users.cg.tuwien.ac.at/zsolnai/wp/wp-content/uploads/2019/09/teaser3-1030x669.jpg)

## Image
Cette partie se concentre sur les méthodes de rendu, et plus particulièrement sur le transport de lumière.

### [NVIDIA RTX Technology](https://developer.nvidia.com/rtx/ray-tracing)
Ensemble de technologies utilisées par NVIDIA pour permettre l'utilisation du raytracing en temps réel
![](https://developer.nvidia.com/sites/default/files/akamai/nvidia-rtx-direct-illumination.jpg)

### [NVIDIA Ampere Architecture](https://developer.nvidia.com/nvidia-ampere) 
Hardware dédié au raytracing permettant d'utiliser cette technologie en temps réel.
![](https://developer.nvidia.com/sites/default/files/akamai/nvidia-deep-learning-super-sampling-800x440.jpg)

### [NVIDIA Deep Learning Super Sampling (DLSS)](https://developer.nvidia.com/rtx/ray-tracing/dlss) 
Réseau de neuronne profond permettant le debruitage des images à la sortie du raytracer.

### [Metropolys light transport](https://graphics.stanford.edu/papers/metro/)

Technique avancée de de rendu photoréaliste remarquablement efficace pur trouver les régions les plus claires de la scène en construisant un nombre plus important de rayons qui visent ces régions. 
Amélioration de la méthode d'intégration par Monte Carlo habituellement en usage pour le path tracing. 

![](http://graphics.stanford.edu/papers/metro/fig6.jpg)

### [Deep Scattering](http://simon-kallweit.me/deepscattering/)

Utilisation d'un réseau de neurone pour le rendu photoréaliste de milieux participatifs. Par exemple le rendu du nuage.

![](http://simon-kallweit.me/deepscattering/deepscattering.jpg)