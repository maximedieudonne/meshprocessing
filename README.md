# NIfTI Mesh Converter

Ce projet permet de **convertir un maillage médical au format NIfTI (.nii/.nii.gz) en PLY, OBJ ou GLB**, formats compatibles avec **MeshLab** et d'autres logiciels de visualisation 3D.

## Objectif
Le format **NIfTI** est souvent utilisé pour les données d'IRM ou de scanner, mais difficilement exploitable dans les logiciels 3D classiques. Ce script extrait les maillages NIfTI et les convertit en formats lisibles par **MeshLab** ou **Blender**.

## Prérequis

Avant d'utiliser le script, assurez-vous d'avoir installé les dépendances suivantes :

```bash
pip install nibabel trimesh numpy

