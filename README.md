# Analysis of patient reported safety incidents in online feedback
The Python Jupyter notebook '[patientReportedIncidents.ipynb](https://github.com/473x/safetyIncidents_analysis/blob/main/patientReportedIncidents.ipynb)' reports an analysis of patient feedback on acute NHS trusts (hospital conglomerates). The aim of the analysis is to create a natural language processing algorithm that can estimate the likelihood that online patient feedback reports a safety incident. The notebook documents all the stages of the analysis and the outputs at each stage. 

A demonstration of the final algorithm is available [here](https://tinyurl.com/safetyIncidentsDemo) (note: this can take up to 10 minutes to load). Although the raw data used in the analysis cannot be hosted here, it is publicly available. The feedback data is from [Care Opinion](https://www.careopinion.org.uk/) and the secondary data is from [NHS Digital](https://digital.nhs.uk/) (more detail in the 'dataSources.pdf' file). The manually coded data, used to validate the automated methodology, is in the file 'data_manualClassifications.xlsx' (the instructions for how the data was manually classified are in 'guidelinesForManualClassification.pdf'). 
