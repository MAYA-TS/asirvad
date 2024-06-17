CRF ID-123257,123738

Issue--There was a mandatory position for signatures of applicant,co-applicant etc in the loan document of asirvad micro finance.But majority of the se documents came in with empty signature positions which caused a lot of compliance issue.

Solution--The solution proposed was to implement a document checking using python to check whether a signature or line or any other writings is detected on the space provided for the signature

Method--The method used uses Google's Vision API for extracting the data from the loan document and writing the same into an excel file.After the writing ,we will check whether there any cells generated between the line above and line below of where the signature needed to be placed.After this process the whole checking needed to be converted into an API so that the checking can be used at the time of loan generation itself and can be rejected if the signature is not detected

