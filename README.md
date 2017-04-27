PubViz
================


PubViz is a tool for interactive visualization of publication data. Usually, publications are presented in textual form with some sorting and searching capabilities. The aim of PubViz is to display structured publication data using a set of interactive visual representations working together. PubViz shows amounts of publications along a timeline, uses bar charts for different publication types, wordclouds to show co-authors as well as keywords, and finally a groupable list view. Allowing for interactive exploration with complex query funcionalities that are easily accessible are the main aims of this tool. PubViz provides powerful query functionality while using intuitive representations that are easy to grasp and add to a playful user experience.

Getting Started
---------------

PubViz uses BibTeX as source data format, which can be exported by all major reference management applications. PubViz can be integrated into your own website easily: no installation procedure is required - just download the package on GitHub, edit the HTML template, upload it together with your .bib file to a webserver, and you are done.

More information about the tool and its installation can be found [here](http://pubviz.fhstp.ac.at/#download). 

Credits
---------------

Created in the context of the project semester in media technology, [St. Poelten University of Applied Sciences](http://www.fhstp.ac.at), 2014-2015

Initial team members: Matthias FABI, Andrea HABERSON, San RASUL, Elisabeth SCHNAITT, Paul THEISEN

Further development: Alexander RIND, Niklas THÜR, Ewald WIESER

Project supervisor: [Wolfgang AIGNER](http://mc.fhstp.ac.at/people/wolfgang-aigner)

Used toolkits/external libraries
---------------

[D3.js (Data-Driven Documents)](http://d3js.org/) version 3.5.3

[zotero-bibtex-parse by Henrik Muehe](https://github.com/apcshields/zotero-bibtex-parse)

[jQuery](http://jquery.com/) version 1.9.1

Developed with
---------------

Windows 8.1

Mac OS X

Sublime 3

Coda 2.5

Settings
--------------

```
target : "#pubvis_container", //the node the pubViz visualization will be appended
filename : "file.bib", //the bibTeX filename used for the pubViz visualization
color: "#ffc200" //color name or hex value which will be used for highlighting
```

Citation
--------------
Rind, A., A. Haberson, K. Blumenstein, C. Niederer, M. Wagner, and W. Aigner, [PubViz: Lightweight Visual Presentation of Publication Data](http://phaidra.fhstp.ac.at/o:1933), Proc. Eurographics Conf. Visualization (EuroVis) -- Short Paper: EuroGraphics, forthcoming, 2017.
