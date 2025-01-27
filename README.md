## Abstractions on BioPAX graphs

Goal: generate contextual views on BioPAX knowledge graphs and integrate views in a multiplex network

Views to generate : 
- Protein-centered view (abstraction based on SIF rules)
- Reaction-centered view
- Metabolite-centered view

Pathway test : R-HSA-2173789 ("TGF-beta receptor signaling activates SMADs")

/home/cbeust/Softwares/JenaFuseki/apache-jena-fuseki-4.9.0/fuseki-server --file TestExampleData/R-HSA-2173789_level3.owl --file TestExampleData/biopax-level3.owl /ractome_tgf_smads
