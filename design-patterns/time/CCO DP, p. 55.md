graph BT
    A{Process Beginning 1} --->|rdf:type| B[Process Beginning ont00000197]
    A --->|temporal part of BFO_0000139| C{Process 1}
    C --->|rdf:type| E[Process 
    BFO_0000015]
    D{Process Ending 1}--->|rdf:type| F[Process Ending ont00000083]
    D--->|temporal part of BFO_0000139| C

    classDef yellow fill:#ffe680
    classDef purple fill:#dbc9ef
    class B,E,F yellow
    class A,C,D purple