# Healthcare Service Distribution Analysis in Indonesia

## Overview
Access to healthcare services is an essential component of public health and social development. However, healthcare infrastructure is often unevenly distributed, particularly in geographically large countries such as Indonesia.

This project analyzes the distribution of healthcare services across Indonesian provinces using hospital data. The analysis evaluates disparities in healthcare accessibility by examining key indicators such as the number of hospitals, bed capacity, healthcare workforce, and available medical services.

To better measure accessibility, this project introduces a **Healthcare Access Index**, a composite indicator that combines multiple healthcare infrastructure metrics into a single score. The results are visualized through statistical charts and geographic maps to highlight regional differences in healthcare availability.

---

## Project Objectives

The main objectives of this project are:

- Analyze the distribution of healthcare infrastructure across Indonesian provinces
- Identify regional disparities in healthcare accessibility
- Develop a Healthcare Access Index to evaluate service availability
- Visualize healthcare distribution using charts and spatial maps
- Provide insights that may support healthcare planning and policy development

---

## Dataset

The dataset used in this project contains detailed information about hospitals across Indonesia.

Key attributes include:

- Hospital name
- Province and city location
- Hospital classification
- Ownership type
- Total bed capacity
- Number of healthcare services available
- Healthcare workforce information

The data is aggregated at the **province level** to evaluate healthcare infrastructure distribution.

Dataset Source:  
Kaggle – *Hospital Data in Indonesia*

---

## Methodology

The analysis follows several steps:

### 1. Data Collection
Hospital datasets were imported into the analysis environment using Python.

### 2. Data Cleaning
The preprocessing process included:

- Standardizing province names
- Handling missing values
- Aggregating hospital data by province

### 3. Feature Engineering
Several healthcare indicators were calculated, including:

- Total number of hospitals per province
- Total bed capacity
- Total healthcare workforce
- Total health services available

### 4. Healthcare Access Index
A composite index was created to measure healthcare accessibility across provinces.

The index combines four normalized indicators:

- Hospital availability
- Bed capacity
- Healthcare workforce
- Service availability

Each component contributes equally to the overall index.

### 5. Data Visualization
The project uses several visualization techniques:

- Bar charts for healthcare services comparison
- Choropleth maps for spatial healthcare distribution
- Geographic visualization of healthcare accessibility

### 6. Spatial Analysis
Using geographic boundary data of Indonesian provinces, healthcare indicators were mapped to visualize regional disparities in healthcare infrastructure.

---

## Tools and Technologies

**Programming Language**
- Python

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Geopandas
- Folium

**Platform**
- Google Colab

**Visualization Methods**
- Bar charts
- Spatial mapping
- Choropleth visualization

---

## Project Structure

```
healthcare_distribution_analysis
│
├── healthcare_distribution_analysis.ipynb
├── README.md
└── dataset
```

---

## Key Insights

The analysis reveals several important patterns in healthcare service distribution across Indonesia.

### Concentration of Healthcare Infrastructure
Provinces located in Java such as **West Java, East Java, and DKI Jakarta** have significantly higher numbers of hospitals, healthcare services, and medical workforce.

This indicates that healthcare infrastructure tends to concentrate in densely populated and economically developed regions.

### Regional Healthcare Inequality
Several provinces outside Java show lower healthcare infrastructure availability. This suggests potential limitations in healthcare accessibility for residents in those regions.

### Importance of Infrastructure Development
The findings highlight the importance of expanding healthcare infrastructure in underserved regions to ensure more equitable healthcare access across Indonesia.

---

## Visualization

The project includes several visual outputs:

- Healthcare service comparison across provinces
- Geographic maps showing healthcare distribution
- Spatial visualization of the Healthcare Access Index

These visualizations help identify areas with limited healthcare access.

---

## Future Improvements

Future work may include:

- Incorporating population data to measure healthcare services per capita
- Performing geographic accessibility analysis (distance to hospitals)
- Developing interactive dashboards
- Applying machine learning models to predict healthcare infrastructure needs

---

## Author

**Muhammad Abrar Rayhan**
