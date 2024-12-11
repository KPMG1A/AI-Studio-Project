# AI-Studio-Project
Overview, Objective, and Goals: The purpose of our project was to help C5LA, one of KPMG's clients, increase the number of donations they receive by developing accurate models that can predict whether a donor will become a repeat donor. This allows C5LA to know what donors to target and reach out to more to most efficiently increase their number of donations.
Methodology: We did data exploration on the CSV files that included information about individual donations. We combined multiple CSV files together with Python libraries such as Pandas to ensure we could see whether a donor donated again. Through our data exploration, we were able to create a combined dataset that showed us whether a donor became a repeat donor and the demographic breakdown of the region the donor was from. These were features that our model later learned to predict whether someone would donate again. In building our model, we developed Random Forest Decision Tree and Logistic Regression models. We compared the performances of both and settled on the Decision Tree given it was more accurate. At the end, we improved the performance of the model by making small tweaks such as filling null values with the mean instead of median.
Results and key findings: We found that our model had a very high accuracy rate of about 98%. We also found that in general, any given donor is quite likely to donate again, so we could report to C5LA that they were doing a great job with retention. We had an F1 score of 0.84.
Visualizations:
<img width="763" alt="image" src="https://github.com/user-attachments/assets/afb8618c-aec3-47c7-b6b2-2147c55688f5">
<img width="741" alt="image" src="https://github.com/user-attachments/assets/650fdcac-a581-43b6-988c-f2ee23492e12">
<img width="705" alt="image" src="https://github.com/user-attachments/assets/210de751-9719-4691-86f3-6a7669159006">
<img width="659" alt="image" src="https://github.com/user-attachments/assets/d7aba13e-3bd4-4d64-a3bf-0d0e725388ed">
<img width="723" alt="image" src="https://github.com/user-attachments/assets/d3949799-12a8-4071-b54c-0307a887a518">
Potential next steps: We have a few more ideas and small tweaks that could be used to improve the model. We also want to retrace our steps in how we created the combined dataset early on. Some other ideas we could explore including finding the most important factors in determining whether a donor would donate again, and using our model to generate a percentage of how likely they are to donate again instead of a binary result.

Thank you so much to Morgan Abbitt, Sam Tan, and Yi Tong for your advice and support throughout the past few months! :)


