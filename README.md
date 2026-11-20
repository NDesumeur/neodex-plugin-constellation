# Orbites

Un jeu de rythme dans l'espace. Ta planète tourne autour de son étoile sur trois orbites, un tour toutes les deux mesures. Saute d'orbite pile sur le temps pour attraper les étoiles filantes et éviter les comètes. Joue les 1200 morceaux du plugin Rythme, ou ta propre musique.

*English version: [README.en.md](README.en.md)*

## Comment jouer

- **↑ ou J/K** : sauter vers l'orbite extérieure · **↓ ou F/D** : vers l'orbite intérieure. Un **clic** marche aussi : en haut de l'écran vers l'extérieur, en bas vers l'intérieur.
- Sur chaque note, une **étoile filante** attend sur l'orbite voisine, avec une flèche qui montre le sens du saut ; saute quand son **cercle se referme**.
- Une **comète** arrive sur ton orbite : rester, ou sauter dans le mauvais sens, c'est la prendre (la note est ratée).
- Une **traînée dorée** suit l'étoile : garde la touche jusqu'à son bout, sinon le combo casse.
- **Manette** : la croix haut ou bas, Y/B vers l'extérieur, A/X vers l'intérieur.

## Précision et points

Les notes sont jugées selon l'écart avec le bon moment : **Parfait** (environ ±45 ms), **Bien** (±90 ms), **OK** (±140 ms), sinon raté.

Les points d'une note augmentent de 1 % par note de combo, jusqu'au double à 100 notes de suite ; une note ratée remet le combo à zéro. À la fin, la précision donne une note : **S** à partir de 95 %, **A** à 90 %, **B** à 80 %, **C** à 70 %, **D** en dessous.

## Chansons et difficulté

L'onglet **Chansons** reprend les 1200 morceaux de Rythme, en quatre difficultés (Facile, Normal, Difficile, Expert). La difficulté de chaque niveau est calculée d'après ses notes (densité, passages chargés), de 1 à 10 étoiles.

## Mes musiques

Dans **Mes musiques**, crée un niveau à partir d'un **fichier audio** importé ou d'une musique de ta bibliothèque **NeoMusic** : le jeu trouve son tempo et ses temps forts et en fait un niveau, à la **difficulté** choisie (1 à 10 étoiles).

## Réglages

- **Volume** de la musique.
- **Son des clics** : le son joué à chaque note touchée, au choix parmi 10 (Doux, Clap, Bois, Grosse caisse, Cristal, Pop, Charleston, Caisse claire, Pluck, Tok) ou aucun. Perdre un combo de 10 ou plus joue un son « combo cassé ».
- **Décalage** (−300 à +300 ms) : il se règle tout seul après chaque partie selon ton retard ou ton avance moyens ; tu peux aussi le changer à la main.

## Données et synchronisation

Tes scores et notes par niveau et tes réglages sont enregistrés par NeoDex, sauvegardés et synchronisés entre tes PC si la synchro est activée.

## Installer

Dans NeoDex : **NeoStore → À découvrir → Orbites → Installer**.

Développer un plugin : voir le [SDK NeoDex](https://github.com/NDesumeur/neodex-sdk).
