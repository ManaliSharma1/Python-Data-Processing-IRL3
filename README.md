# Python Data Processing — Practical Assignment

This repository presents solutions to six applied data-processing tasks implemented in Python.  
The work emphasizes practical usage of core Python data structures to handle real-world style datasets.

## Assignment Focus

The objective of this assignment is to strengthen problem-solving ability using:

- Dictionaries for mapping and counting
- Lists for structured data handling
- Tuples for fixed data pairing
- Strings for text processing and analysis

Each problem reflects a scenario commonly encountered in analytics, data cleaning, or system monitoring.

## Implemented Problems

### 1️ Employee Performance Bonus Eligibility
Determines the highest-performing employees based on score values and handles cases where multiple employees share the top score.

**Techniques Used**
- Extracting values from dictionaries
- Comparing numeric performance metrics
- Handling ties using list comprehension

### 2️ Search Query Keyword Analysis
Processes search queries to identify frequently used keywords by normalizing and counting occurrences.

**Techniques Used**
- String normalization using `.lower()`
- Tokenization using `.split()`
- Frequency dictionary creation

### 3️ Sensor Data Validation
Filters valid sensor readings based on defined criteria and pairs each valid value with its corresponding time index.

**Techniques Used**
- Conditional filtering from lists
- Data pairing using `enumerate()`
- Structured tuple creation

### 4️ Email Domain Usage Analysis
Evaluates user email data to calculate the percentage share of different email service providers.

**Techniques Used**
- Substring extraction from strings
- Frequency calculation
- Percentage distribution computation

### 5️ Sales Spike Detection
Analyzes daily sales values to identify unusually high performance days based on deviation from the average.

**Techniques Used**
- Mean value calculation
- Threshold-based condition checking
- Analytical flag generation

### 6️ Duplicate User ID Detection
Examines user registration data to detect repeated IDs and quantify duplicates for integrity validation.

**Techniques Used**
- Counting occurrences using dictionaries
- Iterating through structured data
- Duplicate detection logic
