Dataset Description
Space Weather May 2024 – Slovenia Event Dataset

Overview
This dataset documents environmental disturbances and cascading impacts on infrastructure and operational systems in Slovenia during the May 2024 space weather event.
The dataset integrates information from multiple public sources including official reports, operator bulletins, and media coverage. It provides a structured representation of environmental forcing, operational incidents, and aggregated daily statistics used for research on cascading system disturbances.
The repository also contains the derived Cascading Systems Complexity Index (CSCI) values calculated from the integrated dataset.

Data sources
Data were compiled from publicly available sources including:
- ARSO (Slovenian Environment Agency) reports and environmental information
- ELES transmission system operator reports
- Civil protection daily bulletins
- publicly available media articles.

A catalogue of sources with URLs and archival references is provided in the 1_sources directory.
The repository contains derived and structured data extracted from these sources; original documents remain subject to their respective copyright and usage policies.

Dataset structure
The repository is organised into several data layers:
1_sources – catalogue of original sources and references
2_tso – transmission system operator (ELES) reports and extracted event information
3_events – base event datasets including raw environmental events, operational events, daily statistics, and daily context descriptions
4_daily_integrated – integrated daily dataset combining environmental forcing and sectoral impacts
5_metrics – definitions and documentation of analytical metrics
6_csci_outputs – calculated CSCI values and summary tables
dataset – final datasets used in the analysis
methodology – documentation describing the data processing and classification methods.

Main datasets
The key datasets included in the repository are:
raw_events.tsv – extracted environmental and incident events
raw_ops_events.tsv – operational infrastructure events reported by system operators
daily_stats.tsv – aggregated daily incident statistics from civil protection bulletins
daily_context.tsv – qualitative daily context descriptions
daily_integrated.tsv – integrated daily dataset combining all event layers
csci_daily_index.tsv – calculated Cascading Systems Complexity Index values.

Temporal coverage: May 2024.
Geographic coverage: Slovenia, with contextual references to broader European environmental conditions when relevant.
Methodology: Event extraction, classification rules, and metric definitions are documented in the methodology directory.

Usage
The dataset is intended for research on:
- cascading system disturbances
- infrastructure resilience
- environmental forcing and operational impacts
- complex event dynamics.

Citation: Dataset archived on Zenodo: https://doi.org/10.5281/zenodo.18105785
License: This dataset is distributed under the Creative Commons Attribution 4.0 (CC-BY 4.0) license unless otherwise noted.
