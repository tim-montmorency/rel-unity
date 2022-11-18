# KlakNDI de Keijiro

KlakNDI permet d'envoyer l'image de la scène, de la caméra ou d'une texture par NDI.

## Installation dans Unity

Pour installer [KlakNDI](https://github.com/keijiro/KlakNDI) de Keijiro nous evons l'ajouter dans la liste de paquets.

Voici l'information à inscrire dans les paramètres du gestionnaire de paquets (voir figure ci-bas) :
* Name: `Keijiro`
* URL: `https://registry.npmjs.com`
* Scope: `jp.keijiro`

![Ajoutez le régistre de paquets de Keijiro](./Diapositive1.SVG)

## Ajout à la scène

![Créez un GameObject que vous nommez «NDI Sender» et ajoutez-y le Script «NDI Sender» tout en sélectionnant le mode de capture «Game View»](./klakndi_ajout_scene.svg)

## Configuration de la Game Window

La «Game Window» doit toujours être visible si vous voulez que le flux NDI soit mise à jour. Si elle est cachée, le flux NDI sera pausé. Il est donc recommandé de :
* Détachez la fenêtre «Game Window»
* Vérouillez la résolution de la «Game Window»

![Détachez la «Game Window» et vérouillez sa résolution](./klakndi_game_window.svg)

## Tester avec le «Studio Monitor» de NDI Tools

![Visualisez le flux NDI de KlakNDI avec le «Studio Monitor» de NDI Tools](./klakndi_ndistudiomonitor.svg)