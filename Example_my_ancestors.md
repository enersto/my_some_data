My Ancestors
================
enersto
2018???8???31???

This file inspires from the [package radmixture](https://github.com/wegene-llc/radmixture), which is an ancestors calculator tool comtaining public calculator data. But the package only provides unvisible and single results. This's why I write the file to make a cut short to find your ancestor infomation visiblely.

This file fits for those people:

-   learn some things about R and Rmarkdown;

-   get personal gene data;

-   want to know more ancestors information in your gene

data import
-----------

### reliable package

``` r
library(radmixture)
library(data.table)
library(ggplot2)
library(ggthemes)
```

### calculator data

If you don't get calculator data yet, downloan with the "\#"line.

``` r
load('/Users/kazuya/Desktop/For R Use/Gene/data/globe4.alleles.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/globe4.4.F.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/K12b.12.F.RData.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/K12b.alleles.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/K7b.7.F.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/K7b.alleles.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/e11.11.F.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/e11.alleles.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/globe13.13.F.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/globe13.alleles.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/world9.9.F.RData')
load('/Users/kazuya/Desktop/For R Use/Gene/data/world9.alleles.RData')
```

### personal data

Change file path in the Rmd file like this:

genotype &lt;- fread("your\_path/your\_file.txt")

calculater results
------------------

### Use E11

A good calculator for east asian people.

![](myGene_files/figure-markdown_github/unnamed-chunk-4-1.png)

### Use world9

![](myGene_files/figure-markdown_github/unnamed-chunk-5-1.png)

### Use K4

![](myGene_files/figure-markdown_github/unnamed-chunk-6-1.png)

### Use K7b

![](myGene_files/figure-markdown_github/unnamed-chunk-7-1.png)

### Use K12b

![](myGene_files/figure-markdown_github/unnamed-chunk-8-1.png)

### Use K13

![](myGene_files/figure-markdown_github/unnamed-chunk-9-1.png)
