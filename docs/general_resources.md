---
layout: default
title: Ressources générales
nav_order: 2
---

<details open markdown="block">
  <summary>
    Ressources générales
  </summary>
  {: .text-delta .fs-4 }
- TOC
{:toc}
</details>

## Ressources du cours
* Carnet [Classiques et numériques](https://classnum.hypotheses.org/)
* Bibliothèque partagée sur [Zotero](https://www.zotero.org) : groupe [Classnum](https://www.zotero.org/groups/294880/classnum/library) (sur invitation)
* Entrepôt de données [Classnum sur GitHub](https://github.com/classnum)
    * Dont [HCHN · Matériaux](https://classnum.github.io/materials/), le présent site de ressources
* [Framapad](https://framapad.org/)
    * [Pad HN1](https://annuel.framapad.org/p/hn1)
    <!-- * [Pad HN3](https://annuel.framapad.org/p/hn3) -->
* [Dropbox](https://www.dropbox.com/)
<!-- * [HN1 : questionnaire de début de S1]() @todo -->

## Forum : quelques bonnes habitudes
* Si vous écrivez vos messages sur le forum en Markdown, comme je vous le suggère (regardez les préférences de votre compte sur CEL), utilisez lorsque c’est utile des apostrophes inversées pour baliser le code :

Ceci est une `expression` affichée comme du code au sein d’un texte (*inline*), car notée ainsi : \`expression\`.

```
Ceci est un paragraphe de code (affiché comme *blockquote*),
```

car précédé et suivi d’une ligne contenant trois *backticks* :

\`\`\`
Ceci est un paragraphe de code (affiché comme *blockquote*),
\`\`\`

* Cependant, dès qu’il s’agit d’une citation un peu longue (d’un extrait d’encodage en HN1 ou de code en HN3), partagez un fichier de code : le texte du forum n’est pas exécutable et ne dit rien de votre environnement de travail.
* Or, le but d’une demande d’aide est d’isoler le problème en le rendant reproductible. La plupart du temps, cela implique de :
    * mentionner votre système et sa configuration – dans le cadre de nos cours, cela revient avant tout à indiquer votre système d’exploitation et sa version
    * préciser ce que vous essayez de faire
    * fournir un *minimal working example* ou [*minimal reproducible example*](https://stackoverflow.com/help/minimal-reproducible-example) – et vous constaterez qu’en réduisant le problème aux données pertinentes, et en l’expliquant, il arrive fréquemment qu’on en trouve la solution
* Des captures d’écran valent souvent plus qu’un long discours.
* Des liens sont généralement utiles. Les URL citées doivent être actives pour éviter les copier-coller à vos lecteurs.
* Lorsque vous avez réussi à résoudre votre problème, indiquez brièvement la solution sur le forum : toute personne qui vous a répondu sera intéressée et d’autres personnes peuvent à l’avenir rencontrer le même problème et trouver ainsi une solution.

## Quelques noms de symboles utiles

| Symbole |            Nom en français · *Name in English*             |
|---------|------------------------------------------------------------|
| [ ]     | crochets · *square brackets*                               |
| { }     | accolades · *curly braces*, *curly brackets*               |
| < >     | chevrons, crochets obliques · *angle brackets*, *chevrons* |
| \|      | barre droite · *pipe*                                      |
| /       | barre oblique · *slash*, *forward slash*                   |
| \       | barre oblique inversée · *antislash*, *back slash*         |
| _       | tiret bas · *underscore*                                   |
| `       | apostrophe inversée · *backtick*, *backquote*              |
| #       | croisillon · *octothorpe*, *hashtag*                       |

## Nommer un fichier ou un objet

* Éviter de faire figurer dans un nom de fichier ou de dossier des espaces, des caractères accentués, voire des majuscules.
* Un bon nom de fichier est distinct, et même unique. S’il doit être partagé, il identifie la personne qui l’a créé et, au besoin, mentionne un numéro de version.
* Parmi les diverses conventions possibles, je recommande l’usage du *snake_case* pour nos fichiers partagés et, en M2, pour les objets créés dans R :
    * `i_use_snake_case.txt`
    * `otherPeopleUseCamelCase.txt`
    * `some.people.use.periods.txt`
    * `And_aFew.People_RENOUNCEconvention.txt`

## Écrire grec en Unicode
* Écrire en grec ancien (grec polytonique) avec un clavier Unicode
    * [Page ENS](https://antiquite.ens.psl.eu/ressources/outils-logiciels/article/pilotes-de-clavier-unicode)
    * Autre possibilité : [Windows](https://michaellanglois.fr/fr/it/greek-with-french-keyboard-12-windows_grec-avec-clavier-francais-12-windows), [Mac](https://michaellanglois.fr/fr/it/clavier-grec-azerty-1-2-mac), [Linux](https://gitlab.com/outils-pour-le-grec/clavier-grec-ancien-azerty)
* [Learn to Type Polytonic Greek in 30 Short Chapters](https://greektyping.com/)

## Polices de caractères
* Utiliser des polices de caractères Unicode adaptées au grec polytonique et au latin étendu
* [Libertinus Serif](https://fontlibrary.org/en/font/libertinus-serif) (ou Linux Libertine O)
* [Gentium Plus](https://fontlibrary.org/en/font/gentium-plus)
* [GFS Didot](https://fontlibrary.org/en/font/gfs-didot)
* [GFS Elpis](https://fontlibrary.org/en/font/gfs-elpis)
* Times (plutôt que Times New Roman)
* Palatino Linotype
* [Asea](https://fontlibrary.org/en/font/asea-textfonts)
* [Lato](https://fontlibrary.org/en/font/lato) (sans empattements, *sans serif*)
* Bonus typographique : [Sacrés caractères !](https://www.franceculture.fr/litterature/sacres-caracteres-une-webserie-de-12-films-courts-sur-des-polices-qui-ont-du-caractere), websérie de 12 films courts sur des polices de caractères historiquement importantes

## Dictionnaires
* Pour consulter les dictionnaires usuels (Liddel-Scott-Jones, Bailly, Gaffiot) sous un format numérique, je vous recommande la plateforme [Logeion](https://logeion.uchicago.edu/).
* Autres interfaces disponibles : [Bailly](https://bailly.app/), [Gaffiot](https://gaffiot.fr/)
* À propos de la numérisation des dictionnaires français : [Gaffiot 2016](http://gerardgreco.free.fr/spip.php?article43) et [Bailly 2020](http://gerardgreco.free.fr/spip.php?article52)

## Digital Classics : sites d’information
* [Stoa Consortium](https://www.stoa.org/)
* [Digital Classicist](https://wiki.digitalclassicist.org/)

## Bibliographie, dont Zotero
* [Zotero](https://www.zotero.org/)
    * Un très complet [tutoriel](https://www.boiteaoutils.info/2012/06/introduction-zotero-30-nouveau-tutoriel/) (également accessible [ici](https://issuu.com/emilienruiz/docs/zotero_19-06-2012))
    * [Les styles de citation](https://www.zotero.org/support/fr/styles)
        * [Citation Styles Library](https://citationstyles.org/)
            * CSL [specifications](https://docs.citationstyles.org/en/stable/specification.html)
        * [Zotero Style Repository](https://www.zotero.org/styles)        
            * styles français : cherchez sur la page le mot « French »
            * voir aussi [csl-france](https://trello.com/b/ACMPVFQf/csl-france)
    * Groupes Zotero
        * [Doing Digital Humanities](https://www.zotero.org/groups/doing_digital_humanities_-_a_dariah_bibliography) - A DARIAH Bibliography
        * [Digital Classics](https://www.zotero.org/groups/digitalclassics)
* [WorldCat](https://www.worldcat.org/)
* [Catalogue collectif de France](https://ccfr.bnf.fr/)
* [Google Scholar](https://scholar.google.com/)
* [L’Année philologique](https://fr.wikipedia.org/wiki/L’Ann%C3%A9e_philologique) (à consulter par le portail de la BU)
* Base de données bibliographiques [CIRIS](https://ciris.huma-num.fr/)
* [The Perseus Catalog](https://catalog.perseus.org/)
* [Ancient World Open Bibliographies](https://ancientbiblio.wordpress.com/)
* [Classical Works Knowledge Base](https://www.cwkb.org)
* Manuscrits
    * Pour le grec, voir [Pinakes](http://pinakes.irht.cnrs.fr/) : catalogue des manuscrits grecs et liens vers les versions numérisées par les bibliothèques
    * Pour le latin, voir le portail du projet [Biblissima](https://portail.biblissima.fr/fr/bbma.view?datesspan_max=2000&datesspan_min=5&sliderDateleft=5&sliderDateright=1500&facet%3Aetype-facet=Manuscript&facet%3Adatesspan=5-1500) et directement les sites des bibliothèques
    * Quelques sites de bibliothèques contenant de riches collections numérisées
        * Paris, Bibliothèque nationale de France : [Gallica](https://gallica.bnf.fr/) et ses [manuscrits latins](https://gallica.bnf.fr/services/engine/search/sru?operation=searchRetrieve&query=(dc.language%20all%20"lat")%20and%20(dc.type%20all%20"manuscrit")%20and%20(gallicapublication_date<="1500"))
        * France, Bibliothèque virtuelle des manuscrits médiévaux ([BVMM](http://bvmm.irht.cnrs.fr/))
        * Londres, [British Library](https://www.bl.uk/collection-guides/classical-latin-manuscripts#)
        * Oxford, [Bodleian Library](https://digital.bodleian.ox.ac.uk/)
        * Florence, [Biblioteca Medicea Laurenziana](http://mss.bmlonline.it/)
        * Rome, [Biblioteca Vaticana](https://digi.vatlib.it/mss/)
        * [Bibliothèque de Heidelberg](https://www.ub.uni-heidelberg.de/helios/digi/handschriften.html)
    * [Papyri.info](https://papyri.info/), moteur de recherche papyrologique
* Publications scientifiques en ligne
    * [OpenEdition Journals](https://journals.openedition.org/)
    * [OpenEdition Books](https://books.openedition.org/)
    * [Cairn](https://www.cairn.info/)
    * [Persée](https://www.persee.fr/)
    * [Érudit](https://www.erudit.org/)
* Revues spécialisées
    * [*Humanités numériques*](https://journals.openedition.org/revuehn/)
    * [*Digital Scholarship in the Humanities*](https://academic.oup.com/dsh)
    * [*Digital Humanities Quarterly*](http://www.digitalhumanities.org/dhq/)
    * [*Variants*](https://journals.openedition.org/variants/)
* Comptes rendus
    * [Bryn Mawr Classical Review](https://bmcr.brynmawr.edu/)
    * [RIDE](https://ride.i-d-e.de/). A review journal for digital editions and resources
    * Society for Classical Studies : [digital projects reviews](https://classicalstudies.org/blogs/reviews)

## Bibliothèques en ligne
* Grec et latin
    * [Perseus Digital Library](https://www.perseus.tufts.edu/hopper/)
        * À consulter de préférence dans l’interface plus récente [Scaife Viewer](https://scaife.perseus.org/) lorsque les textes y sont disponibles
        * Entrepôts de données du projet Perseus : [bibliothèque grecque](https://github.com/PerseusDL/canonical-greekLit) et [bibliothèque latine](https://github.com/PerseusDL/canonical-latinLit)
        * Source complémentaire utilisée : [First Thousand Years of Greek](https://opengreekandlatin.github.io/First1KGreek/)
    * [Poesia latina](http://www.poesialatina.it/) (grec et latin, malgré le nom du site, avec des analyses métriques)
    * [Diogenes](https://d.iogen.es) (interface pour le TLG et le PHI, versions Desktop et Web, voir [Diogenes: a brief how to guide](https://youtube.com/watch?v=o51315nW5f4))
* Grec
    * [TLG](https://stephanus.tlg.uci.edu/) (sur abonnement : à consulter à partir du [portail de la BU](http://bu.parisnanterre.fr/))
* Latin
    * [PHI Classical Latin Texts](https://latin.packhum.org)
    * [Bibliotheca Augustana](https://www.hs-augsburg.de/~harsch/augustana.html)
    * [Corpus Corporum](https://www.mlat.uzh.ch/)
    * [Digital library of late-antique latin texts](https://digiliblt.uniupo.it/)
* Autres langues
    * [Wikisource](https://wikisource.org/)
    * [Project Gutenberg](https://www.gutenberg.org/)

## Vocabulaire grec et latin
* Dickinson College Commentaries, [Core Vocabulary](https://dcc.dickinson.edu/vocab/core-vocabulary) (listes des mots les plus fréquents en latin et en grec ancien)

## Prosopographie
* [Standards for Networking Ancient Prosopographies](https://snapdrgn.net/). Data and Relations in Greco-Roman Names

## Données spatiales et SIG
* Projets liés à l'analyse des données spatiales, notamment aux systèmes d’information géographique (SIG)
* [Rome Reborn](https://www.romereborn.org/)
* [Orbis](https://orbis.stanford.edu)
* [Projet Bretez](https://sites.google.com/site/louisbretez/home)
* [Virtual St Paul’s Cathedral Project](https://vpcp.chass.ncsu.edu/)
* [Pelagios](https://pelagios.org/) et [Recogito](https://recogito.pelagios.org/)
* [Pleiades](https://pleiades.stoa.org/)
* [Google Ancient Places](https://googleancientplaces.wordpress.com/about/)
* [Hestia](https://hestia.open.ac.uk/)

## Droit et licences
* Licences [Creative Commons](https://creativecommons.org/licenses/)
* Peter Suber, [*Open Access*](https://mitpress.mit.edu/books/open-access), 2012
* Calimaq [Lionel Maurel], [S.I.Lex](https://scinfolex.com/). Carnet de veille et de réflexion d’un juriste et bibliothécaire
* [*The Internet’s Own Boy: The Story of Aaron Swartz*](https://amara.org/fr/videos/5Mo4oAj1bxOb/info/the-internets-own-boy-the-story-of-aaron-swartz/), 2014
* [*Paywall: The Business of Scholarship*](https://paywallthemovie.com/paywall) (film documentaire), 2018

## Histoire et géopolitique de l’informatique
* [A History of the Internet and Computing in 71 Seconds](https://www.youtube.com/watch?v=QCw8f3-cIzU)
* Computer History Museum, [Revolution. The First 2000 Years of Computing](https://www.computerhistory.org/revolution/)
* [How the Internet works](https://arstechnica.com/information-technology/2016/05/how-the-internet-works-submarine-cables-data-centres-last-mile/)
* [Web des données](https://fr.wikipedia.org/wiki/Web_des_données)
    * [Linking Open Data cloud diagram](https://lod-cloud.net/)

## Méthodes d’apprentissage automatique
* Vasily Zubarev, [Machine Learning for Everyone](https://vas3k.com/blog/machine_learning/)
* Stephanie Yee et Tony Chu, [A visual introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
