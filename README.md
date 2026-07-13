# Cross-Platform Digital Persona Analysis

An exploration and synthesis of personal digital footprints using data extracted from Indeed, OpenAI, and Meta. This project applies the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework to transform raw, semi-structured metadata into a structured digital persona profile while adhering strictly to data governance principles.

## Project Overview
[cite_start]This project uncovers the geo-cultural and professional trends hidden within personal data exports[cite: 162, 187, 188]. [cite_start]By analyzing interaction histories, location logs, and audience demographics across three major digital ecosystems, the study maps out professional readiness, AI synergy, and global network reach[cite: 215, 227].

## Datasets Processed
[cite_start]The project analyzed over 100 raw files totaling **240 MB**[cite: 169]. [cite_start]The core analysis focused on four specific semi-structured JSON files[cite: 126, 170, 171]:
* [cite_start]`Profile_Preferences.json` (Indeed): Established professional baselines, target roles, and remote work preferences[cite: 129, 143].
* [cite_start]`conversations.json` (OpenAI): Captured proactive learning prompts, tool-assisted upskilling, and IP-based geographic verification[cite: 130, 216].
* [cite_start]`audience_demographics.json` (Meta/Instagram): Quantified the distribution of international vs. local digital reach[cite: 131, 143].
* [cite_start]`link_history.json` (Meta/Instagram): Cataloged behavioral interaction patterns and external content engagement[cite: 132, 143].

## Methodology (CRISP-DM)
1. [cite_start]**Business Understanding:** Defined core goals to investigate how interaction with professional and AI systems affects global digital reach and personal branding[cite: 160, 161, 162].
2. [cite_start]**Data Understanding:** Explored raw multi-platform archives, identifying critical behavioral schemas within massive nested JSON objects[cite: 169, 170, 171].
3. [cite_start]**Data Preparation:** Isolated relevant datasets, filtered out thousands of lines of noisy system metadata, and aligned timestamps to ensure data consistency for the year 2025[cite: 134, 135].
4. [cite_start]**Modelling:** Integrated clean datasets to construct a multi-dimensional Digital Persona Profile mapping localized professional efforts alongside international networks[cite: 185, 187, 188].
5. [cite_start]**Evaluation:** Verified data-driven insights against ground-truth activity logs (including 142 distinct link-clicks and 18 AI conversations) to ensure analytical validity[cite: 193, 195].

## Core Tools Used
* [cite_start]**VS Code & Notepad++:** For raw data parsing, linting, and formatting semi-structured data chunks[cite: 178].
* [cite_start]**JSON Linting:** Employed structured environment shortcuts to safely format, audit, and clean deeply nested objects[cite: 178, 179].

## Data Governance & Compliance
[cite_start]Designed with a "Privacy First" framework, this study strictly complies with **GDPR** regulations[cite: 205]:
* [cite_start]**Data Minimization:** Excluded all highly sensitive or irrelevant structural contents (e.g., private messaging caches)[cite: 206, 207].
* [cite_start]**Secure Local Storage:** Processed entirely on a dedicated, encrypted local storage drive to eliminate third-party exposure risks[cite: 209].
* [cite_start]**Data Retention:** Formulated a strict deletion protocol scheduled for the conclusion of the academic cycle[cite: 210, 211].
