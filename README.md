# SARS-CoV-2-glycosylation-site-analysis-project
Analysis of SARS-CoV-2 spike protein glycosylation motifs. Identifies canonical NXS/T sites, detects near-miss variants, summarizes per-sequence distributions, and generates statistical plots and LaTeX reports for downstream interpretation.
sarscov2-glyco-analysis/
│
├── data/                  # raw and processed sequence data
│   ├── input_sequences.fasta
│   └── alignment_results/
│
├── notebooks/             # Jupyter notebooks for exploration
│   ├── motif_search.ipynb
│   └── visualization.ipynb
│
├── scripts/               # Python scripts for analysis
│   ├── count_glyco_sites.py
│   ├── near_miss_analysis.py
│   └── plot_histograms.py
│
├── results/               # outputs, CSV summaries, plots
│   ├── motif_almost_hits.csv
│   ├── motif_almost_summary.csv
│   └── figures/
│       ├── canonical_vs_nearmiss.png
│       └── distributions.png
│
├── report/                # LaTeX project writeup
│   ├── main.tex
│   ├── sections/
│   │   ├── introduction.tex
│   │   ├── methods.tex
│   │   ├── results.tex
│   │   └── discussion.tex
│   └── references.bib
│
├── environment.yml        # conda environment (Biopython, matplotlib, etc.)
├── requirements.txt       # pip dependencies
├── README.md              # project description and usage
└── LICENSE                # license file (MIT recommended)
