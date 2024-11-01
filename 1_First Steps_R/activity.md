 Welcome, Group X! This folder contains all the files and instructions you need for the workshop activity.

   ## 1. Set Up Your Working Directory
   - Open your RStudio and set the working directory to this folder.
   - Example code:
     ```r
     setwd("path/to/your/group/folder")
     ```

   ## 2. Load `tidyverse` Package
   - Load the `tidyverse` package to access helpful functions.
   - Example code:
     ```r
     library(tidyverse)
     ```

   ## 3. Load the Dataset
   - Use the dataset file provided in this folder (e.g., `data.csv`).
   - Example code to load the dataset:
     ```r
     data <- read.csv("data.csv")
     ```

   ## 4. Explore the Dataset
   - Use the following exploration function(s) to learn more about the dataset:
     - **Assigned Function(s)**: `summary()`, `str()`, `head()`, etc.
   - Record your observations here:
     - Summary of findings: 

   ## 5. Calculate Descriptive Statistics
   - Use the assigned descriptive statistic function (e.g., `mean()`, `sd()`) to calculate the required statistics.
   - Create an object to store your result:
     ```r
     my_stat <- mean(data$column_name)
     ```
   - Record your results and observations here:
     - Descriptive statistic result:

   ## Additional Resources
   - For help with R functions, check the official R documentation [here](https://stat.ethz.ch/R-manual/R-devel/library/base/html/00Index.html).
