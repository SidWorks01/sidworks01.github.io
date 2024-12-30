---
title: "Introduction (Under Work) " 
date: 2024-12-29
lastmod: 2024-12-29
tags: []
author: ["Siddhant Gupta"]
description: "Introduction"
summary: "Introduction"
editPost:
    URL: ""
    Text: "GitHub repository"
showToc: true
disableAnchoredHeadings: false

---

## Overview
I am Siddhant Gupta, a third-year undergraduate student pursuing Industrial Engineering at the Indian Institute of Technology (IIT), Roorkee. My research interests focus on the Natural Language Processing, Model Interpretability, Multimodality, LLM Efficiency and Retrieval 
I am a regular contributor at the Cohere for AI (C4AI) community, where I regularly engage in discussions on recent research and developments in NLP, Multi-Agentic AI systems, Contextual learning, Synthetic data generation and Mechanistic Interpretability. I also lead teams in multiple AI hackathons as part of my role in my university’s ArIES (Artificial Intelligence and Electronic Society) club, guiding them toward achieving CV and NLP alignment. I am also involved with the Computational Intelligence and Operations Laboratory (CIOL), where my work centers on fine-tuning models across multiple modalities and providing solutions for multilingual text-based challenges.

---

## View dataset

+ Irregular verbs in Portugese: [data](https://github.com/pmichaillat/feru)
+ Irregular verbs in Italian: [data](https://github.com/pmichaillat/unemployment-gap)
+ Irregular verbs in French: [data](https://github.com/pmichaillat/job-rationing)
+ Irregular verbs in Spanish: [data](https://github.com/pmichaillat/countercyclical-multiplier)

---

## Source of data

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


---

## Using data with Python

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Start Python:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

```python
import numpy as np
import pandas as pd
```

### Open the file:

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat `data.csv`.

```python
file_path = 'data.csv'
with open(file_path, 'r') as file:
```

### Read data:

Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.

```python
    lines = file.readlines()
```

### Parse and process data:

Duis aute `line_data` irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur `data.extend`.

```python
data = []
for line in lines:
    line_data = line.strip().split(',')  # Split the line into a list of values
    line_data = [float(value) for value in line_data]  # Convert values to floats
    data.extend(line_data)  # Extend the main list with values from the line
```

#### Compute summary statistics using NumPy:

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum: `data_array`. 

```python
data_array = np.array(data)  # Convert the list to a NumPy array
mean = np.mean(data_array)
median = np.median(data_array)
std_dev = np.std(data_array)
min_value = np.min(data_array)
max_value = np.max(data_array)
```

#### Display summary statistics:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat `print`.

```python
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Standard Deviation: {std_dev}")
print(f"Minimum Value: {min_value}")
print(f"Maximum Value: {max_value}")
```

---

## Description of simulation parameters

| Parameter |   Value   |  Language  | Time period |           Description            |
| :-------: | :-------: | ---------- | :---------: | :------------------------------: |
|  $\alpha$ |   $1/2$   | French     |  1930–1954  |         Tempor dolor in          |
| $\lambda$ |   $e/2$   | French     |  1930–1954  |       Fugiat sint occaecat       |
|  $\gamma$ |  $\ln(3)$ | Spanish    |  1833–1954  |      Duis officia deserunt       |
|  $\omega$ | $10^{-4}$ | Italian    |  1930–1994  | Excepteur et dolore magna aliqua |
|  $\sigma$ |   $1.5$   | Portuguese |  1990–2023  |         Lorem culpa qui          |
|  $\chi^2$ |  $\pi^2$  | Portuguese |  1990–2023  |         Labore et dolore         |
