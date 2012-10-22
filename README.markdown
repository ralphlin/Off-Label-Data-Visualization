# Off-Label drug use data visualization

October, 2012  
By Ralph Lin  

## Description:

This is a demo to dynamically visualize data using D3.js.  
  
Off-label drug prescriptions, which accounts for nearly 20% of prescriptions in the US, occurs when a drug is prescribed to treat a condition for which it is not FDA approved. When making decisions on off-label prescriptions, physicians often rely on previous experience, research studies, and practice guidelines for standards of care. However, keeping abreast of current findings is challenging and research findings are rarely conclusive. Moreover, other factors such as costs, patient coverage, marketing, and trends gathered from other doctors also influence decision-making.  
  
In order to better understand off-label prescription patterns, we examined data from the AHRQ Medical Expenditures Panel Survey, a longitudinal survey of nearly 30,000 Americans. This data includes over 3.7 million records of inpatient, outpatient and ER visits with prescription data and associated medical conditions over the period of 1996-2009. We processed, aggregated and linked this data across multiple years, patients, and drug name equivalents, applying textual analysis and other filtering methods to analyze off-label drug use by three-digit and top-level ICD-9 medical condition codes. In addition, we have conducted aggregations of ICD-9 condition codes associated with various heart conditions, pain disorders, and other categories in order to aid visualizing, browsing and interpreting this data.  
  
We present the results of our analysis with three illustrative examples -- Metoprolol, Cymbalta, and Methadone -- chosen based on recent publications and interest. However, our aggregated data set and analytics engine permits analogous analyses by condition codes for over 2,000 medications. We are able to use our analytics engine to examine relative and absolute rankings of prescriptions, view filled drug prescription trends over time, and investigate condition/drug pairing time series. In the future, this data may allow us to build powerful clinical tools such as near real-time identification of emerging off-label uses of drugs in different communities.  

## Notes:
** work in progress
