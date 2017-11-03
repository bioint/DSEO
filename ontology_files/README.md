# dot_visualizations
This directory contains the source files for generating the visualizations on [https://bioint.github.io/DSEO/visualizations.html](https://bioint.github.io/DSEO/visualizations.html).

To generate PDFs from the files, run:
    dot -Tpdf DOTFILE.dot > DOTFILE.pdf
To generate PNGs from the files, run:
    dot -Tpng DOTFILE.dot > DOTFILE.png

# dseo-current.ttl
This is the current Turtle representation of the DSEO. In initial designs,
we represented terms as instances of [SKOS](https://www.w3.org/2004/02/skos/) Concepts 
and connected them with skos:broderTransitive. Here, for the purposes of easier visualization
in BioPortal and Protégé, we represent each term as a class and connect them 
with *rdfs:subClassOf*.
