# Kaggle comment toxicity competition

Link to competition: https://www.kaggle.com/c/jigsaw-toxic-severity-rating/overview 

This is an unsupervised task where we are given only the comments as the training data and we as researchers need to predict the toxicity of the comments. 

The prediction score can be any range. The final score is calculated by how many hidden pairs of comments are labeled correctly. A "correct" label is a one where 
the more "toxic" comment has a higher score than the least toxic comment. 

# Data 

The data should be downloaded via: https://www.kaggle.com/c/jigsaw-toxic-severity-rating/data and put into the **data/** directory. 

# Starting off the virtualenv 

```
# Creating the environment
virtualenv --python 3.9 env

# Starting it 
source env/bin/activate

# Populating with packages
pip install -r requirements.txt
```

# Installing the environment to jupyter kernels

```
ipykernel install --user --name=env
```