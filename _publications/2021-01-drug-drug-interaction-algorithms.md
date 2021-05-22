---
title: "Designing and evaluating contextualized drug–drug interaction algorithms"
collection: publications
permalink: /publication/2021-01-drug-drug-interaction-algorithms
excerpt: 'Alert fatigue is a common issue with off-the-shelf clinical decision support. Most warnings for drug–drug interactions (DDIs) are overridden or ignored, likely because they lack relevance to the patient’s clinical situation. Existing alerting systems for DDIs are often simplistic in nature or do not take the specific patient context into consideration, leading to overly sensitive alerts. The objective of this study is to develop, validate, and test DDI alert algorithms that take advantage of patient context available in electronic health records (EHRs) data.'
date: 2021-01
venue: 'JAMIA Open'
paperurl: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7976224/'
---
## Abstract

### Objective
Alert fatigue is a common issue with off-the-shelf clinical decision support. Most warnings for drug–drug interactions (DDIs) are overridden or ignored, likely because they lack relevance to the patient’s clinical situation. Existing alerting systems for DDIs are often simplistic in nature or do not take the specific patient context into consideration, leading to overly sensitive alerts. The objective of this study is to develop, validate, and test DDI alert algorithms that take advantage of patient context available in electronic health records (EHRs) data.

### Methods

Data on the rate at which DDI alerts were triggered but for which no action was taken over a 3-month period (override rates) from a single tertiary care facility were used to identify DDIs that were considered a high-priority for contextualized alerting. A panel of DDI experts developed algorithms that incorporate drug and patient characteristics that affect the relevance of such warnings. The algorithms were then implemented as computable artifacts, validated using a synthetic health records data, and tested over retrospective data from a single urban hospital.

### Results
Algorithms and computable knowledge artifacts were developed and validated for a total of 8 high priority DDIs. Testing on retrospective real-world data showed the potential for the algorithms to reduce alerts that interrupt clinician workflow by more than 50%. Two algorithms (citalopram/QT interval prolonging agents, and fluconazole/opioid) showed potential to filter nearly all interruptive alerts for these combinations.

### Conclusion
The 8 DDI algorithms are a step toward addressing a critical need for DDI alerts that are more specific to patient context than current commercial alerting systems. Data commonly available in EHRs can improve DDI alert specificity.