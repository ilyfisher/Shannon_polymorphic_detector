# Shannon_polymorphic_detector
Reads JSON to detect polymorphic malware using Shannon's Entropy

For the purposes here I did not reinvent the wheel so I used the code from here 
https://onestopdataanalysis.com/shannon-entropy/ to calculate the entropy score 
of the data. I loaded the data into a dictionary for each entry. I have to use 
an array since the file contains multiple layers to get to the folder I need. 
I save the calculated entopy scores in an exported csv file so that it easy
to look through. It was able to score anomalous data as abnormal and in a case
when we planted a malware file it was able to detect the file as being abnormal.
