# Political Sentiment Analysis

This is a library to analyze the political sentiment of text. We use Deep Learning models to evaluate the speaker's political leaning (liberal/democrat or conservative/republican). This was done as the final project to an MIT course, 17.835 in 2018. Trained models can be found in the bin.

# Setup

After cloning this repository, setup a python virtual environment. This can be done with 

```
source setup
```

this can also be used after initially setting up the environment to activate the virtual environment.

# Project Structure

![image](https://user-images.githubusercontent.com/81732369/206875391-e9937aa4-4c5b-4d47-8411-42beef186759.png)

### bin - this includes binary files like weights or cached data files.
### convote - this is the cornell vote database that includes transcriptions of congressional debates from 2005 along with labels for both for the political party of the speaker and whether the statement is for/against the bill.
### preprocessing - code to preprocess the various datasets into usable formats for the various models 
### models - contains python code that exports keras models


