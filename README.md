# mirt

Multidimensional item response theory in R.

## Description

Analysis of dichotomous and polytomous response data using unidimensional and
multidimensional latent trait models under the Item Response Theory paradigm.
Exploratory and confirmatory models can be estimated with quadrature (EM) or
stochastic (MHRM) methods. Confirmatory bi-factor and two-tier analyses are available
for modeling item testlets. Multiple group analysis and mixed effects designs also
are available for detecting differential item functioning and modeling item and
person covariates.

## Examples and evaluated help files are available on the wiki

Various examples and worked help files have been compiled using the `knitr` package to generate
HTML output, and are available on the package [wiki](https://github.com/philchalmers/mirt/wiki). 
User contributions are welcome!

## Installing from source

It's recommended to use the development version of this package since it is more likely to be up to date
than the version on CRAN. To install this package from source:

1) Obtain recent gcc, g++, and gfortran compilers. Windows users can install the
   [Rtools](http://cran.r-project.org/bin/windows/Rtools/) suite while Mac users will have to
   download the necessary tools from the [Xcode](https://itunes.apple.com/ca/app/xcode/id497799835?mt=12) suite and its
   related command line tools (found within Xcode's Preference Pane under Downloads/Components); most Linux
   distributions should already have up to date compilers (or if not they can be updated easily). 
   Windows users should include the checkbox option of installing Rtools to their path for 
   easier command line usage.

2) Install the `devtools` package (if necessary). In R, paste the following into the console:

```r
install.packages('devtools')
```

3) Load the `devtools` package (requires version 1.4+) and install from the Github source code.

```r
library('devtools')
install_github('philchalmers/mirt')
```

### Installing from source via git

If the `devtools` approach does not work on your system, then you can download and install the
repository directly. 

1) Obtain recent gcc, g++, and gfortran compilers (see above instructions).

2) Install the [git command line tools](http://git-scm.com/downloads).

3) Open a terminal/command-line tool. The following code will download the repository 
code to your computer, and install the package directly using R tools 
(Windows users may also have to add R and git to their 
[path](http://www.computerhope.com/issues/ch000549.htm))

```
git clone https://github.com/philchalmers/mirt
R CMD INSTALL mirt
```

# Upcoming IRT Workshops

*Two day workshop at the* [University of Zurich, Switzerland](http://www.zhrcourses.uzh.ch/programm/datenanalyse/irt-analysis_en.html)

# Bugs and Questions

Bug reports are always welcome and the preferred way to address these bugs is through
the Github 'issues'. Feel free to submit issues or feature requests on the site, and I'll
address them ASAP. Also, if you have any questions about the package, or IRT in general, then
feel free to create a 'New Topic' in the
[mirt-package](https://groups.google.com/forum/#!forum/mirt-package) Google group. Cheers!
