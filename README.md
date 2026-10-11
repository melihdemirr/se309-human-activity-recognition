# <Project title>

**Course:** SE309 AI and Data Science for Innovation in Health Science · Fall 2026–27
**Topic code:** SE309-XX   ·   **Working as:** Individual / Group (n members)  
**Agreed extra feature(s):** <only for groups of 4–5>

<!--
HOW TO USE THIS TEMPLATE
- Keep this file as README.md in the root of your repository.
- Replace every <...> and every comment like this one. Delete these instructions when you are done.
- The README is required. It is checked at the interim report (Week 10) and at the final submission.
-->

## Members

| Name | Student no. | GitHub username |
|---|---|---|
| <Full name> | <number> | @<username> |
| <Full name> | <number> | @<username> |

## What the project does

<!-- 3–5 sentences: the problem, who would use the result, and what the project delivers. -->

## How to install and run

### Weka
1. Open Weka → Explorer → **Open file…** → `data/<file>.arff`.
2. Load the saved model: Classify tab → right-click the result list → **Load model** → `weka/<model>.model`.
3. Settings used: <!-- classifier, filters, test option -->

### Python / Colab
1. Open `notebooks/project.ipynb` in Google Colab (**File → Open notebook → GitHub**, paste this repository's URL).
2. **Runtime → Run all.** The notebook downloads or loads the data itself; no other step is needed.

## Example output

<!-- One screenshot, a short output, or the main result table. Put images in an `images/` folder:
![Main result](images/result.png) -->

## Data

| Dataset | Source (link) | Size | Licence / terms of use |
|---|---|---|---|
| <!-- e.g. Pima Indians Diabetes --> | <!-- URL --> | <!-- rows × columns --> | <!-- licence --> |

> Only public or properly released data is used. No real patient records, and no identifiable health data uploaded to online tools.

A short **data note** (who, why, when/where, label, missingness, impossible values, timing, consent) is in the report and in Section 2 of the notebook.

## Folder structure

```
├── README.md
├── data/                 # .arff / .csv files (or a script that downloads them)
├── weka/                 # saved models (.model) and result buffers (.txt)
├── notebooks/
│   └── project.ipynb     # main notebook (from the course template)
├── reports/
│   ├── interim_report.pdf
│   └── final_report.pdf
└── video.md              # link to the presentation video
```

## Who did what

<!-- Must match the commit history and the Contributions section of the report. -->

| Member | Main responsibilities | Main files / parts |
|---|---|---|
| @<username> | <!-- e.g. data cleaning, evaluation --> | <!-- e.g. src/clean.py, notebook §4 --> |
| @<username> |  |  |

Every member commits their own work from their own GitHub account.

## External code, libraries and AI tools

| What | Used for | Where |
|---|---|---|
| <!-- e.g. scikit-learn --> | <!-- model training --> | <!-- notebook §5 --> |
| <!-- e.g. an AI assistant --> | <!-- what exactly it was used for --> | <!-- files --> |

## Reports and video

- Interim report (Week 10): [`reports/interim_report.pdf`](reports/interim_report.pdf)
- Final report: [`reports/final_report.pdf`](reports/final_report.pdf)
- Presentation video: <link — added at the final; every member appears>
