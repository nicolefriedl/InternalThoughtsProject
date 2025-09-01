# Internal Thoughts Project
Quantitative psychology study examining internal thought patterns using survey data and Principal Component Analysis. Explores overthinking, emotional regulation, and self-talk through 17-item Likert scale with 115 participants.

# Research Question
What are the underlying dimensions of internal thought and emotional processing, as reflected in participants' responses to self-reflective introspective statements?
Methodology

# Survey Design: 17 conversational Likert-scale items (1-5 scale)
Participants: 115 recruited via Prolific (105 retained after data cleaning)
Platform: Qualtrics for survey administration
Analysis: Python with pandas, statistical analysis, and Principal Component Analysis

# Key Findings

Identified dominant rumination factor underlying diverse thought patterns
Highest agreement with planning behaviors and memory recall (means: 4.36 and 4.05)
Strong factor loadings for items related to "rehearsing arguments" and "existential doubt"
Single principal component explains primary variance in self-reported experiences

# Technical Implementation
Data Collection

# Anonymous online survey via Prolific platform
Rigorous data cleaning (removed participants with >3 missing responses)
Quality control maintaining 91% retention rate

# Statistical Analysis

Exploratory Data Analysis (EDA)
Principal Component Analysis (PCA)
Correlation matrix analysis
Factor loading interpretation

# Tools Used

Python: pandas, numpy, matplotlib, seaborn
Survey Platform: Qualtrics
Recruitment: Prolific
Documentation: Jupyter Notebooks

# Repository Structure
├── data/
│   ├── raw_survey_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_principal_components.ipynb
├── results/
│   ├── summary_statistics.csv
│   ├── correlation_matrix.png
│   └── pca_results.csv
├── docs/
│   ├── research_report.pdf
│   └── methodology.md
└── README.md

# Theoretical Framework
This research is grounded in:

Self-Perception Theory (Bem, 1967, 1972)
Emotional Self-Awareness models (Laird, 2007)
Contemporary research on rumination and cognitive patterns

# Implications
Clinical Applications

# Supports anxiety assessment approaches
Informs mindfulness intervention strategies
Contributes to behavioral therapy understanding

# Research Contributions

Demonstrates accessible survey design for complex psychological constructs
Establishes foundation for longitudinal studies of thought pattern stability
Provides psychometric validation for self-reflection measurement

# Future Directions

Longitudinal study to assess thought pattern stability over time
Demographic analysis with larger, more diverse sample
Test-retest reliability assessment
Integration with validated psychological scales

# Installation & Usage
bash# Clone repository
git clone https://github.com/[username]/internal-thought-patterns.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Run analysis notebooks
jupyter notebook notebooks/
Ethics & Privacy

All data collected anonymously
Participants compensated according to Prolific ethical guidelines
No personally identifiable information retained
Study conducted with attention to participant wellbeing
