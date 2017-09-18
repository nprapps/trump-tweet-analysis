# Analysis of Trump tweets

Data from the [Trump Twitter archive](http://www.trumptwitterarchive.com/).

This analysis was used in a [Morning Edition radio segment](http://www.npr.org/2017/04/27/525833198/analyzing-trumps-patterns-of-tweeting). However, because this version uses the latest data at the time the notebook was last run, the data analyzed will be more up-to-date than the radio piece, which taped on April 26, 2017.

### Assumptions

* Python 3 - If you don't have it, you can install it with Homebrew using the command `brew install python3`
* virtualenvwrapper - Used for isolating notebook dependencies 

### Bootstrap the project

```
$ git clone https://github.com/nprapps/trump-tweet-analysis.git
$ mkvirtualenv --python=$(which python3) trump-tweet-analysis
$ pip install -r requirements.txt
```

### Run the notebook

```
$ cd trump-tweet-analysis
$ workon trump-tweet-analysis
$ jupyter notebook
```

A listing of files in the project directory should open automatically in your preferred browser. If it doesn't copy the URL given in terminal.

Click on the link for `trump-tweets.ipynb` to view the notebook.  

Click the `Cell` menu and then the `Run All` menu item to execute the cells and get the most recent results.
