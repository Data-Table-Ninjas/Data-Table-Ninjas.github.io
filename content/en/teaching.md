---
title: "Data Table Ninjas: Teaching"
description: "Our seminars will level up your data science programming skills"
theme_version: '2.8.2'
cascade:
  featured_image: '/images/data-table-hex-logo.png'
---

We are experts in statistical programming -- we have been using
R/Python/C/C++/JavaScript since 2003 (20+ years). During that time, we
have been able to see the advantages and disadvantages of different
programming approaches, and we would be excited to share our insights
with you, during a half-day or full-day teaching seminar, on one or
more of the following topics.

## Seminar topics

### `data.table` for data science

We will teach you how to speed up your data analysis scripts by
10-100x using [`data.table`](https://r-datatable.com/), which is a
state-of-the-art in-memory database system, implemented as an R
package with efficient C code. We can discuss a wide range of topics,
including basics such as reading/writing CSV, as well as advanced
topics such as rolling joins for time series data.  Example: [3 hour tutorial with exercises presented at LatinR conference, Montevideo, Uruguay, Oct 2023](https://github.com/tdhock/2023-10-LatinR-data.table?tab=readme-ov-file#english).

### `torch` for deep learning in R and python

Do you want to create applications that use artificial intelligence,
trained using machine learning algorithms on big data sets? (text,
image, tabular, time series, etc) Then we can teach you how to use
`torch`, from basics like stochastic gradient descent learning with
DataLoaders, to advanced topics like application-specific loss
functions, such as the AUM loss which we proposed for learning with
imbalanced binary labels (for example 99% negative labels, 1% positive
labels, [Python
code](https://tdhock.github.io/blog/2024/torch-roc-aum/), [R
code](https://tdhock.github.io/blog/2024/auto-grad-overhead/)).
Example: [Introduction to Deep Learning in R, a 2 hour lecture for
Research Bazaar Arizona, Flagstaff, April
2023](https://github.com/tdhock/2023-res-baz-az?tab=readme-ov-file#19-april-2023-workshop).

### Machine learning with `mlr3` package

Do you want to be able to easily compare prediction accuracy of
different machine learning algorithms, to help you decide which one
you should deploy for your own data sets? We can teach you how to do
that using the `mlr3` framework, which provides an easy-to-use
interface for many common and highly effective machine learning
algorithms (neural networks, linear models, random forests, boosting,
support vector machines, etc). Advanced seminars can include
parallelization using `mlr3batchmark` package. Example: [The
importance of hyper-parameter tuning blog
post](https://tdhock.github.io/blog/2024/hyper-parameter-tuning/).

### Advanced cross-validation for evaluating machine learning model predictions

Have you ever wondered if your machine learning model trained on this
year will still be accurate next year? Or if a model trained on data
from one country would be as accurate in another country? Or if your
machine learning algorithm would get better predictions if you had
more training data? We can teach you how to answer these questions
with the easily paralellizable implementation of cross-validation in
our
[`mlr3resampling`](https://github.com/tdhock/mlr3resampling?tab=readme-ov-file#installation)
R package.  Examples: [New code for various kinds of cross-validation
blog post](https://tdhock.github.io/blog/2024/cv-all-same-new/),
[Slides for talk about
SOAK](https://github.com/tdhock/two-new-algos-sci-ml?tab=readme-ov-file#title-abstract-slides)

### Regular expressions (regex) for text parsing and data reshaping

Does any of your data analysis involve scraping data from web pages,
or other text files like server logs? We will teach you how to use
regex for extracting tabular data from such data. Refactoring text
parsing code using regex can yield big speedups; using modern
packages like [`nc`](https://github.com/tdhock/nc), the code can be
made simple, readable, and maintainable!  Example: [tutorial with exercises
presented at McGill University, Montreal, Quebec,
2015](https://github.com/tdhock/regex-tutorial?tab=readme-ov-file#tutorial-on-named-capture-regular-expressions-in-r-and-python).

### Sequential and time series data analysis

### Data visualization

### R package development

### Reproducible analysis and report generation

### Time and memory efficient R programming

### C/C++ code in R packages and python modules

### Massive CPU parallelism

[Python](https://tdhock.github.io/blog/2022/cross-validation-cluster/)
[R](https://tdhock.github.io/blog/2020/monsoon-batchtools/)

### Relative advantages of python and R

### Database management systems

## Contact and cost

Please email toby.hocking@r-project.org with a description of the programming/teaching project you would like us to do for you, and we can schedule a free discovery call to discuss our proposed solution, with a quote for how much that would cost. 

Two of our most popular packages are:

* Half day package, US$1000, for two 90-minute seminars:
  * seminar 8:30-10:00.
  * coffee break 10:00-10:30.
  * seminar 10:30-noon.
* Full day package, US$2000, for four 90-minute seminars:
  * seminar 8:30-10:00.
  * coffee break 10:00-10:30.
  * seminar 10:30-noon.
  * lunch break noon-1:30.
  * seminar 1:30-3:00.
  * coffee break 3:00-3:30.
  * seminar 3:30-5:00.

Travel and hotel expenses would also be required for an in person
seminar (not applicable if you prefer that we create a virtual webinar
for your organization).
