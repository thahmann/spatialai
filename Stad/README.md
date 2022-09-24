## An Ontology Design Pattern for Spatial and Temporal Aggregate Data (STAD)

The STAD Ontology Design Pattern models concepts required for defining spatial and temporally aggregated data in a precise manner. It is aimed at providing baselines for data integration decision-making and permitting provenance of aggregate quantities. 

#### Overview
The ontology describes four characteristics that we have identified as essential for capturing the semantics of spatial temporal aggregates: _spatial support (where)_, _temporal support (when and, more precisely, how long and how frequently)_, _base quantity (what)_, and _transformation method (how)_ based on whether a quantity is aggregated spatially, temporally or spatio-temporary. As seen in image gelow, only spatiotemporal aggregates require all four characteristics, while only temporally aggregated data requires no spatial support and only spatially aggregated data requires no temporal support.

![conceptual pattern](https://github.com/thahmann/spatialai/blob/master/Stad/images/STAD_conceptualpattern.png)

#### Example
To illustrate the use of the pattern, consider the encoding of a specific calculation of the summer mean temperature shown in the figure below. We will use this example to present how the four key characteristics of spatial and temporal aggregate data are formally captured.

![conceptual pattern](https://github.com/thahmann/spatialai/blob/master/Stad/images/STAD_usecase_1.png)

