# Visualizations
The DSEO consists of six dimensions with hierarchical terms. 
Each dimension serves to answer a specific question about a data science learning resource.

In the original design of the DSEO, every term was an instance of a
[SKOS](https://www.w3.org/2004/02/skos/) Concept, and all concept instances were connected 
with the skos:broaderTransitive property. However, for the purposes of browsing on BioPortal, we created 
a version of DSEO that has a class/subclass structure. This is seen in the Turtle file found
on [Github](https://github.com/bioint/DSEO/blob/master/ontology_files/dseo-current.ttl) and [BioPortal](https://bioportal.bioontology.org/ontologies/DSEO).

In the visualizations below, each oval is a concept, 
and each edge is labeled with the original SKOS property. Regarding the color of the edges, 
magenta edges indicate that 
the broader node/concept can be used to tag resources, and black edges indicate that the 
broader node/concept should not be used to tag resources. This color coding thus exists to 
show which dimension names can and cannot be used as a tag.

## Data Science Process (7 concepts)
### What stages of the data science process will this resource help me with?
[![datasci]({{ "/assets/ontology-images/data_science_process.png" | absolute_url }})]({{ "/assets/ontology-images/data_science_process.png" | absolute_url }})

## Domain (83 concepts)
### What field of study does this resource focus on?
[![domain]({{ "/assets/ontology-images/domain.png" | absolute_url }})]({{ "/assets/ontology-images/domain.png" | absolute_url }})

## Datatype (18 concepts)
### What types of data are addressed in the resource?
[![datatype]({{ "/assets/ontology-images/datatype.png" | absolute_url }})]({{ "/assets/ontology-images/datatype.png" | absolute_url }})

## Programming Tool (14 concepts)
### What programming tool is used in or taught by this resource?
[![programming_tool]({{ "/assets/ontology-images/programming_tool.png" | absolute_url }})]({{ "/assets/ontology-images/programming_tool.png" | absolute_url }})

## Resource Format (2 concepts)
### How is this resource presented?
[![resource_format]({{ "/assets/ontology-images/resource_format.png" | absolute_url }})]({{ "/assets/ontology-images/resource_format.png" | absolute_url }})

## Resource Depth (2 concept)
### How advanced is this resource?
[![resource_format]({{ "/assets/ontology-images/resource_depth.png" | absolute_url }})]({{ "/assets/ontology-images/resource_depth.png" | absolute_url }})
