# Methods
We designed the DSEO using top-down and bottom-up methods. The terms of the DSEO are 
intended to be descriptors (i.e. tags) for every resource in ERuDIte. Consequently, the 
ontology is designed with automatic assignment in mind.

We expect learners to use DSEO terms to help them find the resources they need for the
data science problems they are trying to solve. Thus, we wanted the terms in DSEO to allow
learners to find resources relevant to where they are in the data analysis life cycle, what
field they are applying data science to, what datatypes they are working with, what
programming tools they prefer, what modality they want to use to learn, and 
what level of difficulty is appropriate for them.

Early in the development process, we looked at MOOC specializations and degree programs to
extract key terms that we wanted to include in the vocabulary. We then started to collect resources
to add to ERuDIte. From this initial collection, we extracted noun phrases from the resources'
metadata and then de-duplicated and cross-referenced the phrases with the collection of terms we
defined manually. This led to the first version of the DSEO. 

As we continued to collect more resources, we used topic models built from
resources' metadata to look for any gaps in the ontology. We also referred to the
[F1000Prime Faculty Categories](https://f1000.com/prime/thefaculty/biology) to fill in
gaps in biomedicine, which was the initial target community for the online learning platform.

This led to the creation of DSEO's six dimensions:
1. Data Science Process
2. Domain
3. Datatype
4. Programming Tool
5. Resource Format
6. Resource Depth

A concept can only belong to one dimension, but a resource can be tagged with multiple 
concepts within and across dimensions. Also, the concepts are hierarchical and can have 
multiple parents. Thus, resources tagged with a child concept are also implicitly tagged 
with any parents, grandparents, etc.

See [Visualizations]({{ "/visualizations.html" | absolute_url }}) for more information 
on each dimension and the terms in each.

We discussed DSEO and the automatic assignment procedure along with the methods involved
in building ERuDIte at the [BigScholar workshop at WWW 2017](https://dl.acm.org/citation.cfm?id=3053060).