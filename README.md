# StackMap
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A data set of key tools used by 1000 highly successful companies.

`stacks.json` contains a list of the companies and what techologies they use and `graph.csv` gives the set of edges used to create the following *StackMap*:  

![StackMap](https://i.imgur.com/uf835D9.jpg)[https://i.imgur.com/uf835D9.jpg

#### What is going on in the landscape

The graph is created by setting each tool to be one node and two nodes are joined by an edge if they are used simultaniously by a company - edge weight corresponds to how often tools are used together.

Graph visualisation is done in Gephi 0.92. 

Node size corresponds to the amount of companies using a tool. If two tool are often used together then they will be closer together in the visualisation.