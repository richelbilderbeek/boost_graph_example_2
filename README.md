# boost_graph_example_2: four human names and their relationships + plotting

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/boost_graph_example_2.svg?branch=master)](https://travis-ci.org/richelbilderbeek/boost_graph_example_2)

A [Boost.Graph example](https://github.com/richelbilderbeek/boost_graph_examples) that uses Graphviz.

It defines a graph of person names and their relationships. 
Then the graph is written to .dot file and plotted using KGraphViewer.

```
graph G {
0[label="Mr. A"];
1[label="Mrs. B"];
2[label="Dr. C"];
3[label="Prof. D"];
0--1 ;
1--2 ;
2--3 ;
0--3 ;
}
```