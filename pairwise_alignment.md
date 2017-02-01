---
layout:     default
title:      Pairwise alignment
date:       2017-02-01
summary:    snp-hair-eye-color
categories: forensics
---

# Pairwise alignment

## De feiten tot nu toe...

- Lichaam man in haven van Antwerpen
- \> 10 dagen geleden overleden
- **NIEUW SPOOR: DNA-STALEN**

## Hoe kunnen we DNA-stalen gebruiken om iemands oog- en haarkleur te achterhalen

Rechercheur Beirnaert wilt graag een robotfoto opstellen en deze rondsturen in de hoop dat iemand het slachtoffer zal herkennen. Omdat het lichaam al zo lang in het water lag, zijn zijn uiterlijke kenmerken helaas zeer sterk aangetast: de ogen zijn onherkenbaar geworden en het haar is verkleurd door de afbraak van het pigment melanine.

Daarom heeft het autopsie lab enkele DNA-stalen van het slachtoffer geëxtraheerd en gesequeneerd om op basis hiervan zijn uiterlijke kenmerken te voorspellen. Dit noemen we *DNA fenotypering*.

## De genetica van oog- en haarkleur - SNP's en alignments

De oog- en haarkleur van mensen wordt bepaald door puntmutaties in een aantal genen (*HERC2, IRF4, MC1R, etc.*). Vergelijk de DNA-sequentie van het slachtoffer met een gekende referentiesequentie om te achterhalen welke mutaties (*single nucleotide polymorphisms* of SNP's) de man had in deze genen. Hiervoor maken we gebruik van *pairwise sequence alignment*, een algoritme om twee verschillende sequenties te vergelijken. 

[De sequenties van de genen kan je hier vinden (in FASTA formaat)...](https://biodatamining.github.io/BioCluedo/data/pairwise_alignment_data.zip)

[Klik hier om de pairwise alignment tool te openen...](https://www.ebi.ac.uk/Tools/psa/emboss_needle/nucleotide.html)

Zodra we alle relevante SNP's hebben opgespoord, kunnen we het fenotype van de man voorspellen met behulp van de volgende website:

[Klik hier om naar IrisPlex te gaan...](http://hirisplex.erasmusmc.nl/)
