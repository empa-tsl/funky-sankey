# funky-sankey
Scripts for designing fancy flow diagrams using LaTeX and TikZ

This work is licensed under the terms CC BY-NC-SA
More information on the license: https://creativecommons.org/licenses/#licenses

The data in the examples is from the following publication:
Kawecki, D.; Nowack, B. Polymer-Specific Modeling of the Environmental Emissions of Seven Commodity Plastics As Macro- and Microplastics. Environ. Sci. Technol. 2019, 53 (16), 9664–9676.

The scripts Charts_MATERIAL.tex are scripts which can be compiled using your favourite LaTeX compiler. They will rely on the data in flow.txt which contains the width of the arrows to plot (to be calculated externally in your favourite material flow analysis software) and the labels to display on top.

Steps in the scripts Charts_MATERIAL.tex :
- first import the header.tex script,
- then import the file flow.txt
- then create a function to extract the appropriate columns of the file flow.txt
- then import the tikzpicture.tex script which does the design job.
- in a last step, a title is displayed on top.
