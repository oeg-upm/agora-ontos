# Contributing to the `agora-ontos` repository

Thank you for your interest in contributing to the Ágora ontology catalog! This repository is designed to collect and organize ontologies conceptualized using the **Chowlk** notation, with the goal of facilitating their visualization, search, and reuse through the Ágora application.

## Contribution Requirements

You can contribute any ontology as long as:

- It is **conceptualized using Chowlk notation**.
- It includes the required files in the appropriate formats.
- It follows the structure described below.

## Required Structure for Each Ontology

Each ontology must be stored in its own folder within the repository, with the following files:

<pre>
/ontology-name/
│
├── ontology_name.xml               # Chowlk conceptualization file
├── ontology_name.ttl               # OWL generated from Chowlk (Turtle format)
├── ontology_name.jpg or .png       # Diagram image
├── logo.png                        # (Optional) Project or source logo (must include "logo")
└── ontology_name_patterns.xml      # (Optional) Pattern library (must include "patterns")
</pre>

Alternatively, you can group multiple ontologies belonging to the same project or organization under a shared folder:

<pre>
/organization-name/
│
├── logo.png                        # (Optional) Organization logo (must include "logo")
├── /ontology-name/
│   ├── ontology_name.xml               # Chowlk conceptualization file
│   ├── ontology_name.ttl               # OWL generated from Chowlk (Turtle format)
│   ├── ontology_name.jpg or .png       # Diagram image
│   ├── logo.png                        # (Optional) Specific ontology logo (must include "logo")
│   └── ontology_name_patterns.xml      # (Optional) Pattern library (must include "patterns")
├── /.../                             # Additional folders for other ontologies
</pre>

## Ways to Contribute Ontologies

Ágora is conceived as an open and collaborative ontology catalog, aiming to grow through user contributions of ontologies developed using the Chowlk notation. To support different levels of technical expertise, there are multiple ways to contribute to the `agora-ontos` GitHub repository.

### 1. GitHub Pull Request (for users familiar with Git)

This is the preferred method for users comfortable with Git and GitHub:

1. Fork the repository `agora-ontos`.
2. Clone your fork locally.
3. Create a new folder following the required structure above.
4. Add at least the following:
   - The `.xml` file with the Chowlk conceptualization.
   - The `.ttl` OWL file generated from Chowlk.
   - A preview image (`.jpg` or `.png`).
5. Commit and push the changes to your fork.
6. Open
