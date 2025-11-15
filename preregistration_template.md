# Preregistration: An Empirical Study on Passive Music Listening Experiences in Childhood and Episodic Memory

## —Through a Questionnaire Survey on the "Parent's Car Theory"—

**Author**: YusukeMiyamaru  
**Date of Registration**: 2025  
**Registry**: OSF (Open Science Framework) / PsyArXiv  
**Status**: Preprint (Post-hoc Preregistration for Transparency)

---

## 1. Research Question

**Primary Research Question**:  
When and how are individual musical preferences formed? Specifically, does the "Parent's Car Theory"—a colloquially discussed phenomenon suggesting that music heard in parents' cars during childhood influences later musical preferences—have empirical validity?

**Secondary Research Questions**:
1. What psychological mechanisms underlie the "Parent's Car Theory"?
2. How do childhood passive listening experiences contribute to musical preference formation?
3. What role does the unique car interior environment play in memory formation and preference development?

---

## 2. Hypotheses

### Hypothesis 1: Mere-Exposure Effect
**Prediction**: The more opportunities children had to listen to music in their parents' cars, the greater the influence on their current musical preferences.

**Rationale**: Based on the mere-exposure effect (Zajonc, 1968), repeated passive exposure to music in childhood should increase familiarity and preference, even without active selection.

**Operationalization**:  
- Independent Variable: Frequency of riding in cars during childhood (ordinal: "daily," "several times a week," "several times a month," "almost never")
- Dependent Variable: Degree of influence on current musical preferences (5-point scale: "very much" to "not at all")

**Statistical Analysis**: Spearman's rank correlation analysis between frequency and influence degree.

### Hypothesis 2: Classical Conditioning
**Prediction**: The more positive children's feelings toward the music they heard and the music selectors (parents, etc.), the greater the influence on their current musical preferences.

**Rationale**: Based on classical conditioning theory, positive emotional associations formed during family drives should strengthen the connection between music and positive emotions.

**Operationalization**:  
- Independent Variable: Emotional scores from childhood (5-point scale for "favorability toward music at that time" and "feelings toward music selectors")
- Dependent Variable: Degree of influence on current musical preferences (dichotomized: "high influence group" vs. "low influence group")

