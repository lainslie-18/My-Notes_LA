# My-Notes_LA (DSI)

## Relevant Links

### Links are entered as [Description/Name](Link)  **makes it a clickable link

* [Code Practice](https://codingbat.com/python)

* [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

----------------------

## Day One

There is also a precourse that needs to be completed after the TI and by the Wednesday before class start.

# Gits/Github



# Markdown

## Anchors/Internal Reference Links

In standard markdown, place an anchor <a name="abcd"></a> where you want to link to and refer to it on the same page by [link text] (#abcd).

## Images

``` 
![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)
```

![Machine Learning Comic](https://imgs.xkcd.com/comics/machine_learning.png)


----------------------------;

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

