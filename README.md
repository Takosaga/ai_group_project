# Image Recongnition to Detect Different Vehicle Types in Riga

This project focuses on training a model for accurate vehicle identification and classification within Riga, Latvia. The model is trained to recognize and categorize the following vehicle types:

*   **V (Passenger Vehicles):** This category includes standard cars used for personal transportation. Passenger vehicles represent a significant portion of traffic and provide a valuable baseline for comparison with other vehicle types.
*   **C (Cargo Vehicles):** This encompasses all commercial vehicles, from smaller vans (C1) to large trucks with trailers (C4). Tracking cargo vehicles is crucial due to their larger size and lower speeds, which can contribute to increased traffic congestion.
*   **S (Buses):** This category specifically targets public transport buses. Monitoring buses is essential for understanding their impact on traffic flow and public transportation schedules.
<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

[Group Proposal](https://github.com/Takosaga/ai_group_project/blob/main/references/Project_Proposal_Final_Draft.pdf)

[Kanban Board of project](https://github.com/users/Takosaga/projects/2)

[Very general progress notes](https://github.com/Takosaga/ai_group_project/blob/main/references/Discussion_Meeting_Progress%20Notes.pdf)

## Team Roles

| Name | Title | Roles |
|---|---|---|
| Dmitrijs | Data Engineer | Business Understanding, Data Preparation, Modelling, Test & Validate |
| Eden | Data Analyst | Business Understanding, Data Understanding, Modelling, Communication of Insights |
| Gonzalo | Project Manager | Management, Support |

## Project Timeline

| Week | Task/Deliverable | Responsible |
|---|---|---|
| 1 | Project requirements | Dmitrijs, Eden, Gonzalo |
| 2 | Data collection, data exploration | Dmitrijs, Eden |
| 3 | Data annotation, data formatting | Dmitrijs, Eden, Gonzalo |
| 4 | Model training and evaluation | Dmitrijs, Eden |
| 5 | Model improvement and tuning | Dmitrijs, Eden |
| 6 | Model testing with new data | Dmitrijs, Eden |
| 7 | Final Model adjustments and validation | Dmitrijs, Eden |
| 8 | Final presentation | Dmitrijs, Eden, Gonzalo |

[Detailed timeline and assigned responsibilities](https://github.com/users/Takosaga/projects/2/views/4)

## Project Organization


```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         ai_group_project and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── project_packages   <- Source code for use in this project.
    │
    └── __init__.py             <- Makes ai_group_project a Python module
```

--------

