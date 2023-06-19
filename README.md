# My-Notes_LA (Data Science)
*****************************************
# Relevant Links

### Links are entered as [Description/Name](Link)  **makes it a clickable link

* [Code Practice](https://codingbat.com/python)

* [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

*****************************************

Something I would advise you to consider is perhaps a change in format. Industry standard is comment notation is used for explaining what your code is doing, and markdown notation is for documenting takeaways and questions. I would suggest using markdown for your null and alternative hypothesis, as well as using markdown to explain, in plain English, what the results of your statistical tests mean.

**********************************************

# <font color = green> Gits/Github </font>

* git init to initialize Git repository within a folder. (Avoid making repositories inside repositories)

* git status at every stage, gives you info on the status
red text means that the file has not been committed

* git add . = period will add anything that has not been added

* git commit (every commit has to have a commit message

* git push

* git log = shows log of commits

* git diff = difference between the commits

**********************************************

# Markdown

# For Titles
## For Major Headings
### For subheadings
#### For 4th level headings

- bullet points

>to block quote or indent

**to make bold**, *to italicize*, ~~to strikethrough~~

**To create task boxes (doesn't render appropriately on Github)**
- [x] Some task
- [ ] Some more tasks
[x] Some task
[ ] Some more task

 <font color = color> To create a font color </font>

<code style="background:yellow;color:black">How to highlight text.</code>

<code style="background:black;color:white">How to highlight with black background</code>

### How to create a table:
| Step  1 | Step 2 | Step 3 | Step 4 | Step 5 |
|---------|--------|--------|--------|--------|
|Acquire  |Prep    |Explore |Model   |Evaluate|

:--- = left align
---: = right align
:---: = centered

`How to do monospace font for code snippets using the grave accent. `

```
how to do code blocks
```

how to add a button with a link
<button class="button-save large">[Codeup Data Science](https://codeup.com/ds-course-catalog/)</button>

how to add a linked image button (cannot use locally saved img. need image url)
[![alt text](image address)](target_url)


## Anchors/Internal Reference Links

In standard markdown, place an anchor <a name="abcd"></a> where you want to link to and refer to it on the same page by [link text] (#abcd).

## Images

``` 
![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)
```

![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)

****************************************************

# SQL

Data stack - 

Relational Database Mgmt System (RMDS) - is operating system for the database

Data definitiion language - 

Data Manipulation language - we use to interact with data

Flavors - different dialects of SQL

We as data scientists work with data warehouse

SQL works with data warehouse

Custom functions in SQL are called stored procedure if I want to look into it.

There are SQL formatter websites where you can put in messy SQL and it returns a pretty/simplified version (search SQL formatter)


****************************************************

# Jupyter Notebook

* How to change theme:

https://stackoverflow.com/questions/46510192/change-the-theme-in-jupyter-notebook






*****************************************************************

# Bash Scripting

* bash profile location on somewhere:  
`~/~./bash_profile`

## Make a Bash Function

```bash
function gitadder() {
    git pull
    git add .
    dt=$(date '+%d/%m/%y %H:%M:%S');
    git commit -m "Auto Updated: $(date '+%a %M:%H %h %d %Y')"
    git push
}
```

****************************************************

# Python

## Comprehensions

```Python
[num for num in range(100)]

```

## Functions to Remember

```Python
def factorial(n):
    prod = 1
    for num in range(n+1):
        prod *= num
        return prod
```

·         ** Methods**

·         String: `capitalize()`, `casefold()’ (converts to lowercase), `count()`, `find()`, `index()`, `join()`, `lower()`, `replace()`, `split()`, `upper()`,

·         List/Array: `append()`, `clear()`, `copy()`, `count()`, `extend()`, `index()`, `insert()`, `pop()`, `remove()`, `reverse()`, `sort()`

·         Dictionary: `clear()`, `copy()`, `fromkeys()` (returns a dict with the specified keys and values), `get()`, `items()` (returns a list containing a tuple for each key value pair), `keys()` (returns a list containing dict keys), `pop()`, `popitem()` (removes the last inserted key-value pair), `update()` (updates the dict with the specified key-value pairs), `values()` (returns a list of all the values in the dict

 

·         **Keywords**

 

·         Break, continue, def, del, elif, else, except (used with exceptions, what to do when an exception occurs), False, for, from (to import specific parts of a module), if, import (to import a module), in, is (to test if two variables are equal), lambda (to create an anonymous function), None, not, or, pass, return, True, while,

 

·         The dir() built-in function returns a sorted list of strings containing the names defined by a module. The list contains the names of all the modules, variables, and functions that are defined in a module. (print(dir(random)))

## Useful Tools

`from collections import defaultdict, Counter`

* `defaultdict` is like a regular dictionary, except that when you try to look up a key it doesn't contain, it first adds a value for it using a zero-argument function you provided when you created it. Useful when you have to iterate through and count items

* `Counter` turns a sequence of values into a defaultdict(int)-like object mapping keys to counts. Primarily used to create histograms. Has a `most_common` method that is frequently useful

* using `try, except`

**********************************************************

# `matplotlib.pyplot` visualizations

* Tovio says will be one of the most important sections (save code so won't have to redo)

* `print(plt.style.available)`

* `plt.style.use('seaborn-deep')`


******************************************************

# pandas

* Tovio says is also important 

******************************************************

# Derivations 

* will use for Jupyter Notebooks

[Derivation of a Perceptron]()

*******************************************************

# LaTEX


$$
\sum_{x=1}^{25} a_x
$$

*******************************************************

# Statistics

## Population vs Sample
Population (N) - the collection of all items of interest to our study

Parameter - a value that refers to a population

Sample (n) - a subset of the population

Statistic - a value that refers to a sample

Random Sample - a sample where each member is chosen from the population strictly by chance

Representative Sample - a sample taken from the population to reflect the population as a whole

## Types of Data
Variable - a characteristic of a unit which may assume more than one value (height, weight, etc)

Types of data - a way to classify data, one of either categorical or numerical

Categorical Data - describes categories or groups

Numerical Data - represents numbers and can be further classified into discrete and continuous

Discrete Data - data that can be counted in a finite manner. Cannot zoom into smaller measurements (can't have 1/2 baby)

Continuous Data - infinite and impossible to count (length, weight). There are infinite measurements between 1 and 2 inches depending on how microscopic you want to get.

## Levels of Measurement
Levels of Measurement - a way to classify data. There are two levels of measurement: qualitative (nominal & ordinal) and quantitative (ratio & interval)

Qualitative Data - a subgroup of levels of measurement. Two types: nominal & ordinal

Quantitative Data - a subgroup of levels of measurement. Two types: ratio & interval

Nominal - the data can only be categorized

Ordinal - the data can be categorized and ranked

Interval - the data can be categorized, ranked, and evenly spaced 

Ratio - the data can be categorized, ranked, evenly spaced, and has a natural zero

 - from nominal to ratio, the complexity and precision of the level of measurement increases

## Categorical Variables - Visualization Techniques
Frequency Distribution Table - a table that represents the frequency of each variable

Frequency - measures the occurrence of a variable

Absolute Frequency - measures the number of occurrences of a variable

Relative Frequency - measures the relative number of occurrences of a variable, usually expressed in percentages (proportion of all)

Cumulative Frequency - the sum of relative frequencies so far, the cumulative frequency of all members is 100% or 1

Pareto Diagram - a type of bar chart where frequencies are shown in descending order, an additional line on the chart shows the cumulative frequency (almost like a cross between a bar and pie chart)


