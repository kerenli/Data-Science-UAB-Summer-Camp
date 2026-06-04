# Data-Science-UAB-Summer-Camp

Welcome to the official repository for the **Data Science UAB Summer Camp**, a summer outreach program organized by the Department of Mathematics at the University of Alabama at Birmingham (UAB).

This repository contains lecture materials, datasets, coding tutorials, and project resources used throughout the camp. The goal of the camp is to introduce motivated high school students to mathematics, statistics, data science, and machine learning through hands-on learning and real-world applications.

## Getting Started

1. Clone or download this repository.
2. Install R and RStudio.
3. Open the materials in the root folder.
4. Verify that datasets in the `data/` folder are accessible.
5. Complete **Lecture 0: Introduction to R** before the start of camp.

## Camp Overview

The Data Science UAB Summer Camp is designed for high school students interested in mathematics, data science, artificial intelligence, and related STEM fields.

Students will learn:

- Statistical thinking and data analysis
- Introduction to machine learning
- Applied mathematics for data science
- Data visualization and communication
- Mathematical modeling
- Team-based project development using real-world datasets

Programming activities primarily use **R**, with instruction provided through **RStudio** and **JupyterLab**.

## Repository Structure

```text
Data-Science-UAB-Summer-Camp/
│
├── README.md
│
├── Lecture0.ipynb
├── Lecture1.ipynb
├── Lecture2.ipynb
├── ...
│
├── data/
│   ├── dataset1.csv
│   ├── dataset2.csv
│   └── ...
│
└── projects/
    ├── Project1/
    ├── Project2/
    └── ...
```

## Software Installation

### Install R

Download and install R from:

https://cran.r-project.org/

### Install RStudio

Download and install RStudio Desktop from:

https://posit.co/download/rstudio-desktop

### Install JupyterLab (Optional)

Students familiar with Python may also wish to use JupyterLab.

```bash
pip install jupyterlab
```

To use R within JupyterLab:

```r
install.packages("IRkernel")
IRkernel::installspec()
```

## Working with the Repository

Many examples in the lectures load datasets from the `data/` folder using relative paths such as:

```r
police <- read_csv("data/il_chicago_2023_01_26.csv")
```

The file path above assumes that:

- The notebook is located in the main project directory.
- The dataset is located in the `data/` subfolder.

Please keep the folder structure unchanged after downloading the repository.

This approach uses **relative paths**, which makes projects easier to share and reproduce across different computers.

## Camp Topics

The camp includes modules on:

- Introduction to Statistical Methods in Data Science
- Introduction to Machine Learning
- Advanced Machine Learning and AI
- Linear Algebra in Data Science
- Probability and Statistics in Data Science
- Monte Carlo Markov chains for computation
- Mathematical Modeling
- Data Analysis and Communication
- Team-Based Data Science Projects

## Camp Director

**Keren Li**  
Assistant Professor  
Department of Mathematics  
University of Alabama at Birmingham

The camp is supported by faculty, graduate teaching assistants, and staff from the Department of Mathematics.

## Contact

For questions regarding the camp or repository, please contact:

**Keren Li**  
Department of Mathematics  
University of Alabama at Birmingham  
Email: kli@uab.edu

## Acknowledgments

The Data Science UAB Summer Camp is organized by the Department of Mathematics at UAB with the goal of promoting mathematics, statistics, data science, and machine learning education among high school students.

## License

All lecture materials are intended for educational use. Please contact the repository maintainers before redistributing or modifying course materials.
