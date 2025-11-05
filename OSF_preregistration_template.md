# OSF Preregistration Template
## An Empirical Study on Passive Music Listening Experiences in Childhood and Episodic Memory

**Author**: YusukeMiyamaru  
**Registration Date**: [Date]  
**Status**: Post-hoc Preregistration (for transparency)  
**Preprint**: [Link to PsyArXiv/OSF preprint]

---

## 1. Research Design Classification

### Research Type
- ☐ Confirmatory (Hypothesis Testing)
- ☐ Exploratory (Hypothesis Generating)
- ☑ **Both** (This study includes both confirmatory hypothesis testing and exploratory analyses)

### Study Type
- ☑ **Cross-sectional study**
- ☐ Longitudinal study
- ☐ Experimental study
- ☐ Mixed methods

### Data Collection Status
- ☐ **Data collection has not begun**
- ☐ **Data collection is ongoing**
- ☑ **Data collection is complete** (Post-hoc preregistration for transparency)

---

## 2. Research Question

### Primary Research Question
When and how are individual musical preferences formed? Specifically, does the "Parent's Car Theory"—a colloquially discussed phenomenon suggesting that music heard in parents' cars during childhood influences later musical preferences—have empirical validity?

### Secondary Research Questions
1. What psychological mechanisms underlie the "Parent's Car Theory"?
2. How do childhood passive listening experiences contribute to musical preference formation?
3. What role does the unique car interior environment play in memory formation and preference development?

---

## 3. Hypothesis

### Hypothesis 1: Mere-Exposure Effect
**Prediction**: The more opportunities children had to listen to music in their parents' cars, the greater the influence on their current musical preferences.

**Rationale**: Based on the mere-exposure effect (Zajonc, 1968), repeated passive exposure to music in childhood should increase familiarity and preference.

**Variables**:
- **Independent Variable**: Frequency of riding in cars during childhood (ordinal: daily, several times a week, several times a month, almost never)
- **Dependent Variable**: Degree of influence on current musical preferences (5-point scale: "very much" to "not at all")

**Analysis Plan**:
- Spearman's rank correlation analysis
- Group comparison: High-frequency vs. Low-frequency groups
- Effect sizes: Odds ratio, NNT, Cramér's V

### Hypothesis 2: Classical Conditioning
**Prediction**: The more positive children's feelings toward the music they heard and the music selectors (parents, etc.), the greater the influence on their current musical preferences.

**Rationale**: Based on classical conditioning theory, positive emotional associations formed during family drives should strengthen the connection between music and positive emotions.

**Variables**:
- **Independent Variable**: Emotional scores from childhood (5-point scale for "favorability toward music at that time" and "feelings toward music selectors")
- **Dependent Variable**: Degree of influence (dichotomized: high vs. low influence group)

