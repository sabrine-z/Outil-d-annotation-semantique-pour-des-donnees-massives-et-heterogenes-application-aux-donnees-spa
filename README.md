# Outil-d-annotation-semantique-pour-des-donnees-massives-et-heterogenes-application-aux-donnees-spa
À l’échelle globale, les océans, l’atmosphère et la biosphère sont l’objet de changements majeurs d’une rapidité sans précédent. Les enjeux associés à ces changements appellent à un développement de connaissances sur le système Terre. Ces connaissances sont construites par l’utilisation conjointe des données issues des observations satellites, de terrain ou encore des sorties de modèle de simulation des phénomènes étudiés. Ces divers systèmes génèrent des volumes de données considérables dans divers formats, hébergés par de nombreux centres de données et de calcul.  L’étape de découverte des données est un défi de premier ordre pour connaître leur disponibilité, assurer leur réutilisation et/ou leur combinaison pour de nouvelles analyses. Notre objectif est donc de fédérer les catalogues de données hétérogènes et fournir à l’utilisateur des données possédées pour proposer une découverte des données de tous les compartiments de la Terre.
# Problématique :

L’approche actuelle est de fédérer les bases de données existantes pour en fournir une vue complète et unifiée en vue de permettre leur interrogation. La volumétrie des données nous impose de baser nos interrogations sur les métadonnées. La transversalité des enjeux scientifiques nous demande de pouvoir rendre découvrables les données au-delà d’une discipline. Pour cela, nous avons choisi de décrire les données en utilisant une ontologie disciplinairement neutre, basée sur le paradigme d’observation [Beretta et al., 2020]. 
Actuellement, les données sont décrites dans les catalogues des systèmes d’observation. Ils sont construits sur des annotations sémantiques faiblement standardisées, incomplètes, voire imprécises. À ce stade, elles ne permettent pas de mettre en œuvre une indexation efficace sur ces grandes masses de données.
# Objectif : 
notre objectif est de transformer et enrichir les catalogues existants sur la base de l’ontologie d’observation et des ressources onto-terminologiques disciplinaires.  Du fait de l’incomplétude, de l’imprécision et de l’hétérogénéité des métadonnées, il est proposé d’explorer l’apport des techniques de classification par apprentissage pour automatiser la standardisation des annotations existantes (sémantique et syntaxique) et la classification des métadonnées en s'appuyant sur notre ontologie métier
# schéma récapitulatif :
Nous résumons notre travail avec le schéma présenté ci-dessous, qui illustre l’approche décrite et récapitule les différentes étapes détaillées.

![1](https://user-images.githubusercontent.com/65137647/136370928-c39dc002-08f9-49bb-a928-a32c3ed42813.png)
# Démarche adoptée :
![Capture1](https://user-images.githubusercontent.com/65137647/136529978-f9e9362b-50f4-4a6c-b2fe-196da3dbb997.PNG)

![image](https://user-images.githubusercontent.com/65137647/136530510-c3bf404e-757d-4ad4-8a73-4ecd5409b787.png)

![Capture](https://user-images.githubusercontent.com/65137647/136530145-d312445c-bf75-45bd-b2ec-c04b50f0070d.PNG)
Nous avons utlilisé la valeur de skos:PrefLabel comme termes standardisés.
![image](https://user-images.githubusercontent.com/65137647/136530631-c1ab4e83-35bc-4e80-a6f7-1227d135907e.png)

![Capture2](https://user-images.githubusercontent.com/65137647/136530375-14266b71-41a2-4ae2-968a-3cfcf6e367eb.PNG)

