# TP 1 - Outils de traitement de corpus

## Quelle type de tâche propose CoNLL 2003 ?

La tâche visée par le corpus CoNLL 2003 est l'identification automatique des entités nommées.

## Quel type de données y a-t-il dans CoNLL 2003 ?

CoNLL 2003 comprend deux jeux de données, un en anglais, un en allemand. Ces jeux comprennent un ensemble de phrases segmentés en tokens. Ces tokens sont préalablement annotés (par leur tag Part-of-Speech et leur catégorie d'entité nommée si elle existe).

Les données en anglais sont des aggrégations de dépêches de presse Reuters. Les données en allemand proviennent du ECI Multilingual Text Corpus. Pour le bien de la « compétition », le bloc de données a été découpé en un gros corpus d'entraînement et un plus petit corpus de test.

## A quel besoin répond CoNLL 2003 ?

CoNLL 2003 répond au besoin de développer des modèles efficaces d'identifier les entitées nommées dans des textes non structurés et non annotés.

## Quels types de modèles ont été entraînés sur CoNLL 2003 ?

L'article lié à la publication du dataset cite plusieurs méthodes. Les principaux sont :

* Maximum Entropy Model (avec et sans isolation)
* Apprentissage statistique
* Modèles de Markov Cachés (HMM)
* Modèles de Markov Conditionnels (CMM)
* Réseaux de neuronnes récurents

## Est un corpus monolingue ou multilingue ?

Le corpus est bilingue : anglais et allemand.
