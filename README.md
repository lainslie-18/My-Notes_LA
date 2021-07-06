# My-Notes_LA (DSI)

# Relevant Links
### Links are entered as [Description/Name](Link)  **makes it a clickable link

* [Code Practice](https://codingbat.com/python)

* [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

----------------------
# Markdown

## Anchors/Internal Reference Links
In standard markdown, place an anchor <a name="abcd"></a> where you want to link to and refer to it on the same page by [link text] (#abcd).

------------------
# Bash Scripting
* bash profile location on somewhere:  
`~/~./bash_profile`


### Make a Bash Function
```bash
function gitadder() {
    git pull
    git add .
    dt=$(date '+%d/%m/%y %H:%M:%S');
    git commit -m "Auto Updated: $(date '+%a %M:%H %h %d %Y')"
    git push
}
```
-----------------------
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