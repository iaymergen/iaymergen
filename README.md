## İpek Güneş Aymergen

Computer Engineering student at Istanbul Technical University. I build data pipelines and ML systems that hold up at scale, and I've worked in both research and production, from genomic datasets to financial ones. I'm interested in research at the intersection of computing, data and the life sciences.

### Experience

**Vodafone Türkiye** · Data Analyst Intern · Oct 2026 – present
- Data work in SQL and Python.

**TU Delft, Abeel Lab** · Research Intern · Jul – Aug 2026
- Built Metadata Agent, an LLM agent pipeline that extracts sample metadata from scientific papers and database records.
- Built a hand-annotated ground truth and benchmarked three models (Gemini 2.5 Flash, Nemotron via OpenRouter, and TU Delft's own LLM, Tulip), reaching about 77% average accuracy on four test papers.

**Prometeia** · Junior Data Scientist · Feb – Jun 2026
- Built a modular data quality pipeline for financial datasets from SQL and Parquet sources: statistical profiling, IQR outlier detection, CSI/PSI drift monitoring and correlation analysis.
- Built the feature shortlist for a credit limit assignment model, using correlation filtering and feature importance scoring.
- Designed a fraud detection benchmark on 590K transactions, comparing Isolation Forest, COPOD and an autoencoder against XGBoost. Three-stage feature selection cut 486 features to 33, and models were tested on a time-ordered out-of-time split ([code](https://github.com/iaymergen/outlier-detection)).

**İTÜ, Baysan Lab** · Research Intern · Nov 2025 – present
- Graduation project, funded by TÜBİTAK: a reproducible Snakemake pipeline that benchmarks five CNV detection tools on 8 exome samples, run as parallel jobs on the university HPC cluster.
- Built a two-level evaluation of deletions and duplications (precision, recall, F1) against the Chaisson et al. truth set, and reproduced the published results of ECOLE, a deep learning CNV caller.
- Earlier in the lab: built and compared 12 somatic variant-calling pipelines on a germline–tumour pair ([code](https://github.com/iaymergen/variant-calling-evaluation)).

**University of Zürich, Robinson Lab** · Research Intern · Jun – Aug 2025
- Built [TFBPlatform](https://www.ethz-ins.org/TFBPlatform/), a public platform for exploring transcription factor binding predictions: ~1 TB of data covering 3.8M genomic regions, 1,224 TF models and 43 cell types.
- Wrote Python/R/Bash pipelines that clean mixed-format data (CSV, TSV, RDS, HDF5) with row-count quality checks, and designed the MySQL schema from scratch.
- Cut database loading from hours to minutes with bulk operations and indexing.
- Integrated outputs from the TFBlearner ML framework into the web app (Vue.js, Laravel, Docker) so users can explore predictions and feature importance.
- Processed single-cell chromatin accessibility data with Signac and Cicero to build features for a PGBoost model.
- Second author on the resulting preprint (below).

**Earlier:** JGU Mainz (CPR education web platform, 2024) · Softtech (LLM prompt engineering, 2024) · IT Team Coordinator, EESTEC LC Istanbul

### Publication

Sonder, E., **Aymergen, İ. G.**, et al. *Large-scale prediction of transcription factor binding across human cell types informs regulatory genomics and reveals promiscuous occupancy associated with chromatin contacts.* bioRxiv, 2026. [Link](https://www.biorxiv.org/content/10.64898/2026.06.16.732527v1)

### Skills

Python · SQL · R · C/C++ · Java · Optuna · LLM agents · Snakemake · Docker · HPC · MySQL · Git

[LinkedIn](https://www.linkedin.com/in/ipek-gunes-aymergen/) · [Email](mailto:ipekaymergen2@gmail.com)
