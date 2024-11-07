.. ChemoPar-db documentation master file, created by
   sphinx-quickstart on November 7, 2024.

========================================================
ChemoPar-db: A Structural Chemogenomics Database
========================================================

Welcome to **ChemoPar-db** documentation! ChemoPar-db is a specialized database designed to provide comprehensive structural information on chemokines and their diverse binding partners. This resource supports researchers in exploring chemokine interactions, structural motifs, and binding partners, with features tailored for easy access to curated data on chemokines and their roles in immune system function and disease processes.

Overview
========

Chemokines are small, secreted signaling proteins essential for immune cell migration and cellular communication. They play key roles in inflammatory responses and disease states, including cancer and autoimmune conditions. Given the unique interaction profiles of chemokines with GPCRs, glycosaminoglycans (GAGs), other chemokines, and pathogen-derived proteins, ChemoPar-db offers a valuable tool for understanding these complex interactions.

ChemoPar-db includes:
- **233 curated chemokine structures** as of October 23, 2024, covering diverse states (monomers, dimers, oligomers).
- **38 unique binding partners**.
- **Reference sequence alignments** to facilitate comparative analysis of chemokine structures.
- **Molecular interaction fingerprints** (IFPs) for detailed interaction annotations.

Features
========

The database offers the following features:

- **Browse and Search**: A user-friendly search interface for finding chemokine structures, sequences, and interaction partners.
- **Protein Information**: Detailed annotations for each chemokine, including structural motifs and binding sites.
- **Structure Page**: View structure details, including resolution, experimental method, and oligomeric states.
- **Interaction Analysis**: Visualization and tabulation of molecular interactions with binding partners, downloadable as Excel files.
- **RESTful API**: Programmatic access for data integration into custom workflows, available at https://chemopar-db.net/api.

Data Accessibility
==================

ChemoPar-db is freely accessible to all users at https://chemopar-db.net, with both web and programmatic API access. Researchers can retrieve sequence data, structure files, and interaction fingerprints to support bioinformatics and cheminformatics applications.

Getting Started
===============

To begin using ChemoPar-db, visit the `Home Page <https://chemopar-db.net>`_ to browse or search entries. You can explore proteins, structures, and binding partners, with each entry providing in-depth data, structural annotations, and visualizations. For programmatic access, consult our API documentation available on the "API" page of the site.

Documentation Contents
======================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   getting_started
   protein_data
   structure_data
   interaction_analysis
   api_usage
   faq

Support
=======

For questions or assistance with ChemoPar-db, please refer to the **FAQ** page or contact our support team at `support@chemopar-db.net`.

.. note::
   **Acknowledgments**: ChemoPar-db was developed by the Division of Medicinal Chemistry, AIMMS, Vrije Universiteit Amsterdam, and the Department of Drug Design and Pharmacology, University of Copenhagen.

Index
=====

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
