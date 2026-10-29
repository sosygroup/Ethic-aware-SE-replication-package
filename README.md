# Ethic-aware-SE-replication-package

Replication package for **Bridging Concept and Practice: A Developer-Facing Catalogue for Ethics-Aware Software Engineering**.

This repository provides the research materials supporting the construction and expert validation of a catalogue for addressing ethical concerns in software engineering.

The catalogue translates ethical concerns into practical actions, possible evidence artefacts, suggested software development lifecycle (SDLC) phases, responsible roles, and supporting references. It comprises **24 concern clusters** and was evaluated by **21 experts from academia and industry**.

The materials allow readers to explore the catalogue, trace its construction, inspect the evaluation instruments, and examine the anonymised validation data.

## Contents

- **[Concerns_bases.xlsx](Concerns_bases.xlsx):** Ethical concerns collected from the literature and industry, with the consolidated list.
- **[Selected_References.xlsx](Selected_References.xlsx):** Supporting references used to construct the catalogue.
- **[Clusterization/](Clusterization/):** Human and LLM-assisted clustering, the prompt used, and reconciliation materials.
- **[Ethics_Catalogue/](Ethics_Catalogue/):** Consolidated catalogue of 24 ethical concern clusters after expert validation; also, the prompt used to map concern clusters to ethical label cards and their associated values; and the actions cycle foundations.
- **[Interview_preparation/](Interview_preparation/):** Pre-read brief and evaluation workbooks used in the expert interviews.
- **[Interview_Results_Data/](Interview_Results_Data/):** Anonymised ratings, comments, and descriptive results from the expert evaluation.
- **[README.md](README.md):** Overview of the repository and its contents.

## 1. Ethical Concern Sources

### Concerns_bases.xlsx

This workbook documents the ethical concerns used as the starting point for catalogue construction. It contains three worksheets:

- **Literature:** concerns extracted from the systematic mapping study.
- **Industry:** concerns reported by industry practitioners.
- **Final_Concerns:** consolidated list bringing together concerns from both sources.

These materials provide the basis for the subsequent clustering process.

### Selected_References.xlsx

This workbook contains the registry of supporting references used in the catalogue. Reference identifiers connect catalogue entries to their underlying sources, supporting traceability and further reading.

## 2. Concern Clustering

The [Clusterization/](Clusterization/) folder documents the grouping of ethical concerns and the reconciliation of the resulting clusters.

| File | Description |
| --- | --- |
| [Concerns-human-clustering.xlsx](Clusterization/Concerns-human-clustering.xlsx) | Human-produced clustering of the ethical concerns. |
| [Concerns_Semantic_Clustering_LLM.xlsx](Clusterization/Concerns_Semantic_Clustering_LLM.xlsx) | LLM-assisted semantic clustering, including explanations of the proposed groupings. |
| [Prompt_Used-LLM.pdf](Clusterization/Prompt_Used-LLM.pdf) | Prompt used to guide the LLM-assisted clustering task. |
| [Reconciliation_base_round2.xlsx](Clusterization/Reconciliation_base_round2.xlsx) | Materials supporting the reconciliation of the clustering results into the consolidated structure of 24 clusters. |

Together, these files allow readers to inspect the clustering approaches and the materials used to establish the catalogue structure.

## 3. Consolidated Catalogue

The [Ethics_Catalogue/](Ethics_Catalogue/) folder contains the main research artefact:

### Consolidated-catalogue-after-validation.xlsx

This workbook presents the consolidated catalogue after expert validation. It contains one worksheet for each of the **24 concern clusters**, identified as **C01–C24**, and a **References** worksheet.

Each cluster includes:

- Its definition, scope, and associated ethical concerns.
- The semantic rationale for the grouping.
- Boundary and overlap decisions.
- Mappings to ethical label cards.
- Practical actions and the concerns they address.
- Possible evidence artefacts.
- Suggested SDLC phases and responsible roles.
- Supporting reference identifiers.

The operational recommendations follow a recurring six-action structure:

**Know → Protect → Inform → Assess → Validate → Respond**

Artefacts, phases, and roles are intended as adaptable guidance. Their application should reflect the system, team, and organisational context. Ethical concerns may also overlap across clusters.

### Prompt_mapping_label_cards.pdf

Prompt used to map concern clusters to ethical label cards and their associated values, justify each mapping, and distinguish primary and secondary mappings.

### Actions-Cycle-Fundations.pdf

The conceptual foundations of the actions cycle proposed. The references used can be found in the file **[Selected_References.xlsx](Selected_References.xlsx):**.

## 4. Interview Preparation

