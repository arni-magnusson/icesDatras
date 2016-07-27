[![Build Status](https://travis-ci.org/ices-tools-prod/icesDatras.svg?branch=master)](https://travis-ci.org/ices-tools-prod/icesDatras)
[![CRAN Status](http://www.r-pkg.org/badges/version/icesDatras)](https://cran.r-project.org/package=icesDatras)

[<img align="right" alt="ICES Logo" width="17%" height="17%" src="http://www.ices.dk/_layouts/15/1033/images/icesimg/iceslogo.png">](http://www.ices.dk/Pages/default.aspx)


icesDatras
======

icesDatras implements R functions that access the webservices of the [ICES (International
Council for the Exploration of the Sea)](http://www.ices.dk/Pages/default.aspx) [DATRAS trawl database](http://ices.dk/marine-data/data-portals/Pages/DATRAS.aspx).

icesDatras is implemented as an [R](https://www.r-project.org) package and will in future be available on
[CRAN](https://cran.r-project.org/package=icesDatras).



Installation
------------

icesDatras can be installed from CRAN using the `install.packages` command:

```R
install.packages('icesDatras')
```


Usage
-----

For a summary of the package
```R
library(icesDatras)
?icesDatras
```





References
----------

Overview of the ICES advisory process:

[http://ices.dk/community/advisory-process/Pages/default.aspx](http://ices.dk/community/advisory-process/Pages/default.aspx).

ICES list of software applications:

[http://ices.dk/marine-data/tools/Pages/Software.aspx](http://ices.dk/marine-data/tools/Pages/Software.aspx).

ICES Datras Webservices:

[https://datras.ices.dk/WebServices/Webservices.aspx](https://datras.ices.dk/WebServices/Webservices.aspx).


Development
-----------

icesDatras is developed openly on [GitHub](https://github.com/ices-tools-prod/icesDatras). 
Feel free to open an [issue](https://github.com/ices-tools-prod/icesDatras/issues) there if you encounter problems or have suggestions for future versions.

The current development version can be installed using:

```R
devtools::install_github('ices-tools-prod/icesDatras')
```