# Langages et Automates

Cette organisation contient les ressources et projets liés au cours **Langages et Automates** de Nantes Université.

---

## Ressources du module

### Cours magistral

- [Slides](https://LangagesEtAutomates.github.io/CM/LEA.pdf) : version PDF avec animations
- [Handout](https://LangagesEtAutomates.github.io/CM/LEA-handout.pdf) : version PDF sans animation

### Travaux dirigés

- [Livret de TD](https://LangagesEtAutomates.github.io/Exercises/lea-td.pdf) : livret de TD

### Travaux pratiques

- TP 1 : Introduction à JFlex
  - [Sujet](https://LangagesEtAutomates.github.io/Exercises/lea-tp1-lexer.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/LangagesEtAutomates/lea-tp2-lexer): code Java à compléter
- TP 2 : Introduction à CUP
  - [Sujet](https://LangagesEtAutomates.github.io/Exercises/lea-tp2-parser.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/LangagesEtAutomates/lea-tp3-parser): code Java à compléter
- TP 3 : Interpréteur pour le langage algorithmique
  - [Sujet](https://LangagesEtAutomates.github.io/Exercises/lea-tp3-interpreter.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/LangagesEtAutomates/lea-tp4-interpreter): code Java à compléter
- TP 4 : Analyse statique de programmes
  - [Sujet](https://LangagesEtAutomates.github.io/Exercises/lea-tp4-analyser.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/LangagesEtAutomates/lea-tp5-analyser): code Java à compléter
- TP 5 : Projet — Enregistrements
  - [Sujet](https://LangagesEtAutomates.github.io/Exercises/lea-tp5-project.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/LangagesEtAutomates/lea-tp6-project): code Java à compléter

---

## Description du module

Ce cours est destiné à des étudiants de L2 en Informatique ou Mathématiques, ainsi qu'à toute personne s'intéressant à la théorie des langages formels, aux automates et à la compilation.

Le responsable du module est Matthieu Perrin.

Les volumes horaires dédiés à ce cours à Nantes Université (séances de 1h20) sont les suivants :
- Cours magistraux : 13.33h
- Travaux dirigés : 18.67h
- Travaux pratiques : 8h

### Contenu

- Monoïde des mots
- Langages rationnels
  - Expressions régulières
  - Automate fini
  - Langage reconnu par un automate fini
  - Déterminisation et minimisation d'un automate fini
  - Lemme d’Arden
  - Lemme de l’Étoile
- Langages algébriques
  - Grammaire algébrique
  - Arbre de dérivation
  - Automates à pile
- Hiérarchie de Chomsky
  - Classification des grammaires
  - Algorithmes de reconnaissance pour les grammaires de type 1 et 2
- Analyse lexicale et syntaxique
  - TP de JFlex et CUP

### Résultats d'apprentissage

À la fin de ce cours, un étudiant doit être capable de :
- Utiliser les logiciels JFlex et CUP
- Écrire une expression rationnelle
- Résoudre un système d'équations linéaires à droite
- Déterminer si un mot donné est reconnu par un automate fini ou un automate à pile
- Déterminer la classe d'une grammaire formelle dans la hiérarchie de Chomsky
- Savoir si un mot est engendré par une grammaire rationnelle, algébrique ou contextuelle
- Minimaliser et déterminiser un automate fini
- Transformer une grammaire rationnelle en une expression rationnelle ou en un automate fini et inversement

### Bibliographie

- K. D. Cooper & L. Torczon. **Engineering a compiler** – 2nd Ed., Morgan Kaufmann 2013
- P. Wolper. **Introduction à la calculabilité** – 3rd Ed., Dunod 2006
- O. Carton. **Langages Formels – Calculabilité et complexité**, Vuibert 2008

---

## Cours lié

Ce cours a été conçu comme la première partie d'un cours sur les fondements de la calculabilité en informatique théorique.
Il est suivi par un cours de [Calculabilité et Complexité](https://github.com/CalculabiliteEtComplexite) en L3,
dédié aux machines de Turing, à la calculabilité et à la complexité. 

---

## Licence

Sauf mention contraire, les contenus de cette organisation sont distribués sous les licences suivantes :

- **Supports pédagogiques (LaTeX, transparents, exercices, PDF)** :  
  [Creative Commons Attribution - ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)
- **Code source Java (snippets, projets de TP)** :  
  [MIT License](https://opensource.org/licenses/MIT)

Les détails, ainsi que les mentions d'attribution, les licences des images et des données externes,
sont disponibles dans le fichier [LICENSE.md](https://github.com/LangagesEtAutomates/.github/blob/main/LICENSE.md).

