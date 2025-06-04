Project summary  
The purpose of this project is to create and analyse a cohort of individuals based on the occurrence of a malady and a given treatment. For my project I chose to analyze a cohort of patients who experienced an opioid overdose and were treated with naloxone. 
	The initial cohort was generated using ATLAS and was drawn from de-identified patient data from the UCSF hospital network. Data was drawn from this source using RAE. For documentation on RAE use please see the following link  

https://ucsfonline.sharepoint.com/sites/InformationCommons/rae_ic/SitePages/Microsoft-Azure-Data-Studio.aspx?ct=1748859699191&or=OWA-NT-Mail&cid=ba85069a-7192-08f1-fae8-32edaa5b7c24&ga=1

Pattern matching results  
	When pattern matching was applied to the clinical notes to discovere references to naloxone, references were discovered in only about 60% of notes pulled with little or no variation in demographic information between the population where references occurred vs did not. This is in contrast to the over 95% rate of concept occurrence that was calculated by ATLAS during cohort generation. The 95% rate is most likely the more accurate number as Naloxone is the most effective treatment for opioids and has no contraindications, meaning  that it is used in almost all cases. The lower rate of naloxone discovered by pattern matching is likely due to a lack of documentation of this treatment in the clinical notes, and not alayzing enough notes from each patient. Due to computational constraints, only patient progress, ER history, and ER general notes were analyzed. 
	These note categories should, and to a certain extent do, cover the majority of references to narcan usage as opioid overdose is an acute condition and narcan is fast acting, meaning that if narcan was using it would be when or before patients arrived at the emergency room. The following is comparison of demographic information of patients whose notes included a reference to Naloxone vs those who did not as determined by pattern matching  
 ![image](https://github.com/user-attachments/assets/912cb0ad-3aa9-4659-a91c-54a807612b23)



These demographics are largely what I expected, though the average age is slightly older than I anticipated. All other demographics largely align with the demographics that were calculated as a part of milestone one using the built in software provided by ATLAS in the table shown below.  
![image](https://github.com/user-attachments/assets/e5dbf1ee-6bec-47f5-ad6b-2ad20b64181f)

