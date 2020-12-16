# example-data

This repository contains exemplary data for exploration and to enable further research in crossroads between historical fields of academia and digital scholarship. 

The `DHP_I_Administration` folder contains tabular lists of office titles that were jointly produced during the first in a series of DigitalHabsburgPlatform workshops, entitled "Administration" and concerned with the conceptual challenges of "offices" as role relations between persons and institutions. The workshop was held at Vienna University on Feb 13/14, 2020.

Several distinct datasets were created by workshop participants in a group effort, with the goal of collecting office and title labels as a baseline for further work:^[We consider these excerpts fair use in a research setting, acknowledging the original sources of the data points as lined out in this README.] 

- [DHP-I_Amtsbezeichnungen-Sammlung-Hof_Kaiser_Rudolfs_II.csv](DHP_I_Administration/DHP-I_Amtsbezeichnungen-Sammlung-Hof_Kaiser_Rudolfs_II.csv) contains a set of office titles drawn from  
    > Hausenblasová, Jaroslava: Der Hof Kaiser Rudolfs II. Eine Edition der Hofstaatsverzeichnisse 1576–1620   

- [DHP-I_Amtsbezeichnungen-Sammlung-Ministerratsprotokolle_Kabinettskanzlei.csv](DHP_I_Administration/DHP-I_Amtsbezeichnungen-Sammlung-Ministerratsprotokolle_Kabinettskanzlei.csv) draws from the joint efforts of the ‘Emperor’s Desk’ project <https://www.univie.ac.at/emperorsdesk/> with the temporally overlapping <https://mrp.oeaw.ac.at/> ‘Ministerratsprotokolle’ digital scholarly edition.  

- [DHP-I_Amtsbezeichnungen-Sammlung-MPR(APIS-Daten).csv](DHP_I_Administration/DHP-I_Amtsbezeichnungen-Sammlung-MPR(APIS-Daten).csv) is a CSV dump of titles and labels from the <https://mpr.acdh.oeaw.ac.at/> ‘modulare prosopographische registratur’ APIS entity store used – among other projects – for 19th century ministerial council data from the <https://mrp.oeaw.ac.at/> ‘Ministerratsprotokolle’ digital scholarly edition.

- [mpr.institutions.json](DHP_I_Administration/mpr.institutions.json) is related to the Ministerratsprotokolle edition as well, it holds the institutions so far recorded within the MPR instance, with about 1680 entries, including links to <https://alex.onb.ac.at> -- in JSON format.

- [DHP-I_Amtsbezeichnungen-Sammlung-Personenregister_VWGI_1_Funktionen.csv](DHP_I_Administration/DHP-I_Amtsbezeichnungen-Sammlung-Personenregister_VWGI_1_Funktionen.csv) contatins a carefully excerpted sizable list of distinct office titles (that has further been curated by removing interesting outliers such as ‘Tochter’). It stems from the index of the monumental  
    > Michael Hochedlinger, Petr Mat'a, Thomas Winkelbauer (eds.), *Verwaltungsgeschichte der Habsburgermonarchie in der Frühen Neuzeit, Band 1: Hof und Dynastie, Kaiser und Reich, Zentralverwaltungen, Kriegswesen und landesfürstliches Finanzwesen* (<https://www.vandenhoeck-ruprecht-verlage.com/themen-entdecken/geschichte/transnationaleglobalgeschichte/39510/verwaltungsgeschichte-der-habsburgermonarchie-in-der-fruehen-neuzeit>)  

These data cover a large variety of offices, with a lot of them overlapping between the different datasets. 

An additional challenge is posed by the fact that these lists merely deal with *labels* for offices, and only in few cases with well-defined offices. Hence, a single office may have various names/labels that are subject to change over time and depend (among other factors) on language or orthography. Likewise, one and the same label may have been used for different offices. 

Attempts to define the offices related to the labels listed here have been started using <https://www.w3.org/2004/02/skos/> already during the workshop, but remain subject to further research, and additional linking to existing thesauri and vocabularies. 

The team would like to thank all contributors of the workshop sessions. 

[![DOI](https://zenodo.org/badge/322104558.svg)](https://zenodo.org/badge/latestdoi/322104558)
