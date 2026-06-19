# Two distinct causal beliefs organizing intuitions about mind, action, and body

This repository contains data and scripts for the project "Two distinct causal beliefs organizing intuitions about mind, action, and body" by Joseph Outa and Shari Liu. If you have any questions about this repository, please contact Joseph Outa at jouta1 [at] jhu [dot] edu.

This is the repository structure and breakdown: 

```
.
├── code
│   ├── analysis
│   ├── codebooks
│   └── data
├── docs
│   ├── images
│   ├── jspsych
│   └── video
├── manuscript
│   └── figures
├── preregistrations
├── README.md
└── SI - Supplementary Information.pdf
```
## Folder contents

### Code
This folder contains the R analysis scripts and data files and codebooks for Experiments 1 - 6.

Feel free to download the repository (button on top right) and look through the files. If you would like to quickly view the analysis reports, you can download just the .html report for the corresponding study, and double-click to open it on your browser (i.e. go to `/code/analysis/1_measure/` and download `/experiment1_analysis.html`). 

### Docs
This folder contains the experimental stimuli. Both experiments was implemented using jsPsych, and are available at the html files `docs/study1.html`, `docs/study2_inference.html` and `docs/study2_intervention.html`. The `/images`, `video`, and `/jspsych` folders contain supporting materials for the experiments. 

## Supplementary Information
In the home directory is a pdf document containing Supplementary Information for the paper. 

## The analysis pipeline

The following is a flowchart depicting the analysis pipeline:

![pipeline_guide](https://github.com/user-attachments/assets/9b5ee686-98c6-498a-ab1f-ef4730f9041c)

The flowchart above describes the steps in the analysis: The raw experiment data from experiment 1 (top left, in red) was read into the r markdown pre-processing script, and analyzed. In the process, two csv files were generated, which were passed as inputs to the main analysis script (top right). One csv was generated from this analysis, which was used as an input to the study 2 analysis, alongside a raw data file from the experiment.

Across the two studies, there are 3 analysis scripts, and 5 relevant data csvs. There is a codebook for all 5 data files in the `code/codebooks/` folder. These codebooks consist of knitted `.html` reports generated using the `codebook` package from Arslan (2019), and contain description of the header columns of each dataset. The names of the codebooks correspond to the names of the datasets they describe. All codebooks can be directly downloaded and double-clicked for viewing.

Thank you for accessing these materials!

### Manuscript

Contains the manuscript submitted to the 2025 Cognitive Science Society Conference.






