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
1. Deschideți QGIS și folosind QGIS Browser navigați către locația unde ați salvat pachetul de start;
2. Extindeți folderul, localizați fișierul Natural_Earth_quick_start_for_QGIS_v3 și adăugați-l în QGIS executând dublu-click.

![Demo](https://github.com/iungurianu/gis/blob/master/assets/images/prima-harta-cu-qgis/add_project.png)

3. Observați că denumirile sunt în limba greacă. Acest proiect folosește variabile pentru a seta limba.
4. Mergeți la Project - Properties.
5. Alegeți tab-ul Variables, găsiți project_language, dați click în coloana Value și schimbați din name_el în name_en. Click ok.
6. Dați un refresh hărții.
7. Asigurati-vă că în panoul de straturi singurul grup bifat este  z5-1:18m.
7. Folosind instrumentele de navigare centrați și măriți harta pe zona Australiei.

## Crearea unui layout și adăugarea hărții
1. Mergeți la Project - New Print Layout
2. În fereastra de dialog introduceți un nume, dacă doriți sau puteți să lăsați necompletat, și dați OK.
3. În fereastra Print Layout, dați click pe butonul Zoom full pentru a afișa întregul extent al layout-ului.
4. Mergeți la Add Item - Add Map și trasați pe foaia albă un dreptunghi pentru a aduce în Layout ceea ce vizualizăm în QGIS.
5. Selectați chenarul hărții, iar în panoul din dreapta, în dreptul căsuței pentru Scara, dați click pe buton, alegeți opțiunea Edit, introduceți valoarea 2000000 și dați OK.
6. Ajustați dimensiunea chenarului hărții astfel încât toata Australia să fie vizibilă.

## Titlu
1. Mergeți la Add Item - Add Label și trasați un chenar acolo unde doriți să poziționați tilul.
2. În panoul din dreapta, la Item Properties, modificați textul. Introduceți de exemplu: Australia
3. Dați click pe butonul Font și alegeti 24 pentru size.
4. Ajustați, dacă este nevoie, dimensiunea chenarului pentru titlu astfel încât să fie vizibil tot textul.
## Legendă
## Scară grafică
## Săgeata nordului
## Autor
## Logo
## Export
