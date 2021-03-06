# Python for Excel
##### A Modern Environment for Automation and Data Analysis
###### Felix Zumstein


[Errata](https://www.oreilly.com/catalog/errata.csp?isbn=0636920386926)

## Preface

* P.xiv : _"This book also expects you to use ... at least **Excel 2007** on Windows and **Excel 2016** on MacOS. The locally installed version of Excel that comes with the Microsoft 365 subscription will also work"_

* P.xv : _"Web page ([https://xlwings.org/book](https://xlwings.org/book)) with additional information to help you with this book"_

* P.xv : _Supplemental material is available at [https://github.com/fzumstein/python-for-excel](https://github.com/fzumstein/python-for-excel)_



## Part I. Introduction to Python

### 01. Why Python for Excel
* P.10 : "[xltrail](https://xltrail.com), a Git-based version control system that knows how to deal with Excel files"
* P.11 : "Excel community uses _modern Excel_ to refer to the tools that were added with Excel 2010: most importantly Power Query and Power Pivot"
* P.11 : "Power Query is only partially available on macOS - however, it is being actively developed, so it should be fully supported in a future release of Excel"
* P.11 : "Power Pivot ... remains an add-in and is so far not available on macOS"
* P.12 : "Power BI ... [has] been supporting Python scripts since 2018. ... Accordingly, the hopes are high that one day Python will find an official way into Excel, too"


### 02. Development Environment
* P.25 : "With Anaconda, you should install everything you can via Conda and only use pip to install those packages that Conda can't find"
* P.26 : `conda install plotly xlutils`
* P.26 : `pip install pyxlsb pytrends`
* P.27 : "when you start building real projects, it's good practice to use one Conda or virtual environment for each project"
* P.28 : `jupyter notebook`
* P.33 : "Easiest way to run the Jupyter notebooks of the companion repository in the cloud is by going to its Binder URL ([https://mybinder.org/v2/gh/fzumstein/python-for-excel/1st-edition](https://mybinder.org/v2/gh/fzumstein/python-for-excel/1st-edition))"
* P.36,37 : [VS Code](https://code.visualstudio.com/) : `code` will launch it from Anaconda Prompt. (Cmd-Shift-P will show its 'Command Palette')


### 03. Getting Started with Python

## Part II. Introduction to pandas

### 04. NumPy Foundations
### 05. Data Analysis with pandas
### 06. Time Series Analysis with pandas

## Part III. Reading and Writing Excel Files without Excel

### 07. Excel File Manipulation with pandas
### 08. Excel File Manipulation with Reader and Writer packages

## Part IV. Programming the Excel Application with xlwings

### 09. Excel Automation
### 10. Python-Powered Excel Tools
### 11. The Python Package Tracker
### 12. User-Defined Functions (UDFs)