**Statistical Analysis**: Independent samples t-test (Welch's t-test) and Mann-Whitney U test for group comparisons. Logistic regression for multivariate analysis controlling for age, gender, music interest, and frequency.

### Hypothesis 3: Context-Dependent Memory
**Prediction**: Listening experiences in a car—a closed, private space—are more likely to remain in memory and have a stronger influence on preference formation than listening experiences through other media such as television or radio.

**Rationale**: Based on context-dependent memory theory (Godden & Baddeley, 1975), the unique multimodal context of car interiors (visual, physical, social, emotional) should create stronger episodic memories.

**Operationalization**:  
- Dependent Variable: Comparison of memory vividness between car and other environments (categorical: "car memories are more memorable," "both are equally memorable," "other locations are more memorable")

**Statistical Analysis**: Binomial test and chi-squared test to examine whether car memories are significantly more memorable than other environments.

### Hypothesis 4: Schema Theory
**Prediction**: There is a relationship between the music genres heard during childhood and current preferred genres.

**Rationale**: Based on schema theory, repeated exposure to specific musical styles in childhood should form "musical schemas" that guide future preference formation.

**Operationalization**:  
- Independent Variable: Artists heard in cars during childhood (free-text responses)
- Dependent Variable: Current preferred music genres (free-text responses)
- Analysis: Co-occurrence analysis using text mining to identify relationships between past artists and current genres

**Statistical Analysis**: Chi-squared test for association. Effect size measured using Cramér's V and odds ratio.

---

## 3. Study Design

### Research Type
- **Cross-sectional study** using web-based questionnaire survey
- **Exploratory analysis** for preliminary verification
- **Preprint status**: Preliminary findings requiring larger-scale validation

### Data Collection Method
- **Platform**: Web-based questionnaire survey
- **Sampling**: Convenience sampling (self-selected participants)
- **Target Population**: Adults who experienced childhood in the 1990s-2000s (age range: approximately 20-55 years)
- **Inclusion Criteria**: 
  - Adults who had experiences riding in cars with family during childhood
  - Ability to recall childhood music listening experiences
- **Exclusion Criteria**:
  - No childhood experiences in cars
  - Incomplete responses

### Data Collection Period
Data collection was conducted in 2025. (Specific dates to be documented)

---

## 4. Variables

### Demographic Variables
- Age (continuous)
- Gender (categorical: male, female, other)
- Age group (categorical: 20s, 30s, 40s, 50s)

### Musical Background Variables
- Current level of interest in music (5-point scale)
- Favorite music genres (free-text)
- Age when actively began listening to music (continuous)

### Childhood Car Experience Variables
- Frequency of riding in cars with family (ordinal: daily, several times a week, several times a month, almost never)
- Frequency of music playing in cars (ordinal)
- Who selected music (categorical: parent, self, siblings, etc.)
- Artists frequently played at that time (free-text)

### Emotional/Memory Variables
- Favorability toward music at that time (5-point scale)
- Feelings toward music selectors at that time (5-point scale)
- Current favorability toward that music (5-point scale)
- Memory vividness comparison: car vs. other environments (categorical)

### Outcome Variable
- Degree of influence on current musical preferences (5-point scale: "very much" to "not at all")
- Dichotomized for analysis: "high influence group" ("very much," "somewhat") vs. "low influence group" ("not much," "not at all")

### Exploratory Variables
- Temporal change in favorability (paired scores: then vs. now)
- Influence by music selector
- Relationship between age when music listening began and influence degree

---

## 5. Analysis Plan

### Primary Analyses

#### Hypothesis 1: Mere-Exposure Effect
1. **Descriptive Statistics**: Frequency distribution of car riding frequency and influence degree
2. **Correlation Analysis**: Spearman's rank correlation between frequency and influence degree
3. **Group Comparison**: High-frequency group (daily + several times a week) vs. Low-frequency group (several times a month + almost never)
   - Odds ratio (OR) with 95% confidence intervals
   - Number Needed to Treat (NNT)
   - Effect size: Cramér's V
4. **Subgroup Analysis**: Age-group stratified analysis
5. **Threshold Effect Analysis**: Comparison between "daily" and "several times a week" groups

#### Hypothesis 2: Classical Conditioning
1. **Descriptive Statistics**: Mean emotional scores by influence group
2. **Group Comparison**: Independent samples t-test (Welch's t-test) for "favorability toward music at that time"
3. **Non-parametric Test**: Mann-Whitney U test
4. **Effect Size**: Cohen's d with 95% confidence intervals
5. **Multivariate Analysis**: Logistic regression controlling for age, gender, music interest, and frequency
6. **Interaction Effects**: Analysis of interaction between favorability toward music and feelings toward selectors

#### Hypothesis 3: Context-Dependent Memory
1. **Descriptive Statistics**: Frequency distribution of memory vividness comparison
2. **Statistical Test**: Binomial test to examine whether car memories are significantly more memorable
3. **Chi-squared Test**: Association between memory vividness categories
4. **Effect Size**: Odds ratio for car vs. other environments

#### Hypothesis 4: Schema Theory
1. **Text Mining**: Extraction of artists and genres from free-text responses
2. **Normalization**: Standardization of artist names and genre categories
3. **Co-occurrence Analysis**: Calculation of co-occurrence frequency between past artists and current genres
4. **Statistical Test**: Chi-squared test for association
5. **Effect Size**: Cramér's V and odds ratio

### Exploratory Analyses

1. **Temporal Change Analysis**: 
   - Paired-samples t-test for favorability change (then vs. now)
   - Pearson correlation between then and now scores
   - Scatter plot visualization by influence group

2. **Music Selector Influence Analysis**:
   - Comparison of positive response rates by selector (parent, self, siblings)
   - Bar chart visualization

3. **Age and Influence Relationship**:
   - Pearson correlation between age when music listening began and influence degree
   - Scatter plot with regression line

4. **Advanced Text Mining**:
   - Morphological analysis (Japanese)
   - TF-IDF analysis
   - Word cloud generation
   - Keyword extraction

### Statistical Software and Methods
- **Software**: Python 3.x
- **Libraries**: pandas, numpy, scipy, matplotlib, seaborn, scikit-learn, wordcloud, janome
- **Statistical Tests**: 
  - Parametric: t-tests, Pearson correlation, linear regression
  - Non-parametric: Spearman's rank correlation, Mann-Whitney U test, Kruskal-Wallis H-test
  - Effect Sizes: Cohen's d, Cramér's V, Odds Ratio, NNT
  - Multivariate: Logistic Regression

### Interpretation Criteria
- **Statistical Significance**: p < 0.05 (two-tailed)
- **Marginal Significance**: p < 0.10 (reported as trends)
- **Effect Size Interpretation**:
  - Cohen's d: Small (0.2), Medium (0.5), Large (0.8)
  - Cramér's V: Small (0.1), Medium (0.3), Large (0.5)
- **Practical Importance**: Evaluated using odds ratio, NNT, and confidence intervals even when statistical significance is not achieved

---

## 6. Sample Size

### Target Sample Size
- **Initial Target**: 50-100 participants
- **Actual Sample Size**: 57 valid respondents

### Sample Size Justification
- **Preliminary Study**: This is a preliminary verification (preprint)
- **Exploratory Nature**: Primary goal is to explore potential effects rather than confirmatory testing
- **Power Analysis**: Post-hoc power analysis will be conducted for future studies
- **Recommendation**: Larger sample size (n ≈ 200-300) recommended for confirmatory studies

---

## 7. Data Collection

### Questionnaire Structure
The questionnaire consists of five main categories:

1. **Musical Background of Respondents**
   - Current level of interest in music
   - Favorite music genres
   - Age when actively began listening to music

2. **Musical Experiences in Cars during Childhood**
   - Frequency of riding in cars with family
   - Frequency of music playing in cars
   - Who selected music
   - Artists frequently played at that time

3. **Evaluation of Memories and Emotions**
   - Favorability toward music at that time (5-point scale)
   - Feelings toward music selectors at that time (5-point scale)
   - Current favorability toward that music (5-point scale)
   - Whether music evokes scenes or moods (episodic memory)

4. **Relationship with "Parent's Car Theory"**
   - Self-assessment of influence on current preferences (5-point scale)

5. **Comparison with Other Listening Environments**
   - Other music listening environments that had influence
   - Memory vividness comparison: car vs. other environments

### Data Collection Procedure
1. Participants accessed the web-based questionnaire
2. Informed consent was obtained (implied by participation)
3. Responses were collected anonymously
4. Data were stored securely

---

## 8. Planned Timeline

### Phase 1: Data Collection
- **Duration**: 2025 (Specific period to be documented)
- **Activities**: Questionnaire distribution and data collection

### Phase 2: Data Analysis
- **Duration**: 2025 (Specific period to be documented)
- **Activities**: 
  - Data cleaning and preprocessing
  - Hypothesis testing
  - Exploratory analyses
  - Figure generation

### Phase 3: Manuscript Preparation
- **Duration**: 2025 (Specific period to be documented)
- **Activities**:
  - Results interpretation
  - Manuscript writing
  - Figure refinement
  - Reference formatting

### Phase 4: Preprint Submission
- **Target**: PsyArXiv / OSF
- **Status**: Submitted in 2025 (Specific date to be documented)

---

## 9. Deviations from Original Plan

### Note on Post-hoc Preregistration
This preregistration is being created **after** data collection and analysis have been completed. This is a **post-hoc preregistration** for transparency purposes, documenting the research plan as it was actually executed.

### Key Deviations (if any)
- Analysis methods were refined during the analysis process
- Exploratory analyses were added beyond the original hypotheses
- No major deviations from the core research plan

### Transparency Measures
- All analysis scripts are available in the `analysis/` directory
- Standardized analysis process is documented in `format/標準化分析プロセス.md`
- All figures are generated from reproducible scripts
- Data preprocessing steps are documented

---

## 10. Data and Materials Sharing

### Data Availability
- **Data File**: `data.csv`
- **Sharing Policy**: Available for research purposes under Creative Commons Attribution 4.0 International Public License (CC BY 4.0)
- **Anonymization**: All personal identifiers removed

### Analysis Scripts Availability
- **Location**: `analysis/` directory
- **Scripts Include**:
  - `chapter2_analysis.py`: Demographic figures
  - `chapter3_analysis.py`: Hypothesis testing figures
  - `hypothesis1_*.py`: Hypothesis 1 analyses (basic, critical, improved, exploratory, integrated)
  - `hypothesis2_*.py`: Hypothesis 2 analyses
  - `hypothesis3_*.py`: Hypothesis 3 analyses
  - `hypothesis4_*.py`: Hypothesis 4 analyses
  - `exploratory_analysis.py`: General exploratory analyses
  - `comprehensive_integrated_analysis.py`: Comprehensive integration

### Documentation Availability
- **Standardized Analysis Process**: `format/標準化分析プロセス.md`
- **Style Guide**: `format/論文文体ルールチェックシート.md`
- **Figure Creation Guidelines**: `format/図表作成観点.md`

### Reproducibility
- All analysis scripts are executable and reproducible
- Figure generation scripts are documented
- Data preprocessing steps are standardized

---

## 11. Ethical Considerations

### Informed Consent
- Participants were informed about the research purpose
- Participation was voluntary
- Anonymity was maintained

### Data Protection
- All personal identifiers were removed
- Data are stored securely
- Data sharing is limited to research purposes

### Ethical Approval
- Ethical approval was obtained through the standard procedures for questionnaire-based research
- All participants provided informed consent (implied by participation)
- Data collection and handling procedures followed ethical guidelines for research involving human participants

---

## 12. Funding and Conflicts of Interest

### Funding
- This research was conducted without external funding
- Self-funded research project

### Conflicts of Interest
- No conflicts of interest to declare

---

## 13. Registration Information

### Registry
- **Platform**: OSF (Open Science Framework) / PsyArXiv
- **Registration Date**: 2025
- **Registration Type**: Post-hoc Preregistration (for transparency)
- **Status**: Preprint

### Links
- **OSF Project**: To be added when available
- **PsyArXiv Preprint**: To be added when available
- **GitHub Repository**: https://github.com/SoundLaboratory/SLResearch_PARENT-S-CAR-THEORY

---

## 14. Contact Information

**Principal Investigator**: YusukeMiyamaru  
**Email**: Contact through GitHub Issues or Pull Requests  
**Institution**: Sound Laboratory

---

## Notes

1. **Preprint Status**: This is a preliminary preprint. Findings are tentative and require larger-scale validation.

2. **Post-hoc Preregistration**: This preregistration was created after data collection and analysis to document the research plan as executed. While not a true prospective preregistration, it serves transparency purposes.

3. **Future Research**: Larger sample sizes (n ≈ 200-300) and longitudinal studies are recommended for confirmatory validation.

4. **Open Science**: All analysis scripts, data preprocessing steps, and documentation are available for reproducibility.

---

**Last Updated**: 2025  
**Version**: 1.0

