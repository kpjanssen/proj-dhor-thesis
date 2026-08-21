# dhor_thesis
Predicting the voting behavior of Members of the Dutch House of Representatives

A Linguistic approach utilizing parliamentary documents during cabinet Rutte III and Rutte IV (2017-2023)

Koen Peter Janssen


Supervisor: dr. Merel Jung

Comittee: dr. Nevena Ranković

Run\analyse the code in the order it is numbered.

## data

**The datasets are not included in this repository.** The notebooks read from a local `data/` directory and write their intermediate files back into it, so a fresh clone will not run end to end — every notebook stops at its first read. The paths are set at the top of each notebook as `file_path` and, in `20_data_unstructured_motions.ipynb`, `document_path`.

The source material is public record: voting records and parliamentary documents of the Dutch House of Representatives (Tweede Kamer) covering cabinets Rutte III and Rutte IV, 2017-2023.

The notebooks are published as a record of the method — the feature engineering, sampling comparison, model tuning and feature-importance analysis are all readable without running anything.

## license

MIT — see [LICENSE](LICENSE).
