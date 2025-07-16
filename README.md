# externship-may-2025

🔍 Project Overview
This data analysis project was completed as part of the TripleTen externship program. The goal was to explore how student iteration behavior (i.e., number of attempts to complete homework) impacts future engagement and graduation likelihood.

We worked with anonymized educational data to answer questions like:

How many iterations does a typical student require per sprint?

Are high-iteration students more likely to disengage?

Does earning a diploma project correlate with higher iteration counts?

💡 Key Findings

Iteration Strain Predicts Dropoff: Students with 4+ iterations on a homework are significantly less likely to begin the next sprint.

Diploma Starters Persist: Diploma students are more likely to have lower iterations per project.

Low-Iteration Group Outperforms: Students completing projects in ≤3 iterations maintain the highest retention rates.

Data Science: Data science has the opposite trend where high-iteration students actually stay more engaged.

🧪 Methods Used

Grouping & Aggregation: Used pandas to segment students by iteration counts and diploma status.

Visualization: Created line plots, box plots, and bar charts using seaborn and matplotlib.

Statistical Testing: Welch’s t-test (scipy.stats) compared iteration counts between diploma and non-diploma students.

Key libraries used:

pandas

seaborn

matplotlib

scipy

tabulate
