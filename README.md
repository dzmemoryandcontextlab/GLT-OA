# GLT-OA

Analysis scripts for the Grid Learning Task (GLT) and Mnemonic Similarity Task (MST) study of younger and older adults (Experiment 1) and individual differences in younger adults (Experiment 2).

## Data

Please download the data files (note on 11/13/2026; The PsychArchives link will be updated in the next few days.) and organize them as below.

```
OA-github/
├── Exp1/
│   ├── Exp1-OA-6.html
│   └── data/
│       ├── 6x6-glt-age-npsych-complete.csv
│       ├── glt/
│       └── mst/
└── Exp2/
    ├── Exp2-OA-indi-diff.html
    └── data/
        ├── fix.csv
        ├── glt/
        └── mst/
```

## Files

- `Exp1-OA-6.html` is the knitted output.
- `Exp2-OA-indi-diff.html` is the knitted output.
- `6x6-glt-age-npsych-complete.csv` contains neuropsychological assessment data (MoCA, RAVLT, Digit Span) and session notes used for exclusions in Experiment 1.
- `fix.csv` lists participant IDs that were revised because of duplicated ID numbers in Experiment 2. These participants are excluded in the validation analysis.
- `glt/` contains raw Grid Learning Task output files, one per participant.
- `mst/` contains raw Mnemonic Similarity Task output files, one per participant.

