# Masters
Masters Project code

RESEARCH PROBLEM
Some individuals interact with behaviours or substances that lead them to become addicted. This study aimed to examine whether AUD can be used to predict GD in the
study populations/selected datasets.

MAIN RESEARCH QUESTION AND HYPOTHESIS
The main research question posed for this study is: Can PRS for alcohol dependence calculated in a discovery dataset be used to predict gambling disorder in a target
dataset?

STUDY DESIGN
This study followed a quantitative methodological approach, which focuses on testing theories and measuring the relationship between variables of interest. It is centred around a hypothesis statement or primary research question and aims to prove or disprove the statement or definitively answer the question.

METHODS OF DATA COLLECTION
Data was collected for this study from the National Epidemiological Survey on Alcohol and Related Conditions-III (NESARC: https://www.ncbi.nlm.nih.gov/projects/gap/cgibin/
study.cgi?study_id=phs001590.v2.p1) and the Alcohol Dependence GWAS in European and African Americans (https://www.ncbi.nlm.nih.gov/projects/gap/cgibin/
study.cgi?study_id=phs000425.v1.p1) datasets.

METHODS OF DATA ANALYSIS
There were numerous different analysis techniques/tools used in this study, with the focus being on data reduction techniques. Dimensional reduction of data can be
achieved by finding a smaller set of variables that are within the study data that contain the same information as the input variables. When looking at a
dataset, exploratory data analysis (EDA) is used to better understand the data, and EDA is achieved by applying various operations to the data, with the outcome allowing
the researcher to decide on the next course of action.

DATA REDUCTION TECHNIQUES
The first technique used was Principal Component Analysis (PCA). 
Multidimensional Scaling (MDS) is a statistical tool used to reduce dimensions in data during exploratory analysis.
While PCA and MDS are linear reduction techniques, a third reduction technique was used, namely Isometric Feature Mapping (ISOMAP). 

Run through a GWAS pipeline. 

POLYGENIC RISK SCORES AND MODELS
SNPs identified from the GWAS of the alcohol dependence and NESARC datasets were used to create PRS with the PRSice software. Once these scores were obtained, they were then entered in a logistic regression model, with sex
and age as covariates. The model was trained with the PRS from the NESARC training dataset and was then used to predict alcohol dependence. The NESARC dataset, that
contained PRS, sex, age and alcohol dependence data, was split into 80:20, for the training and test sets respectively. After the training of the model, it was then used to
predict alcohol dependence in the NESARC test dataset. After alcohol dependence had been predicted, the test set was then used to see where the actual alcohol
dependence and predicted alcohol dependence correlated.
