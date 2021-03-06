# C-TSM
Compound-Topology Shape Metrics Approach

## Description

Orthogonal layout extension for compound graphs for Cytoscape.js ([demo](https://rangmehal.pk/))

## Dependencies

 * Python ^3.7
 * Django ^3.2.6
 * networkx ^2.6.2
 * PuLP ^2.5.0
 * Matplotlib


## Usage instructions
After downloading or cloning the project, install the necessary packages.
Then go into the folder containing manage.py and run the following command:

`python manage.py runserver`

OR

`python3 mange.py runserver`

After running the above command, the html page can he opened [here](http://127.0.0.1:8000/).

The Cytoscape.js extension [file] (https://github.com/iVis-at-Bilkent/cytoscape.js-c-tsm/blob/main/communication/static/cytoscape-chola.js) is taken from the c-tsm folder.

## Limitations
* Can cause overlaps of non-child nodes with compound node
* Can cause node-edge overlaps if a node connected to compound node ends up inside that compound's boundary

## Future Work
* Extra compaction steps to remove extra spaces caused by compound cropping
