# Rapport du projet de bio-informatique

Rapport du projet de bio-informatique réalisé par [Aline
Goeminne](https://github.com/AlineGoeminne) et [Danny
Willems](https://github.com/dannywillems).

## Comment compiler

Un makefile est fourni pour simplifier la compilation des fichiers tex.

* **make**: compile le fichier et génère un pdf.
* **make clean**: supprime les fichiers générés pendant la compilation en pdf
  mais garde le pdf.
* **make fclean**: supprime tous les fichiers générés pendant la compilation et
  supprime pdf.
* **make zip**: compile, clean et créer un dossier zip avec le pdf généré, le
  Makefile et les sources.

## Structure du dépot

```
README.md            // Ce fichier
Makefile
src                  // Dossier contenant les fichiers tex
|--> rapport.tex     // Fichier tex principal.
```

## Dotmatchers

Liste des résultats du dotmatcher

### Simplifiée

* Cible1S
![Résultats dotmatcher Cible1S](res/cible1S.png)
* Cible1S-ic
![Résultats dotmatcher Cible1S-ic](res/cible1S-ic.png)
* Cible2S
![Résultats dotmatcher Cible2S](res/cible2S.png)
* Cible2S-ic
![Résultats dotmatcher Cible2S-ic](res/cible2S-ic.png)
* Cible3S
![Résultats dotmatcher Cible3S](res/cible3S.png)
* Cible3S-ic
![Résultats dotmatcher Cible3S-ic](res/cible3S-ic.png)

### "Normale"

* Cible1
![Résultats dotmatcher Cible1](res/cible1.png)
* Cible1-ic
![Résultats dotmatcher Cible1-ic](res/cible1-ic.png)
* Cible2
![Résultats dotmatcher Cible2](res/cible2.png)
* Cible2-ic
![Résultats dotmatcher Cible2-ic](res/cible2-ic.png)
* Cible4
![Résultats dotmatcher Cible4](res/cible4.png)
* Cible4-ic
![Résultats dotmatcher Cible4-ic](res/cible4-ic.png)
* Cible5
![Résultats dotmatcher Cible5](res/cible5.png)
* Cible5-ic
![Résultats dotmatcher Cible5-ic](res/cible5-ic.png)

## Todo

* [ ] Lister les autres essais qu'on a fait.
* [ ] Lister les complexités ?
* [ ] Quand backtrack, on prend quel jmax et quel imax ? Le plus à gauche ou le
  plus à droite ? Le plus en haut ou le plus en bas ?
