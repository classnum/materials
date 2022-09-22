---
layout: default
title: Outils et langages
nav_order: 3
---

<details open markdown="block">
  <summary>
    Outils et langages
  </summary>
  {: .text-delta .fs-4 }
- TOC
{:toc}
</details>

## Moteurs de recherche
* [DuckDuckGo](https://duckduckgo.com/)
* [Qwant](https://www.qwant.com/)

## Éditeur de texte : Visual Studio Code
* [Visual Studio Code](https://code.visualstudio.com/) est l’éditeur que nous utilisons ensemble, disponible pour tout système d’exploitation
    * [Documentation](https://code.visualstudio.com/docs)
    * Extensions à installer dans le logiciel
        * `Markdown All in One`
        * `markdownlint`
        * `Markdown Preview Enhanced`
        * `Rainbow CSV`
        * `Scholarly XML`
* Autres éditeurs gratuits
    * Nous utilisions auparavant [Atom](https://atom.io), qui deviendra bientôt [obsolète](https://github.blog/2022-06-08-sunsetting-atom/).
    * Mac : [Sublime Text](https://www.sublimetext.com/)
    * Linux : Gedit (installé par défaut)
    * Windows : [Notepad++](https://notepad-plus-plus.org/)

<!-- ## Éditeur de texte : Atom
* [Atom](https://atom.io) est l’éditeur que nous utilisons ensemble, disponible pour tout système d’exploitation
    * [Guide](https://flight-manual.atom.io/getting-started/sections/atom-basics/)
    * Packages à installer depuis les préférences d’Atom
        * `Language Markdown`
        * `Markdown Preview Plus`
        * `Linter Autocomplete Jing`
        * `TEI Framework`
    * Le package Tablr fournit une interface visuelle aux fichiers CSV : dans les préférences, sous « Install », rechercher le package sous le nom `mfripp/atom-tablr`.
    * À l’installation d’un package, si vous recevez un message d’erreur mentionnant le langage Java, contrôlez qu’il est installé sur votre machine : voici le [lien de téléchargement](https://www.oracle.com/java/technologies/javase-downloads.html) (installez la version « Standard Edition », Java SE, si vous n’avez pas besoin de la version « Standard Edition Development Kit », JDK, destinée aux développeurs et que certains logiciels nécessitent).
* Autres éditeurs gratuits
    * Mac : [Sublime Text](https://www.sublimetext.com/)
    * Linux : Gedit (installé par défaut)
    * Windows : [Notepad++](https://notepad-plus-plus.org/)
-->

## Markdown
* [Tutoriel d’introduction](https://commonmark.org/help/)
* [Markdown](https://daringfireball.net/projects/markdown/)
    * Le [bac à sable](https://daringfireball.net/projects/markdown/dingus) permet de faire des essais.
* [MultiMarkdown](https://fletcherpenney.net/multimarkdown/)
    * Le Multimarkdown est une extension du Markdown qui inclut des fonctions essentielles pour nous : notes, citations, marques de révision, tableaux, images, etc.
    * [MultiMarkdown Guide](https://rawgit.com/fletcher/human-markdown-reference/master/index.html)
* [CriticMarkup](http://criticmarkup.com/)
    * Le Multimarkdown inclut la syntaxe CriticMarkup pour ses fonctions de révision.
* [Sustainable Authorship in Plain Text](https://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) using Pandoc and Markdown (tutoriel)

## GitHub
* [GitHub](https://github.com/)
    * Sunoikisis Digital Classics, « Open Source software, command line and Git », 2020 : [présentation de Git](https://www.youtube.com/watch?v=1FDY28DRgso&amp;t=3177), puis [présentation de GitHub](https://www.youtube.com/watch?v=1FDY28DRgso&amp;t=3599)
    * Tutoriel [Hello World](https://guides.github.com/activities/hello-world/) : principes généraux et utilisation de GitHub sur le Web
    * [GitHub Desktop](https://desktop.github.com/) : interface graphique
* Entrepôt de données [Classnum sur GitHub](https://github.com/classnum)

## Terminal Unix
* Pour vous familiariser avec le terminal Unix (également appelé ligne de commande, *shell* et, en l’occurence, *Bash*), suivez ce tutoriel de la plateforme *Programming Historian* : [Introduction to the Bash Command Line](https://programminghistorian.org/lessons/intro-to-bash).
* Sous Windows et sous Mac ou Linux, les commandes varient légèrement. Voici une liste des commandes les plus courantes, extraite d’un [tableau plus complet](https://gist.github.com/carlessanagustin/266171818584b3880f72a625dfa2513b) :

|      Unix      |         Windows         |                                                                      Notes                                                                       |
|----------------|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `chown, chmod` | `attrib`                | Sets ownership on files and directories                                                                                                          |
| `cd`           | `cd`                    | On Windows, `cd` alone prints the current directory, but on Unix `cd` alone returns the user to his home directory.                              |
| `pwd`          | `cd`                    | On Windows, `cd` alone prints the current directory.                                                                                             |
| `clear`        | `cls`                   | Clear the terminal screen                                                                                                                        |
| `cp`           | `copy`                  |                                                                                                                                                  |
| `date`         | `datetime`              | Date on Unix prints the current date and time. Date and time on Windows print the date and time respectively, and prompt for a new date or time. |
| `rm`           | `del`                   | ¡ATTENTION!                                                                                                                                      |
| `rm -r`        | `deltree`               | ¡ATTENTION! Recursively deletes entire directory tree                                                                                            |
| `ls`           | `dir`                   | `dir` also works on some versions of Unix.                                                                                                       |
| `diff`         | `fc`                    |                                                                                                                                                  |
| `grep`         | `find`                  |                                                                                                                                                  |
| `man`          | `help`                  | `help` by itself prints all the commands                                                                                                         |
| `mkdir`        | `mkdir`                 |                                                                                                                                                  |
| `more, less`   | `more`                  |                                                                                                                                                  |
| `mv`           | `move`                  |                                                                                                                                                  |
| `shutdown -r`  | `Reboot`, `shutdown -r` |                                                                                                                                                  |
| `rmdir`        | `rmdir`                 | ¡ATTENTION!                                                                                                                                      |
| `rm -r`        | `rmdir /s`              | ¡ATTENTION! Windows has a y/n prompt. To get the prompt with Unix, use `rm -i`. The `i` means “interactive”.                                     |
| `shutdown -h`  | `shutdown -s`           | Also need `-f` option to Windows if logged in remotely                                                                                           |
| `sort`         | `sort`                  |                                                                                                                                                  |
| `cat`          | `type`                  |                                                                                                                                                  |

## Pandoc
* [Pandoc](https://pandoc.org) convertit les fichiers d’un format dans un autre.

## Regex
* Expressions rationnelles (ou régulières, d’où l’abréviation « regex »), pour réaliser requêtes et transformations avancées
* `?regex`
* Rappels très clairs et adaptés à RStudio
    * [Work with Strings Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/), page 2 (*cheat sheet* du package `stringr`, utile même si vous n’utilisez pas ce package)
    * [RegExCheatsheet](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf)
* [R et les expressions régulières](https://thinkr.fr/r-les-expressions-regulieres/)
* Exercices interactifs : [Regexone](https://regexone.com/)
* Apprendre et tester en ligne : [Regex101](https://regex101.com/)

## HTML
* Pour information
    * [HTML - Wikipedia (EN)](https://en.wikipedia.org/wiki/HTML), [HTML - Wikipedia (FR)](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language)
    * Les documents officiels (*specifications*) qui décrivent [HTML 4.01](https://www.w3.org/TR/html401/) et [HTML 5 (en cours d’élaboration)](https://html.spec.whatwg.org/). Sachez que le XHTML a été une étape d’évolution du HTML.
* Tutoriels
    * À propos du HTML dans les blogs WordPress, dont notre carnet : [Beginning HTML](https://wordpress.com/support/beginning-html/) et [Advanced HTML](https://wordpress.com/support/advanced-html/)
    * W3C : [HTML Tutorial](https://www.w3schools.com/html/) (en anglais)
    * Mozilla : [Apprendre le Web > HTML](https://developer.mozilla.org/fr/Apprendre/HTML) (chaque page peut être affichée dans diverses langues)
    * En français, sur OpenClassrooms : [Apprenez à créer votre site web](https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3) avec HTML5 et CSS3
    * Exemples plus ou moins spectaculaires de styles CSS différents : [CSS Zen Garden](http://www.csszengarden.com)

## TEI (et XML)
* [TEI Consortium](https://tei-c.org/)
    * [TEI Guidelines](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html) (site de référence)
    * Liste de discussion de la TEI : [TEI-L](https://listserv.brown.edu/archives/cgi-bin/wa?A0=TEI-L)
* [TEI by Example](https://teibyexample.org/TBE.htm) (tutoriel, exercices et exemples)
    * Module 0 : [Introduction to Text Encoding and the TEI](https://teibyexample.org/tutorials/TBED00v00.htm)
    * Module 7 : [Critical Editing](https://teibyexample.org/tutorials/TBED07v00.htm)
    * [TBE validation service](https://teibyexample.org/tools/TBEvalidator.htm)
* Marjorie Burghart et Elena Pierazzo, [Digital Scholarly Editions](https://teach.dariah.eu/course/view.php?id=32): Manuscripts, Texts and TEI Encoding (vidéos)
* Marjorie Burghart, [Éditer des sources historiques en ligne grâce à XML](http://mutec.huma-num.fr/?q=guides-Mutec) (guide)
* Marjorie Burghart, [TEI Critical Apparatus Toolbox](http://teicat.huma-num.fr/) (outil de visualisation)
    * Voir l’article [The TEI Critical Apparatus Toolbox](https://journals.openedition.org/jtei/1520): Empowering Textual Scholars through Display, Control, and Comparison Features
* Lou Burnard, [*What is the Text Encoding Initiative?*](https://books.openedition.org/oep/426), 2014 (en accès libre)
* [Guidelines of the Digital Latin Library](https://digitallatin.github.io/guidelines/LDLT-Guidelines.html) (conventions en cours de développement pour les apparats critiques, même complexes)
* Scripts XSLT de transformation du XML-TEI en d’autres formats
    * TEI Stylesheets : plateforme [OxGarage](https://oxgarage.tei-c.org/) et [scripts sur GitHub](https://github.com/TEIC/Stylesheets/)
    * [DLL Stylesheets](https://github.com/DigitalLatin/DLL-Stylesheets) (versions remaniées par l’équipe de la Digital Latin Library)

## Voyant Tools
* [Site canadien](https://voyant-tools.org/), [site français](https://voyant-tools.huma-num.fr/)
* Aurélien Berra, [Introduction à Voyant Tools](https://github.com/aurelberra/voyant_tools/blob/master/tutorial/voyant_tools_intro_fr.md)

<!-- ## AntConc
* [AntConc](http://www.laurenceanthony.net/software/antconc/)
* [Analyse de corpus avec AntConc](https://programminghistorian.org/fr/lecons/analyse-corpus-antconc) -->

## R et RStudio
* [R](https://cran.r-project.org/)
* [RStudio](https://www.rstudio.com/products/rstudio/)
* [RStudio cheatsheets](https://www.rstudio.com/resources/cheatsheets/)
    * Tour détaillé de l’environnement de travail de RStudio : [en anglais](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf) et [en français](https://github.com/rstudio/cheatsheets/raw/master/translations/french/rstudio-ide_fr.pdf)
    * [Base R](https://github.com/rstudio/cheatsheets/blob/main/base-r.pdf)
* Trouver des réponses, poser des questions
    * Copier un message d’erreur ou un nom de commande dans un moteur de recherche (à choisir, [DuckDuckGo](https://duckduckgo.com/) plutôt que Google) permet le plus souvent de mieux comprendre un problème assez vite.
    * Forum [StackOverflow](https://stackoverflow.com), recherche limitée aux [discussions concernant R](https://stackoverflow.com/questions/tagged/r)
    * [RSeek.org](https://rseek.org/) (moteur de recherche spécifique)
    * [The R-universe system](https://r-universe.dev/) (moteur de recherche spécifique)
    * Recommandations du package [Reprex](https://reprex.tidyverse.org/articles/reprex-dos-and-donts.html) – que je ne vous demande pas d’utiliser, mais qui fait le point et donne des liens sur la question du *minimal reproducible example* abordée dans la rubrique « Forum : quelques bonnes habitudes » du présent document
    * [R Debugging Bingo](https://docs.google.com/presentation/d/1iRUa51RQila_vRYdarFt7MhgH-emmKYQqylK0kgjr3Q/)
* Quelques références sur R
    * Types de données (*modes*) : numeric, integer, complex, character (and string of characters), factor, logical (boolean) + `NULL`, `NA`
    * Structures de données (*classes*) : vector, factor, matrix, array, list, data frame/tibble, time series
        * Garrett Grolemund, [R objects](https://rstudio-education.github.io/hopr/r-objects.html)
        * First Steps in R, [Data structure](http://venus.ifca.unican.es/Rintro/dataStruct.html)
    * [Initiation au langage et objets de R](https://www.math.univ-toulouse.fr/~besse/Wikistat/pdf/st-tutor2-R-init.pdf)
    * Kieran Healy, [How to read an R help page](https://socviz.co/appendix.html)
    * [R for Data Science](https://r4ds.had.co.nz) : [modèle d’un projet d’analyse de données](https://r4ds.had.co.nz/introduction.html)
* Packages du Tidyverse : [documentation](https://www.tidyverse.org/packages/)
    * Hadley Wickham, [*The tidyverse style guide*](https://style.tidyverse.org/)
* Représentation graphique avec ggplot2
    * [Site de référence](https://ggplot2.tidyverse.org/) du package ggplot2
    * Quelques tutoriels et ouvrages
        * Kieran Healy, [Data Visualization](https://socviz.co/) (version préliminaire en ligne de Healy Kieran, *Data Visualization: A Practical Introduction*, Princeton, Princeton University Press, 2019)
        * Cédric Scherer, [A Ggplot2 Tutorial for Beautiful Plotting in R](https://cedricscherer.netlify.app/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/)
        * Yannick Rochat, [Introduction à ggplot2](https://yrochat.github.io/ggplot2_tuto/ggplot2.nb.html)
        * Julien Barnier, [Visualiser avec ggplot2](https://juba.github.io/tidyverse/08-ggplot2.html)
        * Garrick Aden-Buie, A Gentle Guide to the Grammar of Graphics with ggplot2 ([présentation](https://pkg.garrickadenbuie.com/gentle-ggplot2/))
        * Isabella Benabaye, [ggplot2 Theme Elements Reference Sheet](https://isabella-b.com/blog/ggplot2-theme-elements-reference/)
    * [Shiny](https://shiny.rstudio.com/gallery/), interfaces dynamiques pour ggplot2
* RMarkdown
    * Reproducible Research and the Wonders of RMarkdown ([présentation](https://alycerussell.github.io/ReproducibleResearchOct2019/#1)), en particulier [What is this wizardry?!](https://alycerussell.github.io/ReproducibleResearchOct2019/#44) et [What is RMarkdown?](https://alycerussell.github.io/ReproducibleResearchOct2019/#46)

## LaTeX
* Pour produire des PDF avec Pandoc, notamment
* Pour installer LaTeX, suivre les [instructions du site de Pandoc](https://pandoc.org/installing.html)
* [(Xe)LaTeX appliqué aux sciences humaines](https://geekographie.maieul.net/95) (introduction pertinente et francophone)

## OCR : Tesseract
* [Tesseract](https://tesseract-ocr.github.io/tessdoc/)

## Open Refine
* [Open Refine](https://openrefine.org)
* [Cleaning Data with OpenRefine](https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine) (tutoriel)

## CLTK
* The Classical Language Toolkit (en Python) : [CLTK](http://cltk.org/)

## Stopwords
* [Principes](https://github.com/aurelberra/stopwords/blob/master/rationale.md) des listes utilisées

## Lemmatisation
* [Pyrrha](https://dh.chartes.psl.eu/pyrrha/), environnement de « post-correction » intégrant le service Web [Deucalion](https://dh.chartes.psl.eu/deucalion/)
* [LemmatizedAncientGreekXML](https://github.com/gcelano/LemmatizedAncientGreekXML), collection désormais ancienne de textes grecs de Perseus comprenant lemmatisation et analyse morphosyntaxique

## Stemmatologie
* [OpenStemmata](https://openstemmata.github.io/) (et entrepôt du [projet sur GitHub](https://github.com/OpenStemmata/))

## Travailler avec des images
* [Omeka](https://omeka.org/classic/) (exposition de métadonnées et de documents)
* [Tropy](https://tropy.org/) (gestion personnelle de collections d’images de recherche)
* IIIF, [International Image Interoperability Framework](https://iiif.io/)
    * Illustration de la mise en œuvre de ce protocole sur la [page API IIIF de récupération des images de Gallica](http://api.bnf.fr/api-iiif-de-recuperation-des-images-de-gallica)
