# My-Notes_LA (Data Science)
-----------------------------------------------
-----------------------------------------------
# Relevant Links

### Links are entered as [Description/Name](Link)  **makes it a clickable link

* [Code Practice](https://codingbat.com/python)

* [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

----------------------

# Gits/Github

* git init to initialize Git repository within a folder. (Avoid making repositories inside repositories)

* git status at every stage, gives you info on the status
red text means that the file has not been committed

* git add . = period will add anything that has not been added

* git commit (every commit has to have a commit message

* git push

* git log = shows log of commits

* git diff = difference between the commits

----------------------------------------------------
# Markdown

## Anchors/Internal Reference Links

In standard markdown, place an anchor <a name="abcd"></a> where you want to link to and refer to it on the same page by [link text] (#abcd).

## Images

``` 
![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)
```

![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)

----------------------------

# SQL


---------------------------------------

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

-----------------------;

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
------------------------------------------
# `matplotlib.pyplot` visualizations

* Tovio says will be one of the most important sections (save code so won't have to redo)

---------------------------------------

# pandas

* Tovio says is also important 

# Derivations 

* will use for Jupyter Notebooks

[Derivation of a Perceptron]()

--------------------------------------

# LaTEX
* won't render in Github but will in VSCode
* figure out why this is not rendering for me. Discussed at 1:02:41 in Notetaking Strategy Video

$$
\sum_{x=1}^{25} a_x
$$

