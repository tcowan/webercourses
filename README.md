# webercourses

## Introduction
This repo contains two Python 3 script, `cate` and `catc`.  

The function of `cate` is to extract all the text from the Weber State Catalog
which the user has downloaded to this folder and renamed to "catalog.pdf".

`cate` outputs the text to stdout, which is piped into `catc`

The function of `catc` is to output to stdout a CSV of all course descriptions
found at the end of the catalog.pdf file.  These two functions, extract and
produce CSV were separated because the extraction process takes a while to run.
