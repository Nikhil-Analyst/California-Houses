# California-Houses
The Data sets describe various aspects and details of the house's location and people. The houses are located in California, USA.

Question 1. What is the average median income of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.
avg = res1["median_income"].mean() #finding mean
rounded = round(avg,2) #rounding the mean to 2 decimal
print(f"Average Median Income of the data set is: {rounded}.")


plt.figure(figsize=(4,5))
res1.hist(bins=50,figsize=(15,15), edgecolor="black") #Histogram to be used
plt.show()




