graph TD
    A{Spatiotemporal Region 1} --->|rdf:type| B[Spatiotemporal Region BFO_0000011]
    A --->|temporally projects onto BFO_0000153| C{Temporal Region 1}
    A --->|spatially projects onto BFO_0000216| D{Spatial Region 1}
    C --->|rdf:type| E[Temporal Region BFO_0000008]
    D --->|rdf:type| F[Spatial Region BFO_0000006]

    classDef yellow fill:#EDF2AE
    classDef purple fill:#dbc9ef
    class B,E,F yellow
    class A,C,D purple