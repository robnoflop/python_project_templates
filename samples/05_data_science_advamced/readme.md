# Project Organization

├── data                <- project data
│   ├── interim         <- Intermediate data that has been transformed.
│   ├── metadata        <- Data that's needed to understand or transform data.
│   ├── processed       <- The final, canonical data for datasets.
│   ├── raw             <- The original, immutable data dump.
├── datacatalog         <- place for a datacatalog where source data is documented
├── docs                <- A default Sphinx project; see sphinx-doc.org for details
├── experiments         <- experimentation documentation
├── models              <- place for trained models
├── notebooks           <- Jupyter notebooks. Naming convention is a number (for ordering)
│                          and a short `-` delimited description, e.g. `1.0-data-exploration`.
├── src
│   ├── [lib_name]      <- The module of this project.
│   ├── scripts         <- These scripts are used for operalization and standardtization
├── tests               <- 
├── .gitignore          <- defines files and folders that should not be commited to repository -> see https://www.pluralsight.com/guides/how-to-use-gitignore-file
├── readme.md           <- The top-level readme for developers using this project.
├── requirements.txt    <- List of all dependencies that are needed to execute the project.