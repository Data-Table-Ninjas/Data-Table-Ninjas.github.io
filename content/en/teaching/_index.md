---
title: "Teaching"
description: "Our seminars will level up your data science programming skills"
theme_version: '2.8.2'
cascade:
  featured_image: '/images/data-table-hex-logo.png'
---

We are experts in statistical programming -- we have been using
R/Python/C/C++/JavaScript since 2003 (20+ years). During that time, we
have been able to see the advantages and disadvantages of different
programming approaches, and we would be excited to share our insights
with you, during a half-day or full-day workshop, including seminars
on one or more of the following topics.

## Seminar topics

### `data.table` for data science

We will teach you how to speed up your data analysis scripts by
10-100x using [`data.table`](https://r-datatable.com/), which is a
state-of-the-art in-memory database system, implemented as an R
package with efficient C code. We teach a wide range of topics,
including basics such as reading/writing CSV, as well as advanced
topics such as rolling joins for time series data. Example: [3 hour
tutorial with exercises presented at LatinR conference, Montevideo,
Uruguay, Oct
2023](https://github.com/tdhock/2023-10-LatinR-data.table?tab=readme-ov-file#english),
[video of 90 minute talk at RUG meeting, Madrid, Spain, Feb
2025](https://vimeo.com/1061999204).

### `torch` for deep learning in R and python

Do you want to create applications that use artificial intelligence,
trained using machine learning algorithms on big data sets? (text,
image, tabular, time series, etc) We teach how to use
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
you should deploy for your own data sets? We teach how to do
that using the `mlr3` framework, which provides an easy-to-use
interface for many common and highly effective machine learning
algorithms (neural networks, linear models, random forests, boosting,
support vector machines, etc). Advanced seminars include
parallelization using `mlr3batchmark` package. Example: [The
importance of hyper-parameter tuning blog
post](https://tdhock.github.io/blog/2024/hyper-parameter-tuning/).

### Advanced cross-validation for evaluating machine learning model predictions

Have you ever wondered if your machine learning model trained on this
year will still be accurate next year? Or if a model trained on data
from one country would be as accurate in another country? Or if your
machine learning algorithm would get better predictions if you had
more training data? We teach how to answer these questions with the
easily paralellizable implementation of cross-validation in our
[`mlr3resampling`](https://github.com/tdhock/mlr3resampling?tab=readme-ov-file#installation)
R package.  Examples: [New code for various kinds of cross-validation
blog post](https://tdhock.github.io/blog/2024/cv-all-same-new/),
[Slides for talk about Same/Other/All K-fold cross-validation
(SOAK)](https://github.com/tdhock/two-new-algos-sci-ml?tab=readme-ov-file#title-abstract-slides).

### Regular expressions (regex) for text parsing and data reshaping

Does any of your data analysis involve scraping data from web pages,
or other text files like server logs? We teach how to use
regex for extracting tabular data from such data. Refactoring text
parsing code using regex can yield big speedups; using modern
packages like [`nc`](https://github.com/tdhock/nc), the code can be
made simple, readable, and maintainable! Examples: [Regex tutorial with exercises
presented at McGill University, Montreal, Quebec,
2015](https://github.com/tdhock/regex-tutorial?tab=readme-ov-file#tutorial-on-named-capture-regular-expressions-in-r-and-python), [Collaborations not allowed blog post about web scraping](https://tdhock.github.io/blog/2024/collaborations-not-allowed/).

### Sequential and time series data analysis

If you work with time series data, you have probably wondered if there
are better analysis algorithms than sliding windows. We teach about
time series data forecasting and optimal change-point detection using
dynamic programming. Example: [3 hour tutorial on optimal change-point
detection algorithms presented at international useR 2017 conference
in Brussels, Belgium](https://github.com/tdhock/change-tutorial).

### Data visualization

Which machine learning algorithm is best for my data set? Which
geographical region is the biggest outlier? What is the state of our
finances this year, relative to previous years? All of these questions
can be convincingly answered, and communicated to others, using data
visualization, which is the art and science of creating graphics that
deliver insights based on your data. Our seminars focus on the
multi-layered grammar of graphics, available via `ggplot2` (static
graphics in R), `plotnine` (static graphics in python), and `animint2`
(our R package for animated interactive graphics rendered on web
pages).  Examples: [The animint2 Manual presented in a tutorial at the
international useR 2016
conference](https://rcdata.nau.edu/genomic-ml/animint2-manual/Ch02-ggplot2.html),
[Visualizing prediction error blog
post](https://tdhock.github.io/blog/2024/viz-pred-err/),
[Video at Toulouse-Datavis 2025](https://www.youtube.com/watch?v=Em6AVJi37zo).

### R package development

Do you often peform similar analyses in multiple different R scripts?
Do you have to update R scripts or functions that were written many
weeks/months/years ago, and you wish there was documentation that can
remind you about how they work? We teach seminars about organizing R
code into packages, complete with functions, tests, documentation,
development on GitHub, and easy installation from CRAN. Example:
[exercises from unsupervised learning class at Northern Arizona
University, Fall
2023](https://github.com/tdhock/2023-08-unsupervised-learning/blob/main/homeworks/Rpkg.org).

### C/C++ code in R packages and python modules

Do you need to use specialized data structures, such as
[`<map>`](https://en.cppreference.com/w/cpp/container/map) container
([red-black
tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)) in C++
Standard Template Library? We teach about how to interface R packages
and python modules with C/C++ code, which can sometimes be necessary
for optimal performance. Example: [Youtube video tutorial series, Make
an R package with C++
code](https://www.youtube.com/playlist?list=PLwc48KSH3D1OkObQ22NHbFwEzof2CguJJ).

### Reproducible analysis and report generation

Do you need to generate reports every day/week/month, based on
constantly updated data sources? We teach reproducible analysis using
`rmarkdown` and `quarto`, which can be used to generate reports in a
variety of output formats (HTML, PDF, Word docx, etc). Example of
daily report generated using `rmarkdown`: [new reverse dependency check
report generated every day to make sure `data.table` is compatible with
packages that depend on
it](https://github.com/Rdatatable/data.table/wiki/Revdep-checks).

### Time and memory efficient R programming

Do you often have to wait for R code to compute results using large
data sets? Or have you run out of memory? We teach seminars about how
to refactor R code to minimize time/memory usage. Topics include code
profiling to determine what lines/functions would benefit from
optimization, and comparative benchmarking to compare time/memory
usage of different code versions (using our proposed
[`atime`](https://github.com/tdhock/atime) package). Example: [When to
NOT write low-level
code?](https://github.com/tdhock/when-c?tab=readme-ov-file#when-to-not-write-low-level-code)

### Massive CPU parallelism

Do you have lots of data sets, or machine learning
algorithms, or train/test splits in cross-validation, that can each be
computed independently? We teach about how to parallelize
[Python](https://tdhock.github.io/blog/2022/cross-validation-cluster/)
and [R](https://tdhock.github.io/blog/2020/monsoon-batchtools/) code,
using software such as SLURM and `batchtools`. Example: [`data.table`
reverse dependency checks involve 1500+ dependent packages, each
checked in parallel, reducing 2-3 weeks of wall time to ~10
hours](https://github.com/Rdatatable/data.table/wiki/Revdep-checks).

### Relative advantages of python and R

Are you an expert in python/pandas, who wonders what are its
advantages/disadvantages relative to R/`data.table`, or other
frameworks such as `tidyverse`, `polars`, `duckdb`, `arrow`, etc? We
teach about the relative strengths/weaknesses of different
libraries/languages, including discussion about functionality, syntax,
and performance.  Example: [Comparing `data.table` reshape to `duckdb`
and
`polars`](https://rdatatable-community.github.io/The-Raft/posts/2024-10-17-duckdb_polars_reshape-toby_hocking/).

### Database management systems

Do you have to store and analyze data that is too large to load into
memory? We teach about R/python interfaces to databases such as
PostgreSQL, as well as alternative storage formats such as CSV, HDF,
`arrow`, `duckdb`, etc.

## Contact and cost

Please email toby.hocking@r-project.org with a description of the programming/teaching project you would like us to do for you, and we can schedule a free discovery call to discuss our proposed solution, with a quote for how much that would cost. 
Discounts are possible for academic and non-profit clients.

Two of our most popular packages are:

* Half day package, US$3000, for two 90-minute seminars:
  * seminar 8:30-10:00.
  * coffee break 10:00-10:30.
  * seminar 10:30-noon.
* Full day package, US$6000, for four 90-minute seminars:
  * seminar 8:30-10:00.
  * coffee break 10:00-10:30.
  * seminar 10:30-noon.
  * lunch break noon-1:30.
  * seminar 1:30-3:00.
  * coffee break 3:00-3:30.
  * seminar 3:30-5:00.
* Travel and hotel expenses would also be required for an in person
  seminar (not applicable if you prefer that we create a virtual
  webinar for your organization).
