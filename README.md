# MiniArith

Une petite bibliothèque de mathématiques discrètes.

## Objectifs

L'objectif de **MiniArith** et de fournir un catalogue de définitions et de théorèmes utiles et simple à utiliser dans le cadre de projets étudiants de niveau licence info.

## TODOS

1. redéfinition de la division euclidienne
   1. une définition plus simple à manipuler que la définition très primitive de Coq
   2. preuve d'équivalence avec la division entière de Coq
   3. théorèmes utiles de comparaison
2. Définition des ensembles (finis/dénombrables)
   1. Sous forme de prédicats caractéristiques `A -> bool` (décidable)
   2. Sous forme de prédicats caractéristiques `A -> Prop` (pas forcément décidable)
   3. Opérateurs ensemblistes et théorèmes associés
4. Théorèmes utiles sur les listes
   1. Principe d'induction inversé (ajout en fin de liste)
   2. Lemmes utiles sur `fold`, `map`, `filter`
5. Logique propositionnelle
   1. sémantique dans `bool`
   2. Définitions des valuations propres (listes <-> fonctions)
   3. conversions CNF, DNF, etc
   4. théorèmes classiques (lemme de substitution, équivalences usuelles)