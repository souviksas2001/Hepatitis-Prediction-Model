# Hepatitis-Prediction-Model
The provided dataset comprises laboratory values of both blood donors and individuals diagnosed with Hepatitis C, along with demographic information such as age and sex. The data was sourced from the UCI Machine Learning Repository and can be accessed at: https://archive.ics.uci.edu/ml/datasets/HCV+data

The dataset contains various attributes, with most of them being numerical in nature. The attributes can be categorized as follows:

**Patient Information (Attributes 1-4):**
1. **X (Patient ID/No.):** A unique identifier for each patient in the dataset.
2. **Category (Diagnosis):** This attribute indicates the diagnosis or medical condition of the patient. The possible values are:
   - '0=Blood Donor': Represents individuals who are blood donors.
   - '0s=suspect Blood Donor': Denotes individuals who are suspected blood donors.
   - '1=Hepatitis': Indicates individuals diagnosed with Hepatitis C.
   - '2=Fibrosis': Represents individuals with fibrosis, which is a scarring of the liver tissue.
   - '3=Cirrhosis': Denotes individuals with cirrhosis, a more advanced stage of liver scarring.

3. **Age:** Represents the age of the patient in years.
4. **Sex:** Indicates the gender of the patient ('f' for female, 'm' for male).

**Laboratory Data (Attributes 5-14):**
5. **ALB:** Laboratory value related to albumin levels.
6. **ALP:** Laboratory value related to alkaline phosphatase levels.
7. **ALT:** Laboratory value related to alanine aminotransferase levels.
8. **AST:** Laboratory value related to aspartate aminotransferase levels.
9. **BIL:** Laboratory value related to bilirubin levels.
10. **CHE:** Laboratory value related to cholinesterase levels.
11. **CHOL:** Laboratory value related to cholesterol levels.
12. **CREA:** Laboratory value related to creatinine levels.
13. **GGT:** Laboratory value related to gamma-glutamyltransferase levels.
14. **PROT:** Laboratory value related to protein levels.

The target attribute for classification in this dataset is the 'Category' attribute (Attribute 2). The goal of classification is to distinguish between blood donors and individuals diagnosed with Hepatitis C, including those with varying stages of the disease's progression, such as fibrosis and cirrhosis.

In summary, this dataset provides a comprehensive set of numerical attributes, including patient information and laboratory values, that can be utilized for classification tasks involving the differentiation of blood donors from Hepatitis C patients and the assessment of disease progression. The dataset can be accessed using the link provided above.
