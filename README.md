# RAMON-Retrieval-Advanced-Manufacturing-Ontology
This repository contains an industrial ontology for representing knowledge related to advanced manufacturing systems.

## Repository structure
```
.
├── ontology/
│   └── cfaa-industrial-ontology.ttl	# General industrial ontology
├── source/
│   └── Brochadora_AAS_IDTA32.ttl    # RDF representation of the AAS used as the source of knowledge
└── graph/
    └── brochadora-kg.ttl	# Machine-specific knowledge graph based on the ontology and the AAS
```

The ontology defines the general and reusable concepts and relationships, while the knowledge graph contains the specific instances and relationships corresponding to the broaching machine represented in the AAS.
