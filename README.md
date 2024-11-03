# module_5_challenge_madplotlib

This challenge analyzes data from two sources for a company Pymaceuticals, one detailing profiles of different mice used in drug experiments and the other detailing study results by drug regimen on tumor size. Joining on Mouse_id, we are able to analyze the effectiveness of each of these drugs, with lower tumor size being the barometer of success.

The Drugs Capomulin and Ramicane show lower overall tumor volume than other drugs such as Infubinol and Ceftamin, indicating that they may successfully bring down tumor size. Tumor size increases up until day 20, and then drops off, indicating that future patients of the drug may see a 20 day delay for benefits.

Given a correlation coefficient >0.8 (.84), there appears to be a linear correlation between mouse size and tumor size, suggesting that the heavier the mouse, the larger a tumor size is. This can help inform future dosages by patient, altering dosage size by weight.


This challenge was completed using methods learned during class time and through personal notes, as well as referencing Stack Overflow (https://stackoverflow.com/questions/70754708/how-to-create-a-pie-chart-from-pandas-dataframe)
for suggestions on constructing different charts using Pandas vs. Pyplot. 
