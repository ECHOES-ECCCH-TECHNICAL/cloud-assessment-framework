# Kg Tools

Knowledge graph and data-oriented tools.

## Summary

- **SHACL Engines (Apache Jena SHACL)** — Validate RDF data against SHACL shapes enforcing structural and logical constraints.
- **SHACL Engines (pySHACL)** — Python-based SHACL validator for RDF graphs.
- **ShEx (Shape Expressions) Validators (ShEx.js)** — Validates RDF data against Shape Expressions schemas, especially suited for entity-centric datasets.
- **Openllet Reasoner** — OWL 2 DL reasoner for ontology consistency checking and inference.
- **RDFUnit** — Rule-based validation framework using SPARQL test patterns to detect structural issues and missing links.
- **Schematron** — Rule-based validation language used to enforce standard compliance and structural rules.
- **Metadata Quality Toolkit** — Computes metrics for field completeness and textual readability in metadata records.
- **KGTK (Knowledge Graph Toolkit)** — Toolkit for profiling, connectivity analysis, and exploration of large knowledge graphs.
- **Silk Link Discovery Framework** — Discovers and validates links across datasets using similarity rules and can detect duplicates.
- **LODsyndesis** — Indexes links across many knowledge graphs and computes sameAs closures to detect duplicates.
- **RDFind** — Detects structural dependencies and patterns in RDF data to identify missing or expected properties.
- **F-UJI** — Automatically evaluates FAIR indicators related to accessibility and interoperability.
- **FAIR-Checker** — Validates FAIR compliance directly on RDF metadata using SPARQL and SHACL.
- **FAIR Evaluator** — Executes machine-readable FAIR maturity indicator tests using web and API interrogation.
- **FAIR-Shake** — Combines automated FAIR checks with human-evaluated rubrics.
- **TripleCheckMate** — Crowdsourcing platform for human validation of RDF triples selected automatically.
- **KGEval** — Uses statistical inference to minimize human effort in validating factual correctness of triples.
- **Manual Metadata Quality Checklists** — Human-curated checklists used by institutions to assess qualitative metadata aspects.
- **SHACL Playground** — A constraint validator for the Shapes Constraint Language, written in JavaScript.

## SHACL Engines (Apache Jena SHACL)

- **ID:** `KG_TOOLS_SHACL_ENGINES_APACHE`
- **Dimensions covered:** Consistency; Format.
- **Description:** Validate RDF data against SHACL shapes enforcing structural and logical constraints.
- **Link:** https://jena.apache.org/documentation/shacl/

### Additional properties

- **Quality Category:** Intrinsic; Representational.
- **Automation:** automatic.

## SHACL Engines (pySHACL)

- **ID:** `KG_TOOLS_SHACL_ENGINES_PYSHACL`
- **Dimensions covered:** Consistency; Format.
- **Description:** Python-based SHACL validator for RDF graphs.
- **Link:** https://github.com/RDFLib/pySHACL

### Additional properties

- **Quality Category:** Intrinsic; Representational.
- **Automation:** automatic.

## ShEx (Shape Expressions) Validators (ShEx.js)

- **ID:** `KG_TOOLS_SHEX_SHAPE_EXPRESSIONS`
- **Dimensions covered:** Consistency; Format.
- **Description:** Validates RDF data against Shape Expressions schemas, especially suited for entity-centric datasets.
- **Link:** https://github.com/shexjs/shex.js

### Additional properties

- **Quality Category:** Intrinsic; Representational.
- **Automation:** automatic.

## Openllet Reasoner

- **ID:** `KG_TOOLS_OPENLLET_REASONER`
- **Dimensions covered:** Consistency.
- **Description:** OWL 2 DL reasoner for ontology consistency checking and inference.
- **Link:** https://github.com/Galigator/openllet

### Additional properties

- **Quality Category:** Intrinsic.
- **Automation:** automatic.

## RDFUnit

- **ID:** `KG_TOOLS_RDFUNIT`
- **Dimensions covered:** Schema; Property; Consistency; Interlinking.
- **Description:** Rule-based validation framework using SPARQL test patterns to detect structural issues and missing links.
- **Link:** https://github.com/AKSW/RDFUnit

### Additional properties

- **Quality Category:** Intrinsic; Contextual; Accessibility.
- **Automation:** automatic.

## Schematron

- **ID:** `KG_TOOLS_SCHEMATRON`
- **Dimensions covered:** Standards; Format.
- **Description:** Rule-based validation language used to enforce standard compliance and structural rules.
- **Link:** https://schematron.com/

### Additional properties

- **Quality Category:** Representational; Accessibility.
- **Automation:** automatic.

## Metadata Quality Toolkit

- **ID:** `KG_TOOLS_METADATA_QUALITY_TOOLKIT`
- **Dimensions covered:** Structural; Readability.
- **Description:** Computes metrics for field completeness and textual readability in metadata records.

### Additional properties

- **Quality Category:** Contextual; Representational.
- **Automation:** automatic.

