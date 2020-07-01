# WQU COVID-19 EXPLORATORY DATA ANALYSIS (EDA) PROJECT

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7103e561afcb48049e835a7a6f35ed24)](https://app.codacy.com/manual/boratonAJ/WQU-ML_PROJECT?utm_source=github.com&utm_medium=referral&utm_content=boratonAJ/WQU-ML_PROJECT&utm_campaign=Badge_Grade_Settings)


The purpose of this turorial is to introduce everyone to the [2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) and how to explore it using some foundational packages in the Scientific Python Data Science stack.

This is intended for practice and share amongst insight we derive from the data and data visualizations. Note, we may ask you to explain your thought on how you go about creating the data visualization as well as making it clear for everyone to understand the process you follow, in many cases it is irresponsible to publish amateur visualizations, which at best will not make sense to some domain expertise. After EDA process, we will proceeed to doing predictions and some statistical modelling.


## Prerequisites

Not a lot. It would help if you knew

* WQU Unit 1: programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about `pandas` and DataFrames;
* a bit about Jupyter Notebooks;
* a bit of how to work with terminal/shell.


**However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.**

Also, if you'd like to watch and **not** code along, you'll also have a great time and these notebooks will be downloadable afterwards also.

If you are going to code along and use the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below), I ask that you install it before you start.



## Getting your anaconda environment set up


### 1. Clone the repository

To get set up for this EDA, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/hugobowne/WQU-COVID-19
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).


Please follow the following link to download your prefer doistribution to use for exploring the data;

* [Downloading conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html) 
* [Installing on Windows](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html) 
* [Installing on macOS](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)
* [Installing on Linux](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)


### 3. Create your conda environment for this session

Navigate to the relevant directory `WQU-COVID-19` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called covid_19_eda. To activate the environment on OSX/Linux, execute

```
source activate WQU-COVID-19
```
On Windows, execute

```
activate WQU-COVID-19
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the notebook `WQU-COVID-19-EDA.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). 
