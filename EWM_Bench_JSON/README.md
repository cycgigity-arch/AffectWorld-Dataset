# EWM-Bench Dataset (annotations-first release)

This repository currently contains annotations and sample identifiers. Video files are being uploaded separately.

- `annotations_1498.json`: 1,498 normalized annotation records, keyed by `video_key`. Each record includes `ewm_unit` and task eligibility in `qc.tier`. Counterfactual annotations are embedded for 223 records.
- `splits.json`: the exact 1,451 `video_key` values used in the Task 2/Task 3 evaluation shards, and the 223 records with counterfactual annotations. The overlap is 176; the other 47 counterfactual records are outside the 1,451-video evaluation cohort.

The `video_url` values in annotation records point to source references; this repository does not currently host those source videos. Video release status and download links will be added later.

Data license and redistribution terms: to be specified by the dataset authors before reuse is permitted.
