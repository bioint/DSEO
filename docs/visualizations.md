# Visualizations
The DSEO consists of six dimensions with hierarchical terms. 
Each dimension serves to answer a specific question about a data science learning resource.

In the original design of the DSEO, every term was an instance of a
[SKOS](https://www.w3.org/2004/02/skos/) concept, and all concept instances were connected 
with the broaderTransitive property. However, for the purposes of browsing on BioPortal, we created 
a version of DSEO that has a class/subclass structure. This is seen in the Turtle file found
on [Github](https://github.com/bioint/DSEO) and [BioPortal](https://bioportal.bioontology.org/ontologies/DSEO).

In the visualizations below, each oval is a concept, 
and each edge is labeled with the original SKOS property. Regarding the color of the edges, 
magenta edges indicate that 
the broader node/concept can be used to tag resources, and black edges indicate that the 
broader node/concept should not be used to tag resources. This color coding thus exists to 
show which dimension names can and cannot be used as a tag.

## Data Science Process (8 concepts)
### What stages of the data science process will this resource help me with?
[![datasci]({{ "/assets/data_science_process.png" | absolute_url }})]({{ "/assets/data_science_process.png" | absolute_url }})

## Domain (74 concepts)
### What field of study does this resource focus on?
[![domain]({{ "/assets/domain.png" | absolute_url }})]({{ "/assets/domain.png" | absolute_url }})

## Datatype (18 concepts)
### What types of data are addressed in the resource?
[![datatype]({{ "/assets/datatype.png" | absolute_url }})]({{ "/assets/datatype.png" | absolute_url }})

## Programming Tool (13 concepts)
### What programming tool is used in or taught by this resource?
[![programming_tool]({{ "/assets/programming_tool.png" | absolute_url }})]({{ "/assets/programming_tool.png" | absolute_url }})

## Resource Format (2 concepts)
### How is this resource presented?
[![resource_format]({{ "/assets/resource_format.png" | absolute_url }})]({{ "/assets/resource_format.png" | absolute_url }})

## Resource Depth (2 concept)
### How advanced is this resource?
[![resource_format]({{ "/assets/resource_depth.png" | absolute_url }})]({{ "/assets/resource_depth.png" | absolute_url }})
