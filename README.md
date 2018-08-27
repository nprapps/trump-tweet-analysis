# Analysis of Trump tweets

Data from the [Trump Twitter archive](http://www.trumptwitterarchive.com/).

#### Previous versions

A [2017 version of this analysis](https://github.com/nprapps/trump-tweet-analysis/releases/tag/v1.0) was used in a [Morning Edition radio segment](http://www.npr.org/2017/04/27/525833198/analyzing-trumps-patterns-of-tweeting).

The current iteration has diverged in several significant ways, including:

- Updating the underlying data to cover Trump's presidency to date (through Aug. 26, 2018).
- Updating the analysis code to accommodate data from multiple years.
- Different keyword searches

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
