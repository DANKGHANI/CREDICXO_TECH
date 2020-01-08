# CREDICXO_TECH
Please find the attached code for the task assigned here.
I have used a simple keras sequential neural net for the above task assigned.
My approach involved understanding the data provided initially  by looking at any missing values to clean the data, looking at the values of that were repetative and if some inference could be drawn from it. Next, I used robust scaling to scale the data, which helps in removing abnormal valesthat may be prevalent in the data vast data provided. After scaling, correlation matrix was formed and all the fields that were co-related were removed. Co-relation helps provide the right fields to be chosen to ne used to help predict much more accurately. Lastly a 3 layer sequential neural net providd us with good results.
One the training was finished, we used simple tools of visualization (library matplotlib.pyplot) to plot accuracy and loss graphs. The recall, precision and f1-score were calculated.
The above methodology provided an accuracy of 0.99 and had minimum losses as depicted by the graphs below.




![Accuracy](SC1.png)




![Loss](SC2.png)
