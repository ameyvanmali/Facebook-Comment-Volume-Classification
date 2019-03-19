# Install the following libaries in the same order. The first two libraries are for plotting the decision trees. It may or may # not work for some other systems based on whether the Environment variables have the path of graphviz or not. If it doesn't # run and plot the decision tree then consider it as your system issue. It works for me. The rest of the code can still be # executed.

!pip install graphviz
!pip install pydot

!pip install xgboost

# Import the following libraries

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings
warnings.simplefilter("ignore")
from sklearn.svm import SVC, LinearSVC
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import cross_validate
from sklearn.model_selection import train_test_split
from sklearn import preprocessing
import seaborn as sns
from sklearn.model_selection import learning_curve
from sklearn.metrics import classification_report, confusion_matrix
from sklearn import metrics
from matplotlib import style
from sklearn.model_selection import learning_curve
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import confusion_matrix,classification_report,accuracy_score
%matplotlib inline
plt.style.use('ggplot')
from sklearn.tree import export_graphviz
from sklearn.externals.six import StringIO
from IPython.display import Image
import pydotplus
from sklearn.ensemble import AdaBoostClassifier
from sklearn.model_selection import learning_curve
from sklearn.model_selection import ShuffleSplit

# Download link for the Facebook Comment Volume dataset

https://archive.ics.uci.edu/ml/datasets/Facebook+Comment+Volume+Dataset
 