**Analysis Plan**:
- Independent samples t-test (Welch's t-test)
- Mann-Whitney U test
- Effect size: Cohen's d
- Logistic regression (multivariate analysis)

### Hypothesis 3: Context-Dependent Memory
**Prediction**: Listening experiences in a car—a closed, private space—are more likely to remain in memory and have a stronger influence on preference formation than listening experiences through other media such as television or radio.

**Rationale**: Based on context-dependent memory theory (Godden & Baddeley, 1975), the unique multimodal context of car interiors should create stronger episodic memories.

**Variables**:
- **Dependent Variable**: Comparison of memory vividness between car and other environments (categorical: "car memories are more memorable," "both are equally memorable," "other locations are more memorable")

**Analysis Plan**:
- Binomial test
- Chi-squared test
- Effect size: Odds ratio

### Hypothesis 4: Schema Theory
**Prediction**: There is a relationship between the music genres heard during childhood and current preferred genres.

**Rationale**: Based on schema theory, repeated exposure to specific musical styles in childhood should form "musical schemas" that guide future preference formation.

**Variables**:
- **Independent Variable**: Artists heard in cars during childhood (free-text)
- **Dependent Variable**: Current preferred music genres (free-text)

**Analysis Plan**:
- Text mining: Co-occurrence analysis
- Chi-squared test
- Effect sizes: Cramér's V, Odds ratio

---

## 4. Sampling Plan

### Existing Data
- ☑ **Yes, this study involves analysis of existing data**
- ☐ No, new data will be collected

### Sample Size
- **Target Sample Size**: 50-100 participants
- **Actual Sample Size**: 57 valid respondents

### Sample Size Rationale
- **Preliminary Study**: This is a preliminary verification (preprint)
- **Exploratory Nature**: Primary goal is to explore potential effects
- **Power Analysis**: Post-hoc power analysis will be conducted for future studies
- **Recommendation**: Larger sample size (n ≈ 200-300) recommended for confirmatory studies

### Sampling Method
- **Type**: Convenience sampling (self-selected participants)
- **Target Population**: Adults who experienced childhood in the 1990s-2000s (age range: approximately 20-55 years)

### Inclusion/Exclusion Criteria
**Inclusion**:
- Adults who had experiences riding in cars with family during childhood
- Ability to recall childhood music listening experiences

**Exclusion**:
- No childhood experiences in cars
- Incomplete responses

---

## 5. Variables

### Outcome Variable(s)
- **Primary Outcome**: Degree of influence on current musical preferences (5-point scale: "very much" to "not at all")
- **Secondary Outcomes**:
  - Memory vividness comparison (categorical)
  - Co-occurrence between past artists and current genres

### Predictor Variable(s)
- Frequency of riding in cars during childhood (ordinal)
- Emotional scores from childhood (continuous, 5-point scale)
- Memory vividness comparison (categorical)
- Artists heard in cars during childhood (free-text)

### Covariates
- Age (continuous)
- Gender (categorical)
- Current level of interest in music (5-point scale)
- Age when actively began listening to music (continuous)

---

## 6. Analysis Plan

### Statistical Analysis Plan

#### Hypothesis 1
1. **Descriptive Statistics**: Frequency distribution
2. **Correlation Analysis**: Spearman's rank correlation
3. **Group Comparison**: High-frequency vs. Low-frequency groups
   - Odds ratio (OR) with 95% CI
   - Number Needed to Treat (NNT)
   - Effect size: Cramér's V
4. **Subgroup Analysis**: Age-group stratified analysis

#### Hypothesis 2
1. **Descriptive Statistics**: Mean emotional scores by group
2. **Group Comparison**: Independent samples t-test (Welch's t-test)
3. **Non-parametric Test**: Mann-Whitney U test
4. **Effect Size**: Cohen's d with 95% CI
5. **Multivariate Analysis**: Logistic regression controlling for covariates

#### Hypothesis 3
1. **Descriptive Statistics**: Frequency distribution
2. **Statistical Test**: Binomial test
3. **Chi-squared Test**: Association between categories
4. **Effect Size**: Odds ratio

#### Hypothesis 4
1. **Text Mining**: Co-occurrence analysis
2. **Normalization**: Standardization of artist names and genre categories
3. **Statistical Test**: Chi-squared test
4. **Effect Size**: Cramér's V and odds ratio

### Exploratory Analyses
1. Temporal change analysis (paired-samples t-test, correlation)
2. Music selector influence analysis
3. Age and influence relationship (correlation, regression)
4. Advanced text mining (morphological analysis, TF-IDF, word cloud)

### Software
- **Python 3.x**
- **Libraries**: pandas, numpy, scipy, matplotlib, seaborn, scikit-learn, wordcloud, janome

### Interpretation Criteria
- **Statistical Significance**: p < 0.05 (two-tailed)
- **Marginal Significance**: p < 0.10 (reported as trends)
- **Effect Size Interpretation**:
  - Cohen's d: Small (0.2), Medium (0.5), Large (0.8)
  - Cramér's V: Small (0.1), Medium (0.3), Large (0.5)
- **Practical Importance**: Evaluated using odds ratio, NNT, and confidence intervals

---

## 7. Data Collection Procedures

### Data Collection Method
- **Platform**: Web-based questionnaire survey
- **Sampling**: Convenience sampling
- **Data Collection Period**: [Specify actual period]

### Questionnaire Structure
1. Musical Background of Respondents
2. Musical Experiences in Cars during Childhood
3. Evaluation of Memories and Emotions
4. Relationship with "Parent's Car Theory"
5. Comparison with Other Listening Environments

---

## 8. Data Preparation and Cleaning

### Data Cleaning Steps
1. Removal of incomplete responses
2. Handling of missing values
3. Standardization of free-text responses
4. Normalization of artist names and genre categories (for Hypothesis 4)

### Exclusion Criteria
- Responses with missing critical variables
- Responses indicating no childhood car experiences

---

## 9. Confirmatory Analysis Plan

### Primary Confirmatory Analyses
- Hypothesis 1: Spearman's rank correlation
- Hypothesis 2: Independent samples t-test
- Hypothesis 3: Binomial test
- Hypothesis 4: Chi-squared test

### Secondary Confirmatory Analyses
- Multivariate logistic regression (Hypothesis 2)
- Subgroup analyses
- Effect size calculations

### Exploratory Analyses
- Temporal change analysis
- Music selector influence analysis
- Age and influence relationship
- Advanced text mining

---

## 10. Data and Materials Sharing

### Data Availability
- **Data File**: `data/data.xlsx`
- **Sharing Policy**: Available for research purposes
- **Anonymization**: All personal identifiers removed

### Analysis Scripts
- **Location**: `analysis/` directory
- **Documentation**: `format/標準化分析プロセス.md`

### Documentation
- Standardized Analysis Process: `format/標準化分析プロセス.md`
- Style Guide: `format/論文文体ルールチェックシート.md`
- Figure Creation Guidelines: `format/図表作成観点.md`

---

## 11. Deviations from Plan

### Note on Post-hoc Preregistration
This preregistration is being created **after** data collection and analysis have been completed. This is a **post-hoc preregistration** for transparency purposes, documenting the research plan as it was actually executed.

### Key Deviations (if any)
- [Document any deviations from the original plan, if applicable]
- Analysis methods were refined during the analysis process
- Exploratory analyses were added beyond the original hypotheses

---

## 12. Ethical Considerations

### Informed Consent
- Participants were informed about the research purpose
- Participation was voluntary
- Anonymity was maintained

### Data Protection
- All personal identifiers were removed
- Data are stored securely
- Data sharing is limited to research purposes

### Ethical Approval
- [Specify if ethical approval was obtained and from which institution]

---

## 13. Funding and Conflicts of Interest

### Funding
- [Specify funding sources, if any]

### Conflicts of Interest
- [Specify any conflicts of interest, if any]

---

## 14. Additional Notes

1. **Preprint Status**: This is a preliminary preprint. Findings are tentative and require larger-scale validation.

2. **Post-hoc Preregistration**: This preregistration was created after data collection and analysis to document the research plan as executed.

3. **Future Research**: Larger sample sizes (n ≈ 200-300) and longitudinal studies are recommended.

4. **Open Science**: All analysis scripts, data preprocessing steps, and documentation are available for reproducibility.

---

**Last Updated**: [Date]  
**Version**: 1.0

