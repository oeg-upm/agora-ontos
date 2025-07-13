# Contributing to the `agora-ontos` repository

Thank you for your interest in contributing to the Ágora ontology catalog! This repository is designed to collect and organize ontologies conceptualized using the **Chowlk** notation, with the goal of facilitating their visualization, search, and reuse through the Ágora application.

## Contribution Requirements

You can contribute any ontology as long as:
- It is **conceptualized using Chowlk notation**.
- It includes the required files in the appropriate format.
- It follows the structure described below.

---

## Required Structure for Each Ontology

Each ontology must be stored in its **own folder** within the repository, containing the following files:

/ontology-name/
│
├── ontology_name.xml # Chowlk conceptualization file
├── ontology_name.ttl # OWL generated from Chowlk (Turtle format)
├── ontology_name.jpg/png # Diagram image (.jpg or .png)
├── logo.png # (Optional) Project or source logo; must include the word "logo"
├── ontology_name_patterns.xml # (Optional) Pattern library extracted from the ontology; must include the word "patterns"

lternatively, multiple ontologies belonging to the same project or organization can be grouped under a single folder, following this structure:

/organization-name/
│
├── logo.png # (Optional) Project or organization logo; must include the word "logo"
├── /ontology-name/
│ │
│ ├── ontology_name.xml # Chowlk conceptualization file
│ ├── ontology_name.ttl # OWL generated from Chowlk (Turtle format)
│ ├── ontology_name.jpg/png # Diagram image (.jpg or .png)
│ ├── logo.png # (Optional) Logo specific to the ontology; must include the word "logo"
│ ├── ontology_name_patterns.xml # (Optional) Pattern library extracted from the ontology; must include the word "patterns"
├── /.../ # Additional folders for other ontologies within the organization

## Ways to Contribute Ontologies

There are **multiple ways to contribute** to the `agora-ontos` GitHub repository:

### 1. GitHub Pull Request (for users familiar with Git)

1. **Fork** the repository `agora-ontos`.
2. **Clone** your fork locally.
3. Create a new folder following the [required structure](#required-structure-for-each-ontology).
4. Add at least the following:
   - The `.xml` file with the Chowlk conceptualization.
   - The `.ttl` OWL file generated from Chowlk.
   - A preview image (`.jpg` or `.png`).
5. **Commit** and **push** the changes to your fork.
6. Open a **pull request** to the `main` branch of `agora-ontos`.

---

### 2. Upload Files via GitHub Web Interface

For users not familiar with Git, files can be uploaded directly via the GitHub interface:

1. Navigate to the desired folder in the repository.
2. Click on **"Add file" → "Upload files"**.
3. Drag and drop the required files (as described above).
4. Add a brief commit message.
5. Submit the changes.

---

### 3. Submit via GitHub Issue

For users who prefer not to upload files themselves:

1. Open a new **issue** in the [Issues](https://github.com/oeg-upm/agora-ontos/issues) section.
2. Title it as `New ontology contribution`.
3. Provide:
   - A description of the ontology.
   - A link to download the required files.
   - Any additional relevant details.

The maintainers will assist in reviewing and integrating the ontology into the repository.

---
