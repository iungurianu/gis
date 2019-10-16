---
title: "Crează prima hartă cu QGIS!"
date: 2019-10-11T10:57:30-04:00
categories:
  - workshop
tags:
  - QGIS
  - gis
  - hartă
  - cartografie
toc: true
---
Nivel de complexitate: **Începător**

# Prezentare generală
Sunt foarte întâlnite situațiile când este nevoie să realizați o hartă pentru a fi imprimată sau publicată. Pornind de la pachetul de start realizat de **Natural Earth** vom explora cum putem crea și exporta o hartă în **QGIS** care să conțină elemente componente specifice (legendă, săgeata nordului, scară șamd).

# Produsul final :)
La finalul workshop-ului vom obține această hartă.
![Demo](https://github.com/iungurianu/gis/blob/master/assets/images/prima-harta-cu-qgis/demo.png)

# Materiale necesare
Pentru a parcurge acest workshop este necesar să aveți instalat **QGIS** (de preferat versiunea 3) și să downloadați pachetul de start realizat de Natural Earth de aici

# Crearea hărții
## Adăugarea datelor
1. Deschideți QGIS.
2. În QGIS Browser adăugați la Favorite locația unde ați salvat pachetul de start
3. Deschideți folderul și adăugați versiunea pentru QGIS 3.
4. Pachetul de start de la Natural Earth este deja stilizat și conceput pentru diferite niveluri de zoom
5. În panoul de straturi bifați grupul corespunzator nivelului 2 de zoom
2. În QGIS Browser executați click dreapta pe opțiunea **GeoPackage**, alegeți **New connection** și navigați către locația unde ați salvat datele, alegeți **natural_earth_vector.gpkg**, click **Open**
3. În QGIS Browser, în submeniul GeoPackage observați că vă apare un nou container denumit: **natural_earth_vector.gpkg**. Puteți să îl deschideți executând dublu-click pentru a vizualiza ce date conține.


## Crearea unui layout
Layout este instrumentul din QGIS unde putem să customizăm o hartă și să adăugăm elemente componente specifice.
1. În meniul principal al QGIS mergeți la Project - New Print Layout
2. Scrieți un nume, de exemplu prima harta, și dați OK. Observați că se deschide o fereastră nouă. În partea de sus sunt butoane de zoom, de export, în partea dreapta veți găsi butoane pentru adăugarea unei hărți, a unei legende, a scării etc, în timp ce în partea dreapta veți găsi opțiuni pentru customizarea elementelor adăugate și selectate din layout.

Înainte de a adaugă harta să facem niște setări, cum ar fi dimensiunea paginii sau orientarea acesteia
1. În orice spațiul alb al foii executați click dreapta și alegeți Page properties
2. În partea dreaptă se activează un panou, iar în tab-ul Item properties puteti alege la Size din dimensiunile predefinite (A4, A3 etc) sau puteți introduce dimensiunile dvs. custom. Tot de aici puteți seta orientarea paginii și o culoare pentru background.

Adaugarea hărții
3. Localizați în partea stângă butonul Add map și prin drag and drop trasați un dreptunghi pe foaia albă
## Titlu
## Legendă
## Scară grafică
## Săgeata nordului
## Autor
## Logo
## Export
