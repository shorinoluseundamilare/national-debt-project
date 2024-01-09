# National Debt Project

This demonstration is focused on providing an example of using a public application programming interface (API) to retrieve financial data and produce some basic visualizations using the [ggplot2](https://ggplot2.tidyverse.org/) R package. Using the API provided by the [U.S. Treasury Fiscal Data Webpage](https://fiscaldata.treasury.gov), this demo will develop a query to request a [panel of data](https://search.brave.com/search?q=panel+data) that contain the components of the U.S. National Debt over more than 200 months.

This Fiscal Data API is based on a [RESTful API format](https://search.brave.com/search?q=RESTful+API). For more information about the structure of the API, review the [official Fiscal Data API Documentation](https://fiscaldata.treasury.gov/api-documentation/). The goal of this demonstration is to break down the process of creating an API call, sending the request, and parsing the response. In practice, many APIs have 'wrappers' or 'packages' in various programming languages that simplify the coding process to interact with the APIs.

In addition to loading this national debt data, this demo makes use of the ggplot2 package to generate several visualizations of this data. Then for further research into this topic of the national debt and long-term projections, check out the [U.S. Treasury's Financial Report](https://www.fiscal.treasury.gov/reports-statements/financial-report/current-report.html) and the [Long-Term Budget Outlooks from the Congressional Budget Office](https://www.cbo.gov/taxonomy/term/31/recurring-reports).

The data work for this project demo is contained in the R Notebook directory of this repository. On GitHub, the webpage should display the README.md file, which contains the compiled output of the R Notebook. If you wish to explore the source code locally, then you can open the natdebt.Rmd file in RStudio and execute the code chunks to replicate the data work. Note the `output: html_notebook` line in the header of that file, which indicates that the R Markdown document is an R Notebook. 

After exploring the R Notebook and making any desired changes, you can then create a copy that will appear on GitHub. To do this, save a copy of the R Notebook and name it README.Rmd. Then, change the header line to `output: github_document`, which will switch the file from being an R Notebook to an R Markdown file that will compile into a generic [Markdown](https://www.markdownguide.org/) file (.md). This format (along with the README name) will automatically be recognized by GitHub and displayed in-browser. This will also replace the Preview button with an option to Knit the Markdown file. This knitting process will re-run all the code chunks and generate a new README.md file inside of the R Notebook folder, which will display on GitHub.
