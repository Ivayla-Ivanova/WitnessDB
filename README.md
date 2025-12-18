# WitnessDB

Ensuring the correctness of software systems remains a critical goal in software
engineering, with formal verification providing strong guarantees through mathe-
matical proofs. Verification witnesses have been introduced as standardized artifacts
that capture the verification process to enhance the transparency, reproducibility,
and trustworthiness of verification results. Despite their value for validation,
benchmarking, and research, these witnesses are currently stored only as individual
files within large archives, which is inconvenient for large-scale querying, analysis,
and visualization.
This thesis presents WitnessDB, a system for storing, validating, and exploring
verification witnesses using the Neo4j graph database. WitnessDB transforms veri-
fication results encoded in Witness Format 2.0 (YAML) into graph structures and
allows querying and interactive analysis through graphical and tabular interfaces.
By leveraging the capabilities of a graph database, WitnessDB demonstrates how
complex, interconnected verification data can be modeled in ways that potentially
unlock new use cases and encourage new approaches to analysis.
