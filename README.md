# Mini-Compilateur en Java

**Université A / Mira de Béjaia**  
**Département d’informatique – 3ème année Licence**  
**Module : Compilation – Octobre 2025**

## Objectif
Créer un mini-compilateur en Java avec analyseur lexical et syntaxique pour un mini-langage simplifié (C, Java, PHP, JavaScript ou Python).  
La grammaire est proposée par l’étudiant puis validée par l’enseignant.  
Le but est de comprendre les bases de la construction d’un compilateur.

---

## Déroulement

### 1. Définition des règles
Chaque langage doit inclure uniquement :  
- Déclaration de variables  
- Affectation (logique et arithmétique)  
- Comparaison  
- Incrémentation et décrémentation  
- Structures de contrôle : if/else, while, do/while, for, foreach ou switch/case  

### 2. Développement
- **Étape 1** : Analyse lexicale (reconnaissance des mots-clés)  
- **Étape 2** : Analyse syntaxique (descente récursive, LL(1), etc.)  
- **Étape 3** : Gestion des erreurs lexicales et syntaxiques  
- **Étape 4** : Création de l’exécutable `.jar`  

### 3. Suivi et rendu
- Utilisation de GitHub pour le suivi (commits réguliers)  
- Mini-rapport expliquant : grammaire choisie, analyseur lexical, analyseur syntaxique, structure du projet, cas de test

---

## Structure du projet

```text
Mini-Compilateur/
├─ App/
│   ├─ src/             # Code source Java
│   └─ bin/             # Fichiers compilés (optionnel)
├─ A2_BENZAID-Mohamed_Amine.jar   # Exécutable
├─ Rapport.pdf          # Rapport complet
└─ README.md            # Ce fichier