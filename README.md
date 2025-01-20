# Medical_Transcriptions
Exploring Tool Calls in Data Camp to Extract Structured Information from Medical Transcriptions. 

I created this code to read a .csv file containing unstructured medical notes from patients. 
To make the information more useful, I used the chat completions API with the tool calls functionality to create a strategy to output structured data formats for the medical transcriptions. 
The fields to output included:
- Age of the patient
- A more concise summary of the treatment for the patient
- Category of treatment
- ICD code (standard taxonomy to be able to map these to a database of treatments).
- https://icd.who.int/browse10/2019/en (International Statistical Classification of Diseases and Related Health Problems 10th Revision)
