# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
It went from 0.89 to almost 0.65. The accurate significantly decreases, and this is becaues the model isn't scaled, creating a giant decrease in accuracy of the values and removing variance of the values.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
0.89. This model is accurate for the given use case, as it nearly has a 90% success rate, leading to a very high success rate in the results which is very good for the use case.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model was extremely accurate, however there was discernable pattern to inputs that resulted in an incorrect model.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No, they would not according to the model.
