# Créer une scène XR HDRP

## Préalables

Avant de commencer, assurez-vous que vous avez suivie les instructions de la section [Support XR en HDRP](./xr_introduction/xr_introduction.md).

## «Action Based» ou «Device Based»

Il existe souvent 2 versions (ou plus) des Scripts ou Components pour la XR. En cas de doute, choisissez la version «Action Based».

## Nouvelle scène

![Créez une nouvelle scène HDRP (de nuit ou de jour)](./Diapositive4.SVG)

## «Sky and Fog Volume» et «Motion Blur» 

![Ajoutez l'«Override» «Motion Blur» et activez son intensité à 0 pour désactiver le «Motion Blur»](./Diapositive1.SVG)

## XR Origin

![À l'aide d'un clic droit sur la caméra, la convertir en «XR Origin (Action-based)» ce qui devrait aussi ajouter un «XR Interaction Manager»](./Diapositive2.SVG)

## XRI Default Input Actions

![Ajoutez un Component «Input Action Manager» au «XR Origin» et glissez-y le «XRI Default Input Actions»](./Diapositive3.SVG)

## Prefab XR

![Ajoutez le «XR Origin» et le «XR Interaction Mangager» à un nouvel GameObjet nommé «XR Player» et convertissez le en Prefab](./Diapositive5.SVG)