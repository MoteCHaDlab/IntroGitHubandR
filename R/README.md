# Introduction to R

Code Notebook Author: Sara D. Williams

Contact: swilliams@mote.org

Updated: 4/1/2021

## If you're new to R...

Download R from https://mirrors.nics.utk.edu/cran/

Dowload R Studio from
https://rstudio.com/products/rstudio/


## If you're not new to R...

Still check your versions, and update to the latest version of R and RStudio.

How to check your R version inside R:

```{r}
R.version$version.string
```


## Using R Notebook and R Markdown

I prefer to use R Notebooks to write all of my code. It helps me stay organized by allowing me to write up notes and results in the same file as my code and makes it pretty. 

So what are R notebook and R Markdown? Well, R notebook is just like an interactive R Markdown. R Markdown allows you to create PDFs, word documents, HTML docs of your code and uses Latex to format text and equations outside of code chunks. In R Markdown, you have to keep "knit"-ing your file to see what it will look like, but with R notebook, you can preview as you go. In R notebook/markdown, you can use different heading levels to set up your code into different sections, put in mathematical equations, insert images from outside R, and view figures made from R inline with your code. 

I like using R Notebooks as a kind of "living lab notebook for my code and analyses." Whatever you do, try to make it a habit and stick to it. 

### Some resources for learning about using R notebook/markdown:

https://bookdown.org/yihui/rmarkdown/notebook.html

https://rmarkdown.rstudio.com/articles_intro.html

http://www.stat.cmu.edu/~cshalizi/rmarkdown/

## Best coding principles:
1. Comment your code.
2. Comment your code.
3. Comment your code.

## Some favorite getting started with R links:

https://rafalab.github.io/dsbook/getting-started.html

http://www.cookbook-r.com

https://www.rstudio.com/resources/cheatsheets/?utm_content=buffer46add&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer

https://r4ds.had.co.nz

https://ourcodingclub.github.io/tutorials/intro-to-r/


## The dataset we will use in most code vignettes: The Palmer Penguins

https://allisonhorst.github.io/palmerpenguins/articles/intro.html

Install the package: 

```{r}
install.packages("palmerpenguins")
```