The [Interview_preparation/](Interview_preparation/) folder contains the materials prepared for the expert evaluation.

### Expert_Validation_PreRead_Brief.pdf

A briefing document introducing the catalogue and preparing participants for the evaluation.

### Evaluation Workbooks

Each workbook covers three concern clusters and includes an overall evaluation worksheet and cluster-specific evaluation materials.

| Workbook | Clusters covered |
| --- | --- |
| [C01-C03.xlsx](Interview_preparation/C01-C03.xlsx) | C01–C03 |
| [C04-C06.xlsx](Interview_preparation/C04-C06.xlsx) | C04–C06 |
| [C07-C09.xlsx](Interview_preparation/C07-C09.xlsx) | C07–C09 |
| [C10-C12.xlsx](Interview_preparation/C10-C12.xlsx) | C10–C12 |
| [C13-C15.xlsx](Interview_preparation/C13-C15.xlsx) | C13–C15 |
| [C16-C18.xlsx](Interview_preparation/C16-C18.xlsx) | C16–C18 |
| [C19-C21.xlsx](Interview_preparation/C19-C21.xlsx) | C19–C21 |
| [C22-C24.xlsx](Interview_preparation/C22-C24.xlsx) | C22–C24 |

The evaluation involved **21 experts**, each assessing three clusters, yielding **63 expert–cluster assessments**. Every cluster was assessed by at least one academic expert and one industry expert.

## 5. Interview Results and Analysis

The [Interview_Results_Data/](Interview_Results_Data/) folder provides anonymised evaluation data and descriptive analysis outputs.

| File | Description |
| --- | --- |
| [README.md](Interview_Results_Data/README.md) | Methodological notes on the calculations, qualitative synthesis, and interpretation of the results. |
| [anonymous_ratings.csv](Interview_Results_Data/anonymous_ratings.csv) | Quantitative responses, including pseudonymous expert identifiers, expert profiles, clusters, evaluation items, ratings, and response status. |
| [anonymous_comments.csv](Interview_Results_Data/anonymous_comments.csv) | Qualitative comments linked to pseudonymous expert identifiers, profiles, clusters, and evaluation items. |
| [question_wording.csv](Interview_Results_Data/question_wording.csv) | Wording of the overall evaluation questions (QO) and cluster-specific evaluation questions (QC). |
| [cluster_coverage.csv](Interview_Results_Data/cluster_coverage.csv) | Number of academic and industry experts who assessed each cluster. |
| [expert_weighting_sensitivity.csv](Interview_Results_Data/expert_weighting_sensitivity.csv) | Comparison of pooled mean ratings with means calculated by giving equal weight to each expert. |
| [selected_qualitative_evidence 2.csv](Interview_Results_Data/selected_qualitative_evidence%202.csv) | Selected comments organised into refinement themes, with traceability to the corresponding evaluation records. |
| [cluster_heatmap.png](Interview_Results_Data/cluster_heatmap.png) | Visual summary of cluster evaluation results. |
| [Experts-profile.pdf](Interview_Results_Data/Experts-profile.pdf) | The profile of the 21 experts involved in the validation. |

### Interpretation Notes

- Ratings use a **1–5 scale**, with **N/A** where applicable.
- N/A responses should be excluded from valid-rating denominators.
- Each expert assessed multiple clusters; pooled assessments should not be interpreted as independent participants.
- Selected qualitative comments may support more than one theme. Theme counts should therefore not be summed.
- Expert feedback reflects perceived quality and usefulness; it does not establish effectiveness in deployed software projects.

## How to Explore the Package

1. **Start with the catalogue:** open `Ethics_Catalogue/Consolidated-catalogue-after-validation.xlsx`.
2. **Trace its construction:** review `Concerns_bases.xlsx` and the materials in `Clusterization/`.
3. **Consult supporting sources:** open `Selected_References.xlsx` or the catalogue’s `References` worksheet.
4. **Understand the evaluation:** read the pre-read brief and evaluation workbooks in `Interview_preparation/`.
5. **Inspect the evidence:** explore the anonymised data and methodological notes in `Interview_Results_Data/`.

The files can be downloaded individually or together through **Code → Download ZIP**. Spreadsheet files require a compatible spreadsheet application; PDF files require a PDF reader. CSV files can be opened in a spreadsheet application or processed with a data-analysis tool.

## Related Tool: EthicSpark

The catalogue also provides the knowledge base for **EthicSpark**, a conversational tool designed to help developers adapt generic ethical guidance to the context of a specific software application.

The application source code is maintained separately:

[EthicSpark — Ethics-Aware SE Catalogue](https://github.com/sosygroup/ethics-aware-se-catalogue)
