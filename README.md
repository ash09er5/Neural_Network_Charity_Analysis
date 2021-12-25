# Neural_Network_Charity_Analysis

# Overview
In this moduel we are using a neural network to predict whether or not an applicant will be sucessful if they are funded by Alphabet Soup

# Results


Data Preprocessing
Target Variables: IS Successful

Feature Variables: All variables except the ISSUCESSFUL and the ones that were dropped

Variables to be removed: EIN and NAME as these variables would have no influence on the output of the model

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
First Run: 8 in the first layer and 5 in the second layer
The reason i had the number so low was i used the numbers from the moduel excersise because i was not sure what to put there first.
For the second run i incresed it up to 75 for the first layer and 25 for the second layer. For the rest of them i incresed it slightly more 

I ran the model multiple times changing the amount of hidden layers and also chaning the activation functions for the output layer and
the amount of loss went up and the accuracy went down to less than 50 percent
Second Run 70 in the firstlayer and 25 in the second layer

# First Run Results:
![first_run](https://user-images.githubusercontent.com/25463509/147381726-b9c02eb3-71fa-4c98-b61c-2465b68a109d.png)


# Second Run Results


![second_run](https://user-images.githubusercontent.com/25463509/147381733-c00f07fb-6ddc-4467-b250-22467fc93d07.png)


# Run Number ??????
Eventually lost track of how many times i ran this model but to no avail I was only able to bring it back up slightly over 50%


[Screenshot 2021-12-25 042726](https://user-images.githubusercontent.com/25463509/147382112-c0cb3469-54c6-4e0b-b4c0-0c6dd4044bdc.png)



![Screenshot 2021-12-25 042919](https://user-images.githubusercontent.com/25463509/147382129-d562926b-56e5-45ab-a8f4-eb200434d0c2.png)


# Summary
 
As for the two runs the models accuracy decresed from the first run to the second run starting from 68% down to 65% and using a relu 
activation fuction for the hidden layers and a sigmoid fuction for the outter layers. Overall i was not able to bring it over 70% for 
this test.
