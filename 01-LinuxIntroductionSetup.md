---
title: |
  Command-line interfaces and tools \
  for biologists
author: Pierre Tocquin (ptocquin@uliege.be)
keywords: 'Linux, Command line, Shell, Scripting, Bioinformatics'
date: 2021
logo: FIGS/logoULiege.jpg
---

# Linux: installation et découverte du système d'exploitation.

## Pourquoi Linux ?

### Populaire dans le monde académique et pour les applications bioinformatiques.

Si on se réfère aux statistiques de popularité des systèmes d'exploitation, on peut légitimement se poser la question de l'intérêt de consacrer du temps et de l'énergie à apprendre à maitriser un système d'exploitation tel que Linux qui n'équipe que 2% des ordinateurs de bureaux en Europe \(Figure {@fig:statsOS}\).

![Statistiques d&apos;usage des syst&#xE8;mes d&apos;exploitation en Europe en 2020. Source: \[StatCounter.com\]\(https://gs.statcounter.com/os-market-share/desktop/europe\)](.gitbook/assets/StatCounter_EU_2020.jpg){\#fig:statsOS}

Ces chiffres sont évidemment le résultat d'une analyse menée pour un usage "grand public" \(il s'agit de données récoltées lors de la consultation de sites internet\). Or, lorsqu'on s'éloigne d'une utilisation domestique d'un ordinateur, l'usage spécifique qui en est fait dicte généralement de manière importante le choix du système d'exploitation. Ainsi, il est remarquable que, chez les "gamers", Microsoft Windows soit quasiment l'unique système utilisé \(96,5% en juin 2021. Source: [Steam](https://store.steampowered.com/hwsurvey/Steam-Hardware-Software-Survey-Welcome-to-Steam)\). A l'inverse, si on s'intéresse aux systèmes qui équipent les super-caculateurs utilisés pour le traitement de données, on constate que 100% des 500 plus grosses machines au niveau mondial tournent sous Linux \(Source: [top500.org](https://store.steampowered.com/hwsurvey/Steam-Hardware-Software-Survey-Welcome-to-Steam)\).

Comme nous ne sommes pas là pour jouer mais bien pour apprendre les bases de l'analyse de données biologiques, nous pourrions en rester là dans l'argumentation en faveur de Linux... Mais prenons néanmoins le temps d'évoquer quelques éléments concrêts qui explique cette égémonie de Linux dans le monde du _Data Science_.

## Un développement _finalement_ académique et ouvert.

Au delà du monopole de Linux sur les machines de calcul, ce système d'exploitation est, de par son histoire, le plus populaire chez les développeurs informatiques, en particulier dans le secteur académique. En effet, Linux a été développé à partir de 1991 en utilisant comme base un autre système d'exploitation simple et gratuit, Minix, lui-même dérivé de Unix. Unix est né à la fin des années \`60 en parallèle avec le langage C. Ses concepteurs, Ken Thompson et Dennis Ritchie ont le souhait de produire un système d'exploitation multi-utilisateurs et multi-tâches pouvant être installé sans trop de difficultés sur différents modèles de machines. Ces 2 développeurs travaillent à l'époque pour le Bell Labs de la société de télécommunication AT&T \(aujourd'hui Nokia Bell Labs\). A l'époque, pour des raisons légales, AT&T ne peut pas commercialiser Unix et décide donc de le diffuser notamment vers les universités avec une licence peu contraignante: cela va doper le développement de Unix. À cette époque, l'Université de Californie à Berkeley est l'un des plus important contributeur au développement d'une version open-source de Unix \(_Berkeley Software Distribution_ ou BSD\). Notez qu'un grand nombre des systèmes d'exploitations utilisés aujourd'hui, dont MacOS mais à l'exception notable de Microsoft Windows, sont issus de Unix. La généalogie complète \(et impressionante!\) de Unix peut être visualisée sur [https://www.levenez.com/unix/](https://www.levenez.com/unix/).

