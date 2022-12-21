---
title: "Networks - Part 2"
teaching: 60
exercises: 60
---
[**Download Chapter pdf**]()

[**Download Chapter notebook (ipynb)**]()

[<span style="color: rgb(255, 0, 0);">**Mandatory Lesson Feedback Survey**</span>](https://docs.google.com/forms/d/e/1FAIpQLSdr0capF7jloJhPH3Pki1B3LZoKOG16poOpuVJ7SL2LkwLHQA/viewform?pli=1)


::::::::::::::::::::::::::::::::::::: questions 

- 
-
-

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

-
-
-
::::::::::::::::::::::::::::::::::::::::::::::::


:::::::::::::::::: prereq 

## Prerequisites

- [Basic Python]()
- [Basic Matplotlib]()

::::::::::::::::::


## Example: Protein-protein interactions

Protein-protein interactions (PPIs) ([PLoS: Protein–Protein Interactions](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2891586/)) refer to specific and function physical contact between proteins in vivo. Interactions may be dependant on biological context, organism, definition of interaction, and many other factors. An example of some PPIs can be seen below.

![](fig/mazG.png)

PPIs may be visualised as a network, in order to give greater context to the protein interactions, and see how changes to one protein may affect another protein several steps removed. A PPI network can be modelled via a graph in which the nodes represent the proteins and the edges represent interactions; an edge from node A to node B indicates protein B interacts with protein A. The diagram above shows the PPI network centred around the protein $mazG$ in *Escherichia coli K12 MG1655*. This is part of a toxin-antitoxin system. These systems generally encode pairs of *toxin* and inhibitory *antitoxin* proteins, are transmitted by plasmids, and likely serve several biological functions including stress tolerance and genome stabilisation. $mazG$ regulates the type II toxin-antitoxin system shown in this network, where $mazF$ is the toxin and $mazE$ is the antitoxin. More details on the proteins in this network can be seen on STRING-DB ([STRING-DB: mazG in E. coli](https://version-11-0b.string-db.org/cgi/network?networkId=b6lw5pU2DeQm))

At the end of the example we are going to use Python to draw this PPI network, before this however, we shall begin with some small examples to familiarise you with the elements and properties of small graphs. 


## An Introduction to Networks

### What is a graph?

A graph is an object in mathematics for describing relationships between objects. An simple example of a visual representation of a graph is given below.

![](fig/simple_graph2.png)


This graph contains three objects or **nodes** or **vertices** and three links called **edges** or **arcs** between the nodes. Graphs can be used to represent networks.

For a formal definition of a graph see, e.g. the [Wikipedia entry](https://en.wikipedia.org/wiki/Graph_theory).

If the above graph represented a protein-protein interaction network then the nodes would represent three proteins and the edges represent interactions between them.

To add further proteins, you add new nodes to the network. To include further dependencies, you add edges.

We shall see below how we can build and modify such a network, and how to represent networks in Python.

::::::::::::::::::::::::::::::::::::: keypoints 

-
-
-

::::::::::::::::::::::::::::::::::::::::::::::::



[r-markdown]: https://rmarkdown.rstudio.com/
