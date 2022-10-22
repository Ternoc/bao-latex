# Boîte à outils LaTeX

Vous trouverez dans ce dépôt des fichiers pour l'écriture sous LaTeX principalement dans le but de rapports de travaux pratiques.

## colorboxes.tex
Ce fichier présente des exemples d'utilisation du paquet [tcolorbox](https://ctan.org/pkg/tcolorbox) dans un contexte de documents mathématiques.

Les définitions des différents environnements sont dans le fichier [colorboxes.def.tex](colorboxes.def.tex) :

* equationEncadree : box "Equation importante" de couleur bleue, utilise le même compteur que les équations.
* customFig : box pour mettre en forme et inclure des figures
* resultat : box personnalisée de couleur rouge, avec un titre
* theroemCustom : box personnalisée de couleur verte, avec un titre

## fancyhdr.tex
Ce fichier présente des exemples d'utilisation du paquet [fancyhdr](https://ctan.org/pkg/fancyhdr).

## statuts.tex
Ce fichier présente un exemple de customisation des titres de section, sous-section, sous-sous-section pour réaliser un document de statuts par exemple pour une association.

Paquets utilisés : [titlesec](https://ctan.org/pkg/titlesec), [xcolor](https://ctan.org/pkg/xcolor) et [cleveref](https://ctan.org/pkg/cleveref)

```
\section{Exemple de titre}
```
Affichera TITRE I Exemple de titre

```
\subsection{Exemple d'article}
```
Affichera Article 1 Exemple d'article

Le numéro n'est pas réinitialisée à chaque titre.

```
\subsubsection{Exemple de section}
```
Affichera Section 1A Exemple de section

Le numéro contient le numéro de l'article en numéro arabe devant le numéro de la section en lettre.

Le numéro est réinitialisé à chaque article.