## KGTK (Knowledge Graph Toolkit)

- **ID:** `KG_TOOLS_KGTK_KNOWLEDGE_GRAPH`
- **Dimensions covered:** Population; Property; Richness; Interlinking.
- **Description:** Toolkit for profiling, connectivity analysis, and exploration of large knowledge graphs.
- **Link:** https://github.com/usc-isi-i2/kgtk

### Additional properties

- **Quality Category:** Contextual; Accessibility.
- **Automation:** semi-automatic.

## Silk Link Discovery Framework

- **ID:** `KG_TOOLS_SILK_LINK_DISCOVERY`
- **Dimensions covered:** Interlinking; Believability; Conciseness.
- **Description:** Discovers and validates links across datasets using similarity rules and can detect duplicates.
- **Link:** http://silkframework.org/

### Additional properties

- **Quality Category:** Intrinsic; Representational; Accessibility.
- **Automation:** automatic.

## LODsyndesis

- **ID:** `KG_TOOLS_LODSYNDESIS`
- **Dimensions covered:** Interlinking; Conciseness.
- **Description:** Indexes links across many knowledge graphs and computes sameAs closures to detect duplicates.
- **Link:** https://demos.isl.ics.forth.gr/lodsyndesis/

### Additional properties

- **Quality Category:** Representational; Accessibility.
- **Automation:** automatic.

## RDFind

- **ID:** `KG_TOOLS_RDFIND`
- **Dimensions covered:** Schema; Property; Format.
- **Description:** Detects structural dependencies and patterns in RDF data to identify missing or expected properties.
- **Link:** https://github.com/stratosphere/rdfind

### Additional properties

- **Quality Category:** Contextual; Representational.
- **Automation:** automatic.

## F-UJI

- **ID:** `KG_TOOLS_F_UJI`
- **Dimensions covered:** Accessibility; Interoperability.
- **Description:** Automatically evaluates FAIR indicators related to accessibility and interoperability.
- **Link:** https://www.f-uji.net/

### Additional properties

- **Quality Category:** Accessibility.
- **Automation:** automatic.

## FAIR-Checker

- **ID:** `KG_TOOLS_FAIR_CHECKER`
- **Dimensions covered:** Accessibility; Interoperability; Standards.
- **Description:** Validates FAIR compliance directly on RDF metadata using SPARQL and SHACL.
- **Link:** https://github.com/IFB-ElixirFr/FAIR-checker

### Additional properties

- **Quality Category:** Accessibility.
- **Automation:** automatic.

## FAIR Evaluator

- **ID:** `KG_TOOLS_FAIR_EVALUATOR`
- **Dimensions covered:** Accessibility; Interoperability; Licensing.
- **Description:** Executes machine-readable FAIR maturity indicator tests using web and API interrogation.
- **Link:** https://fairsharing.github.io/FAIR-Evaluator-FrontEnd/

### Additional properties

- **Quality Category:** Accessibility.
- **Automation:** automatic.

## FAIR-Shake

- **ID:** `KG_TOOLS_FAIR_SHAKE`
- **Dimensions covered:** Accessibility; Interoperability; Licensing; Standards.
- **Description:** Combines automated FAIR checks with human-evaluated rubrics.
- **Link:** https://github.com/MaayanLab/FAIRshake

### Additional properties

- **Quality Category:** Accessibility.
- **Automation:** semi-automatic.

## TripleCheckMate

- **ID:** `KG_TOOLS_TRIPLECHECKMATE`
- **Dimensions covered:** Factual; Semantic; Believability; Structural.
- **Description:** Crowdsourcing platform for human validation of RDF triples selected automatically.
- **Link:** https://aksw.org/Projects/TripleCheckMate.html

### Additional properties

- **Quality Category:** Intrinsic; Contextual.
- **Automation:** semi-automatic.

## KGEval

- **ID:** `KG_TOOLS_KGEVAL`
- **Dimensions covered:** Factual; Believability.
- **Description:** Uses statistical inference to minimize human effort in validating factual correctness of triples.
- **Link:** https://aclanthology.org/D17-1183/

### Additional properties

- **Quality Category:** Intrinsic.
- **Automation:** semi-automatic.

## Manual Metadata Quality Checklists

- **ID:** `KG_TOOLS_MANUAL_METADATA_QUALITY`
- **Dimensions covered:** Relevance; Labelling; Provenance.
- **Description:** Human-curated checklists used by institutions to assess qualitative metadata aspects.
- **Link:** not applicable

### Additional properties

- **Quality Category:** Contextual; Intrinsic.
- **Automation:** manual.

## SHACL Playground

- **ID:** `KG_TOOLS_SHACL_PLAYGROUND`
- **Dimensions covered:** Consistency; Format.
- **Description:** A constraint validator for the Shapes Constraint Language, written in JavaScript.
- **Link:** https://shacl.org/playground/

### Additional properties

- **Quality Category:** Intrinsic; Representational.
- **Automation:** automatic.
