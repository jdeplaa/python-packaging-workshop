---
title: "Package structure"
teaching: 0 # teaching time in minutes
exercises: 0 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions 

- How do you write a lesson using Markdown and `{sandpaper}`?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

After following this episode, learners will be able to:
 
* Create a directory structure for their package
* Create the essential files needed for the package (e.g. `src/<packagedir>/sourcefile`, `README.md`, `__init__.py`, etc.)
* Create a small program that prints 'Hello world!'
* Import your program into Python

::::::::::::::::::::::::::::::::::::::::::::::::

## Package structure


::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?
Please indicate which essential file(s) are missing in the following Python package structure:
```
   README.md
   src/mypackage/hello.py
   pyproject.toml
```

:::::::::::::::::::::::: solution 

## Answer
 
```output
`src/mypackage/__init__.py`. Bonus points for `LICENSE`, `CHANGELOG`, `doc` directory with documentation.
```

:::::::::::::::::::::::::::::::::


## Challenge 2: 

The following simple Python program prints "Hello World!". Can you create a function instead that prints "Hello World!" when you call the function `hello_world()`.
```
print('Hello World!')
```
Where would you save the hello.py file for this program?

:::::::::::::::::::::::: solution 

```
def hello_world():
    print("Hello world!")
    return
```
Save it in ``src/mypackage/hello.py``.

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: keypoints 

- To be determined

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
