# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
0.86. This means that there is a very strong correlation, and that the data is in a close proximity to the line of best fit, signifying a more accurate response.
2. Is your model accurate? Why or why not?
The model is more accurate, because it a higher r squared coefficient meaning that the data is more reliable and has a stronger correlation. The data points are not scatterd around.
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
Around $8000, and around $550.
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
I believe this is happening because there is no limit below 0 for the predicted results, meaning that if a car is deemed as worthless or has a very low value, then the value can potentially dip below $0.