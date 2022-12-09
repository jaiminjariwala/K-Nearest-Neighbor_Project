# Goal: To Create a Machine Learning Model capable of detecting the difference between a Rock or a Mine based on the response of 60 seperate Sonar Frequencies.

<b>Done using a PipeLine and a GridSearchCV(Grid Search Cross-Validation) tool!</b> <br>

<b>Imported the following Libraries:</b><br>

import numpy as np <br>
import pandas as pd <br>
import matplotlib.pyplot as plt <br>
import seaborn as sns <br>

from sklearn.model_selection import train_test_split <br>
from sklearn.preprocessing import StandardScaler <br>
from sklearn.neighbors import KNeighborsClassifier <br>
from sklearn.pipeline import Pipeline <br>

<i><b> To test Various values of K and report back the best performing parameter, imported... </b></i><br>
from sklearn.model_selection import GridSearchCV
