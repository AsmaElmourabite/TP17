
# Lab de Sérialisation de Données : JSON vs XML vs Protobuf

Ce projet est un laboratoire pratique Node.js conçu pour démontrer et comparer trois formats de sérialisation de données populaires : **JSON**, **XML** et **Protocol Buffers (Protobuf)**.

L'objectif est de comprendre comment manipuler ces formats et d'observer les différences significatives en termes de **taille de fichier** et de **performance** (temps d'encodage/décodage).

## 📋 Prérequis

* **Node.js** (version 14 ou supérieure recommandée)
* **npm** (gestionnaire de paquets Node)

## 🚀 Installation

1.  Clonez ce dépôt ou copiez les fichiers dans votre dossier de travail.
2.  Installez les dépendances nécessaires (`xml-js` et `protobufjs`) :

```bash
npm install
````

## 🛠️ Structure du Projet

  * `index.js` : Script principal contenant la logique de création des données, la sérialisation dans les 3 formats, et les mesures de performance.
  * `employee.proto` : Fichier de définition du schéma pour Protocol Buffers.
  * `data.json` : Sortie générée au format JSON.
  * `data.xml` : Sortie générée au format XML.
  * `data.proto` : Sortie générée au format binaire Protobuf.

## ⚙️ Utilisation

Pour exécuter le laboratoire et voir les résultats dans la console :


node index.js

# 📊 Résultats 
![alt text](https://github.com/AsmaElmourabite/TP17/blob/d81f9f2d91ab606316f24bc904a7944b3d002782/tp_17.jpg)
