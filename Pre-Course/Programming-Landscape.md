# The Programming Landscape
When you are first beginning to program, you will hear a bewildering array of terms, and it can be difficult to understand what they all mean and how they fit together. The following guide, adapted from one provided by [the Lede Program](http://ledeprogram.com/), provides a good summary of some of the most common terms you might hear.  
   
Python: Python is a multipurpose programming language that is at home crunching, parsing text, or building Twitter bots, and is the most popular language for data science work.  
  
R: R is a programming language that is used widely for mathematical and statistical processing and thus a popular language among data scientists.
  
C++: A heavy-lifting programming language that is the language of choice for many university Computer Science Departments. It’s far faster than Python or JavaScript and introduces you to the nitty-gritty of computer science. And yes, it’s based on a language called C.  
  
JavaScript: JavaScript is a programming language that’s in charge of interactivity on the web. When images wiggle or popups annoy you, that’s all JavaScript. While it’s historically been used for the fronted (i.e., your browser),  JavaScript has making inroads the past few years into the backend via node.js.  
  
HTML: HTML isn’t technically a programming language, it’s a markup language. A hypertext markup language, to be exact. HTML is used to explain what different parts of web pages are to your browser – this is a paragraph, there’s a header over there, maybe a footer down at the bottom of the page.
  
Markdown: Markdown is a specific markup library that allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). [Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a great cheatsheet that I always reference when writing Markdown.  
  
CSS: If the web were left to its own devices, it would be nothing but black text on a white background. Web developers use CSS – cascading style sheets – to dress it up. Headlines become bold, links change colors, and tables get backgrounds all thanks to CSS.  
  
git: While git isn’t a programming language, it’s certainly often used with them – it’s a version control system. Version control is a way of keeping track of the history of your code, along with providing a structure that encourages collaboration. Github is the most popular cloud-based service for keeping track of your code using git.

### Tools for Data Analysis
  
Jupyter Notebook: Jupyter Notebooks are an interactive programming environment that encourage documentation, transparency, and reproducibility of work. When you’re done with your analysis, you’ll be able to put your work up for everyone to see (and check).  
  
Pandas: Pandas is a high-performance Python package for data wrangling. In this course we will also be using the GeoPandas package, which takes the core concept of the Pandas dataframe and leverages it for spatial analysis.
  
scikit-learn: scikit-learn is a Python package for machine learning and data analysis. It’s the Swiss Army knife of data science: it covers classification, regression, clustering, dimensionality reduction, and so much more.

### Some Common Data Formats
##### Structured Data: RDBMS
In many cases, data is stored within a database. Although there are many different kinds of databases, the most well-known type is a [relational database management system](https://en.wikipedia.org/wiki/Relational_database) (RDBMS), where data is organized into rows and columns. For data science work, we will typically have each row / record representing a data point, and each column representing a value / feature. 

Within organizations, databases will typically be the starting point for any analytical work, and you will most likely use some version of Structured Query Language (SQL) to work with this data. I _**highly**_ recommend you spend time some time learning the basics of SQL, since it is an indispensible language for working with data. In fact, roughly 75% of my work is completed within databases using SQL.

##### Structured Data: CSV
The most common format for importing / exporting data from spreadsheets and databases is a CSV (comma-separated-values) file, defined in [RFC 4180](https://tools.ietf.org/html/rfc4180.html#page-2). Within a CSV, each _record_ is separated by a line break. Each record typically has multiple _fields_, and these fields are typically delimited by a comma (,) value, though you will often see fields delimited by other values such as the pipe character (|) or tabs. Well-documented datasets will often contain metadata that clarifies this kind of information. Because the CSV file adheres to the same row-column structure that you will find in a relational database system, it is also referred to as _structured_ data.

##### Semi-Structured Data: JSON & XML
JSON & XML are referred to as semi-structured datasets since they not are strictly organized in a relational format with columns and rows, yet they have some organizational structure to them. This structure may be clear from looking at documentation; however, in many cases you will need to inspect the data to understand the structure.
