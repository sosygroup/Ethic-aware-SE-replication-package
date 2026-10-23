# Calculated expert-validation results


## Calculation and verification
Read-only extraction from the 21 workbooks in Academia and Industry, using native Sheets bounded range reads and readable Excel text. No original was changed. Expert 1–21 follow the same source order as the full-width v2 profile table. Three QO and eight QC questions were located by their IDs rather than cell offsets. Each expert had exactly three cluster assessments. Checks confirmed 63 expert–cluster pairs, 504 QC slots, 63 QO slots, 562 valid ratings, five N/A and zero blank quantitative answers. No duplicate expert–cluster–item record or unparsed response remained. All 24 clusters had at least one academia and one industry reviewer (15 clusters: 2A/1I; 9 clusters: 1A/1I).

Ratings are ordinal 1–5. Main tables use median, Q1–Q3 and counts/proportions of 4–5 ratings. Quartiles use NumPy's linear interpolation; IQR=Q3−Q1. N/A and missing responses are excluded from valid denominators and remain distinct. The 3 category is partial agreement/neutral, not rejection. Counts are preferred over percentages alone for small clusters. QC pooled summaries count repeated expert–cluster assessments and should not be interpreted as independent samples. No significance tests, confidence intervals or reliability-scale claims are made.

The profile comparison reports pooled values plus a descriptive mean difference within each comparable cluster, equally weighting clusters. QC1 has 23 comparable clusters; QC4 and QC8 have 22, because N/A removes the only industry rating in the affected clusters. All other QC comparisons use 24. Both profiles reviewed each cluster, but N/A can remove item-level comparability. Profile comparisons do not identify causal profile effects.

Section indices are supplementary arithmetic means across all four valid items per expert–cluster pair. Each section retains 61 pairs and excludes two incomplete pairs. These are descriptive composites, not validated scales. The equal-expert sensitivity calculation first averages each expert's valid ratings for each QC item, then averages those 21 expert means. It tests unequal valid-response weighting without treating repeated responses as independent experts.

## Qualitative synthesis and privacy
The qualitative table is a targeted, single-pass synthesis of recurring improvement issues. The selected-evidence CSV explicitly lists the records supporting every displayed expert count. It is not a complete independent coding of all comments, and the counts are documented supporting counts rather than exhaustive prevalence. Some comments support more than one theme; counts must not be summed. All proposed refinements await author review, implementation and revalidation. No claim of completed catalogue revision is made.

Anonymous comments are supplied for review. They retain original spelling and wording. The published LaTeX uses synthesis rather than identifying quotations and includes no names, organisations or source links. Anonymous IDs are pseudonyms.

## Limits
Each cluster has only two or three reviewers; individual distributions matter. Overall usefulness is expert-perceived usefulness, not measured deployment effectiveness. Non-random expert selection and the questionnaire's combined partial-agreement/neutral category limit interpretation. The output is a draft results section for author review.

Largest absolute difference between pooled and equal-expert QC means: 0.0297 rating points.
