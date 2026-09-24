# Tropical Geometry and Amoebas

This repository contains the final degree project for the thesis "Geometría tropical y amebas" by Sergio Martínez Olivera. The canonical document is the PDF file `TFG_Matemáticas_def.pdf`.

## Repository classification

This is a mathematics thesis repository, not a software library or application. Based on the document itself, the verified scope is an academic final project on tropical geometry and amoebas, with explanatory text, proofs, and visual examples. There is no application code, package installation step, or automated build/test pipeline in this checkout.

## Verified project purpose

The thesis is organized around the interaction between tropical geometry and algebraic geometry through amoebas. The document explicitly studies:

- tropical semirings and tropical algebra
- tropicalization and Maslov dequantization
- tropical polynomials, Newton polygons, and dual subdivisions
- tropical curves and the balancing condition
- amoebas as logarithmic images of algebraic varieties
- non-Archimedean and Archimedean viewpoints
- the relationship between amoebas and tropical curves
- future applications, especially in machine learning and neural networks

The document also identifies GeoGebra and Python as the main tools used for visual and computational illustrations, while noting that any AI-assisted generated elements were verified and validated by the author.

## Mathematical and computational methods

The repository content reflects the following verified mathematical methods and concepts:

- max-plus/min-plus algebra and tropical semirings
- tropical polynomial and polynomial tropicalization
- Newton polygon duality and subdivision constructions
- tropical curves in low dimensions
- amoeba construction via logarithmic maps
- Archimedean and non-Archimedean amoebas
- valuation and initial-form ideas in the Kapranov framework
- Passare deformation retracts and the spine of an amoeba
- Hausdorff convergence between Archimedean and non-Archimedean amoebas

## Repository structure

- `README.md` — project overview and usage notes
- `TFG_Matemáticas_def.pdf` — the complete final written thesis

## Prerequisites

There are no project-specific runtime dependencies for viewing the repository itself. To read the PDF, use any PDF viewer or editor that supports standard PDF rendering. If you want to inspect or re-parse the PDF programmatically, Python with a PDF library such as `pypdf` is sufficient.

## Setup and execution

This repository does not contain an executable application or build process. The intended workflow is to open and read the thesis PDF, or to inspect it using a PDF processing script.

Example: view the document from a terminal on macOS:

```bash
open "TFG_Matemáticas_def.pdf"
```

Example: verify that the PDF loads and count its pages:

```bash
python - <<'PY'
from pypdf import PdfReader
reader = PdfReader('TFG_Matemáticas_def.pdf')
print(f'Pages: {len(reader.pages)}')
print(reader.metadata.title)
PY
```

## Examples and documented topics

The thesis includes examples and figures covering:

- tropical polynomial graphs and their geometric interpretation
- Newton polygons associated with plane polynomials
- tropical curves in two variables
- amoebas for specific algebraic varieties
- convergence of amoebas to tropical objects under dequantization
- relationships between tropical geometry and neural-network activation functions

## Reproducibility and provenance

The source of truth for the project is the PDF document itself. The repository does not include a separate source-code pipeline or dataset to regenerate that document automatically. The document states that the visualizations were produced mainly using GeoGebra and Python, and that any AI-assisted contributions were reviewed and validated by the author.

## Limitations

- The repository is document-centric rather than software-centric.
- There is no installable package, CLI, library, or application to run.
- The mathematical results are contained in the thesis PDF; no additional implementation files are provided here.
- The repository is best understood as an archival and presentation repository for a final undergraduate/master's mathematics project.

## Status

This repository is effectively a thesis archive and documentation repository. It is not an actively maintained software project, but it remains a complete record of the verified final work described in `TFG_Matemáticas_def.pdf`.
