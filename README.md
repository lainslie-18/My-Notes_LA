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

