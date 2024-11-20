# Bengali-Inscription-to-Knowledge-Graph (BIKG) 
Bengali-Inscription-to-Knowledge-Graph (BIKG) is a pioneering project that aims to make Bengali cultural history accessible, understandable, and interactable through a digital platform. It focuses on converting historical Bengali inscriptions into a structured knowledge graph, leveraging state-of-the-art techniques in data extraction, ontology development, and semantic querying. `The folder size is bigger than 100MB. So, we add it in releases.`

## Project Overview
BIKG integrates multiple data sources and methodologies to process 47 inscriptions from the 3rd century B.C. to the 12th century A.D. It ensures that historical data is preserved and made available in a ready-to-query format.

The workflow includes:

1. Data Extraction: Gathering raw data from inscriptions.
2. Preprocessing: Converting extracted data into structured text or CSV formats.
3. RDF Generation: Creating RDF triples using existing vocabularies and Large Language Models (LLMs).
4. Ontology Development: Using SETLBi for ABox and TBox generation.
5. Data Storage: Uploading ontologies to Virtuoso Conductor for semantic querying.
6. Analytical Interface: Querying the BIKG with SPARQL to gain insights.

## Key Features
- Historical Data Integration: Incorporates a diverse range of inscriptions, ensuring cultural representation.
- Semantic Framework: Uses Resource Description Framework (RDF) to represent historical knowledge systematically.
- Advanced Querying: Supports SPARQL queries for detailed data analysis and insights.
- Modern Tools:
  - RDF Generation with existing vocabularies and LLMs.
  - Virtuoso Conductor for ontology management.

## Requirements
To run or contribute to BIKG, you need the following:

- RDF Processing Tools: SETLBi or equivalent software.
- Ontology Management Software: Virtuoso Conductor.
- Querying Tools: Tools capable of executing SPARQL queries.

## Usage Instructions
1. Data Preprocessing: Use the provided scripts to extract and preprocess raw data into CSV formats.
2. Ontology Creation: Generate RDF triples and ontologies using the RDF Generator and SETLBi.
3. Upload Ontologies: Load the ABox and TBox into Virtuoso Conductor.
4. Run SPARQL Queries: Use the Analytical Interface to fetch historical insights.

## Contribution
We welcome contributions! If you would like to collaborate, please:

1. Fork the repository.
2. Make your changes in a separate branch.
3. Submit a pull request with a detailed description of your updates.


## License

This project is licensed under the [MIT License.](https://choosealicense.com/licenses/mit/)

