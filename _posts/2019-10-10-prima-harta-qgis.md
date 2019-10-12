---
title: "Prima hartă cu QGIS!"
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
Sunt foarte întâlnite situațiile când este nevoie să realizați o hartă pentru a fi imprimată sau publicată. Pentru acest workshop vom folosi ca date pachetul de start realizat de **Natural Earth** și ne vom concentra pe adăugarea elementelor care alcătuiesc layout-ul unei hărți (săgeata nordului, legendă, scară șamd) în **QGIS** și mai puțin spre deloc pe stilizarea straturilor.
# Scurtă descriere
Sunt foarte des întâlnite situațiile când este nevoie să realizați o hartă care să poată fi printată sau publicată. Acest workshop își propune să vă arate care sunt primii pași pentru a realiza o hartă în **QGIS** oferindu-vă în același timp un punct de plecare pentru realizarea unor produse cartografice mai avansate.
# Produsul final :)
La finalul workshop-ului vom obține această hartă.
![Demo](https://github.com/iungurianu/gis/blob/master/assets/images/prima-harta-cu-qgis/demo.png)

# Materiale necesare
Pentru a parcurge acest workshop este necesar să aveți instalat **QGIS** (de preferat versiunea 3) și să downloadați pachetul de start realizat de Natural Earth de aici

# Să începem!
1. Deschideți QGIS.
2. În QGIS Browser executați click dreapta pe opțiunea **GeoPackage**, alegeți **New connection** și navigați către locația unde ați salvat datele, alegeți **natural_earth_vector.gpkg**, click **Open**
3. În QGIS Browser, în submeniul GeoPackage observați că vă apare un nou container denumit: **natural_earth_vector.gpkg**. Puteți să îl deschideți executând dublu-click pentru a vizualiza ce date conține.
```
Puteți citi mai multe informații despre cum sunt 
structurate datele accesând site-ul 
![Natural Earth](https://www.naturalearthdata.com/features/)
```
