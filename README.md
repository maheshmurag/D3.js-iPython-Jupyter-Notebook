###An example of a D3.js canvas running as an iFrame in an iPython (Jupyter) notebook.

The Process:   
1. Reads data from a JSON file   
2. Adds it to the standard D3.js nodes and links arrays   
3. Renders the data in a canvas.    
4. The second row in the iPython notebook renders this as an iFrame   
5. The third row, which calls function display(), renders this in the iPython notebook.
   
Ideas borrowed from:   
1. http://bl.ocks.org/mbostock/3180395    
2. https://github.com/skariel/IPython_d3_js_demo    


TODO:
Replace canvas with SVG for mouse interactivity.
