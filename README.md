# v4

QUESTION:
Between Fall 2021 and Fall 2025 (time window), how did the freshman admit rate for Asian applicants at UC Santa Cruz (population of interest) change, measured in percentage point difference (metric being measured)?

Methodology
This project analyzes how the freshman admit rate for Asian applicants at UC Santa Cruz changed between Fall 2021 and Fall 2025. The analysis uses UC admissions data containing information on campus, fall term, entrant level, ethnicity, count type, and number of students.

The dataset was processed using Python and pandas. First, the data was filtered to include only freshman applicants, UC Santa Cruz, and the Asian ethnicity category. Applicant (App) and admit (Adm) counts were then separated by fall term so that an admission rate could be calculated for each year.

The freshman admit rate was calculated using:

Admit Rate = (Number of Admits ÷ Number of Applicants) × 100

To answer the research question, the Fall 2021 admit rate was compared with the Fall 2025 admit rate. The change was measured in percentage points, calculated as:

Percentage-Point Change = 2025 Admit Rate − 2021 Admit Rate

Using this method, the admit rate increased from 60.59% in Fall 2021 to 78.71% in Fall 2025, resulting in an increase of 18.12 percentage points.

This question is useful because it helps show how access to UC Santa Cruz changed over time for a specific group of applicants. By comparing the freshman admit rate for Asian applicants between Fall 2021 and Fall 2025, we can see whether admission became more or less selective for this population and whether the change happened gradually or varied from year to year.

The Streamlit dashboard also displays the annual admit-rate trend and compares applicant and admit counts to provide context for the change. Interactive year controls allow users to compare different years while keeping the population fixed to Asian freshman applicants at UC Santa Cruz, ensuring that the dashboard remains focused on the original research question.
