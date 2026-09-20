# JM1 Software Defect Analysis

## Empirical Analysis of Software Defect-Proneness Using Code Complexity and Size Metrics

This project investigates the association between software size,
cyclomatic complexity, and reported defects using the JM1
software-defect dataset.

## Authors

- Anand Kumar
- Raushan Kumar

Batch: ECE B  
Faculty of Technology, University of Delhi

## Research Questions

### RQ1
Is Lines of Code (LOC) associated with reported defects?

### RQ2
Is McCabe Cyclomatic Complexity associated with reported defects?

### RQ3
Does defect rate vary across Cyclomatic Complexity quartiles?

## Dataset

Dataset: JM1

Domain: Software Defect Prediction

Unit of Analysis: Software Module

Main Metrics:

- Lines of Code (LOC_TOTAL)
- McCabe Cyclomatic Complexity (v(g))
- Defect Status

The analysis uses the data-quality-corrected JM1 dataset.

## Methodology

1. Dataset acquisition
2. Data cleaning
3. Descriptive statistics
4. Point-biserial correlation analysis
5. Visualization
6. Complexity quartile analysis
7. Interpretation
8. QA recommendations

## Results

The analysis found positive associations between Lines of Code,
Cyclomatic Complexity, and reported defect status.

Defect rates also increased across the Cyclomatic Complexity
quartiles.

## Visualizations

The project contains:

- LOC distribution by defect status
- Cyclomatic Complexity distribution by defect status
- Defect rate by complexity quartile

## Tools

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Project Report

The final report is available in the `report/` directory.

## Note on AI Assistance

AI tools were used during development for code assistance,
debugging, explanation, and documentation. The dataset,
analysis execution, statistical outputs, visualizations, and
final report were reviewed by the project authors.

## Limitations

The analysis examines associations rather than causal relationships.
The results are based on a single dataset and should be validated
on additional datasets before applying the identified thresholds
generally.

## References

The complete references and dataset source are provided in the
project report.