# Activity Identification

Looking to see if I can classify [this](http://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring) time series dataset. A set of test subjects had a variety of sensors attached to them whilst perfoming various activities. 

Start by exploring the dataset in [this notebook](descending_stairs_plot.ipynb).

I was about to start writing scripts to process the .dat files but found on GitHub that user @ianlcassidy has already a repo for this dataset. His original repo is forked to my master branch and this dev branch retains the file which processes the datasets while all others for now are deleted. 

An initial binary 'beginners' task with this time domain data might be:

* Is this subject descending stairs or not?
