# Hospital-Cost-Efficiency-Analysis

IDC6940 - Capstone in Data Science - Fall 2022

Florida International University

Student :
Rolf Kinder Gilet

Faculty Mentors : 
Dr. Kalai Mathee, 
Dr. Alejandro Arrieta

Faculty Advisor : 
Dr. Giri Narasimhan


## Abstract 

Throughout the years, the citizens of the United States has experienced a steady increase 
in the cost of their healthcare. According to the Centers for Medicare & Medicaid Services [93], 
in 2021, healthcare costs skyrocketed to $4.3 trillion [Figure 1]. The American Medical 
Association revealed that the United States spends more on healthcare than any other country in 
the world, with costs approaching 18% of the gross domestic product (GDP) [1]. The cost of 
healthcare is driven by many confounding factors such as the economy of the market that the 
hospital is operating in, natural disasters, and waste just to name a few. The diverse nature of
those factors makes researching the cost of healthcare a complex issue. Fortunately, many 
scholars before us have researched and analyzed the problem. The Institute of Medicine,
Berwick, and Hackbarth, have identified six domains of waste that are said to have a direct 
impact on the cost of healthcare. Hence reducing the cost of any of those six domains, we may be 
able to reduce the cost of healthcare [2]. Those six domains of waste are failure of care delivery, 
failure of care coordination, overtreatment or low-value care, pricing failure, fraud and abuse, 
and administrative complexity. Administrative complexity is the most tangible and measurable 
of the six domains of waste, hence, we focus on waste, which is related to administrative 
complexity. We define administrative complexity cost as the needed expenses of a hospital for 
its day-to-day operations. We assumed that hospitals that provide the same type of service 
(hospital type) and are relatively similar in size, (number of beds, employees) shouldn't have too 
much of a variation when it comes to their administrative complexity cost. As such, our objective 
for this paper is to use Data Envelopment Analysis (DEA) and Stochastic Frontier Analysis
(SFA) to model an efficiency score for each hospital in our Centers for Medicare & Medicaid 
Services (CMS) data. 


We will use the mean method used by Haney and Pollitt [94] to combine the results from 
DEA and SFA for each hospital and generate a final efficiency score for each hospital. With the 
combined or consolidated efficiency score from both methods (DEA and SFA), we will identify 
hospitals with low-efficiency scores, hospitals with average efficiency scores, and hospitals with 
high-efficiency scores. We also hoped to gain a deeper understanding of the confounding 
variables that have a direct impact on the hospital's efficiency scores. Finally, we hope to analyze 
annual trends and compare the top and bottom 5 hospitals, we hope to draw a meaningful 
conclusion on the reason behind the efficiency scores trends and make suggestions for 
improvements.

Key Words: Hospitals, Efficiency, Data Envelopment Analysis, Stochastic Frontier 
Analysis, Administrative complexity
