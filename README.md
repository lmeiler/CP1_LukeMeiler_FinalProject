# CP1_Final Project
## Luke Meiler and Austin Marga

Below are all files pertaining to UB PHY 410 Fall 2021 Final Project for the group of Luke Meiler and Austin Marga.

---

# Line Frequency Stability

This is the final project on our class of Computational Physics.
Our plan is to explore the electrical grid and its structure from at-home experiments that are easily accessible to everyone.

## Project Structure

To read about and follow my project I suggest reading the following articles.
[www.energuide.be](https://www.energuide.be/en/questions-answers/why-does-the-electricity-grid-have-to-stay-in-balance/2136/)
[www.engineering.com](https://www.engineering.com/story/grid-frequency-stability-and-renewable-power)
Please note this code is under the following license *Apache License 2.0*, or `apache-2.0` in GitHub and the documentation for this license [apache.org](https://www.apache.org/licenses/LICENSE-2.0).
The main Jupyter notebook that walks through the complete process of gathering magnetic field data from a household appliance to processing and analyzing it is found in this repository, titled `Magnet.ipynb` which you can see [here](https://github.com/ubsuny/CP1_LineFrequency_Project/blob/main/Magnet.ipynb).
The necessary utility functions written in *Python* are in the [UtilityFunctions](https://github.com/ubsuny/CP1_LineFrequency_Project/tree/main/UtilityFunctions) folder.
To run the Jupyter notebook I suggest using the docker image *ubsuny/cp1-hw8:latest*.
There is also a YouTube video *link here*.


## Setup

Do the following to navigate the repository and begin doing the experiment on your own:
In a Jupyter Notebook terminal:
```
git clone https://github.com/ubsuny/CP1_LineFrequency_Project
```
The following `.txt` documents are pre-gathered data used for our analysis:
'MagnetTest1.txt','MagnetTest2.txt','MagnetTest20.txt','MagnetTestLong.txt'
The usages for all of these text files, along with the bulk of the project, are found in  the  'Magnet.ipynb' Jupyter Notebook. 

Additionally, in the 'UtilityFunctions' folder, find the `python` file 'Utility.py' which can be used for your own experiments.
## Your Participation

If you want to participate feel free open an issue with the appropiate labels and/or fork my project and create a pull request against the *main* branch.

