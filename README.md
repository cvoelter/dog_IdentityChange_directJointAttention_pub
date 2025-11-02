# Identity-change Experiment with Dogs: Direct (1st Person) Joint Attention

This repository contains data, analysis scripts, functions, and outputs for the eye-tracking study entitled  
**"Joint attention biases dogs’ memory towards object identity."**

---

## 📁 Repository Structure

```
.
├── 01_Dog_Identity_Change_Exp1_dwell_time_analysis.rmd
├── 02_Dog_Identity_Change_Exp1_sample_report_analysia.rmd
├── 03_Dog_Identity_Change_Exp1_sample_report_pupillometry.rmd
├── README.md
├── dog_IdentityChange_directJointAttention_pub.Rproj
├── data/
│   ├── dog_identity_change_IA_report.txt
│   ├── dog_identity_change_counterbalancing_exp1.csv
│   ├── dog_object_change_downsampled_actionphase_samplereport.parquet
│   └── raw_data/      # Sample reports of each recording saved as parquet files
├── functions/
├── graphics/
├── saves/
│   ├── Table_S1_GAMM01.docx
│   ├── action_phase_gamm01.txt
│   ├── m1_firstlook_samplebased_outcome_table_final.csv
│   ├── m1_firstlookdwell_outcome_table_final.csv
│   ├── m1_latencyfirstfix_outcome_table_final.csv
│   ├── mm1_actionphase_actor_dwelltime_zscores_lmer_output_table.csv
│   ├── mm1_actionphase_target_dwelltime_zscores_lmer_output_table.csv
│   ├── mm1_dwelltime_zscores_lmer_output_table.csv
│   └── mm1_samplebased_lookingtime_zscores_lmer_output_table.csv
├── screenshots/
│   ├── com01.png, com02.png, com03.png
│   ├── ncom01.png, ncom02.png, ncom03.png
│   ├── outcome_identity.png
│   ├── outcome_location.png
│   └── outcome_no.png
└── workspaces/ #files not provided due to space limitations
```

---

## 📜 Description of Contents

### Analysis Scripts

- **01_Dog_Identity_Change_Exp1_dwell_time_analysis.rmd**  
  R Markdown script for analyzing dwell times (sum of fixations on objects/actors).

- **02_Dog_Identity_Change_Exp1_sample_report_analysia.rmd**  
  Script for analyzing sample report data, including interest area analyses from raw samples (while excluding blinks).

- **03_Dog_Identity_Change_Exp1_sample_report_pupillometry.rmd**  
  Script for pupillometry analyses, focusing on changes in pupil size during the action phase.

---

### Data

- **data/dog_identity_change_IA_report.txt**  
  Interest Area (IA) report summarizing fixation events.

- **data/dog_identity_change_counterbalancing_exp1.csv**  
  Spreadsheet with demographic and counterbalancing information.

- **data/dog_object_change_downsampled_actionphase_samplereport.parquet**  
  Preprocessed and downsampled sample report file, e.g., for pupil size analysis.

- **data/raw_data/**  
  Contains individual, raw Parquet files from each eye-tracking recording.

---

### Functions

- **functions/**  
  Custom R scripts for bootstrapping of CIs, model assumption checks, stability diagnostics, and helper functions, kindly provided by Dr. Roger Mundry. 

---

### Graphics

- **graphics/**  
  Generated plots and figures.

---

### `saves/`

Tables and model outputs from statistical analyses.

| File                                                             | Description                                                         |
| ---------------------------------------------------------------- | ------------------------------------------------------------------- |
| `m1_firstlook_samplebased_outcome_table_final.csv`               | Results of first-look at outcome (duration, sample-based) analysis. |
| `m1_firstlookdwell_outcome_table_final.csv`                      | Results of dwell time of first look at outcome analysis.            |
| `m1_latencyfirstfix_outcome_table_final.csv`                     | Results of latency to first fixation at outcome analyses.           |
| `mm1_actionphase_actor_dwelltime_zscores_lmer_output_table.csv`  | Results of actor-directed dwell time models (action phase).         |
| `mm1_actionphase_target_dwelltime_zscores_lmer_output_table.csv` | Results of object-directed dwell time models (action phase).        |
| `mm1_dwelltime_zscores_lmer_output_table.csv`                    | Results of dwell time at outcome analysis.                          |
| `mm1_samplebased_lookingtime_zscores_lmer_output_table.csv`      | Results of sample-based looking time at outcome analysis.           |

---


### `screenshots/`

Stimulus screenshots.

| Example Files                                                    | Description                                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------------------ |
| `com01.png`, `com02.png`, `com03.png`                            | Example frames of action phase of **communicative condition**.     |
| `ncom01.png`, `ncom02.png`, `ncom03.png`                         | Example frames of action phase of **non-communicative condition**. |
| `outcome_identity.png`, `outcome_location.png`, `outcome_no.png` | Example frames of outcome conditions.                              |


