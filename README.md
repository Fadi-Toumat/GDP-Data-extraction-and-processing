# GDP Data Extraction and Processing

This repository contains a Jupyter Notebook that demonstrates practical data extraction and transformation techniques using Python.

> **Note:** This notebook is based on exercises from the IBM AI Developer course on Coursera.  
> It is shared here for educational purposes with full respect to the original authors and intellectual property.

## Overview

In this project, I performed data extraction and preprocessing on GDP data sourced from Wikipedia. The goal was to extract a GDP ranking table of countries and perform essential data transformation operations to make it analysis-ready.

## Key Techniques Demonstrated

- Reading HTML tables from a web archive using `pandas.read_html()`
- Selecting and renaming specific columns
- Cleaning the data and converting types
- Performing unit conversions (from million USD to billion USD)
- Exporting the final DataFrame to a `.csv` file
- Using `numpy` and `pandas` for processing

## Notes

- **Use of `lxml`**: Although not explicitly imported in the notebook, the `pandas.read_html()` function relies on the `lxml` or `html5lib` libraries as parsing engines. If `lxml` is installed, it may be used implicitly to parse HTML content.
- **Warnings**: Some warning messages may appear during execution (e.g., `FutureWarning` from `pandas` or formatting warnings). These do not affect the functionality or correctness of the code and are usually related to upcoming changes in future versions of libraries.

## Requirements

- Python 3.x
- pandas
- numpy
- lxml *(used implicitly)*
- Jupyter Notebook

## Files

- `GDP Data extraction and processing.ipynb`: Contains the full step-by-step implementation.
- `Largest_economies.csv`: Output file that contains the final cleaned and processed GDP data in CSV format.

---

Feel free to fork or clone this repository to explore, learn, or extend the notebook for your own projects!
