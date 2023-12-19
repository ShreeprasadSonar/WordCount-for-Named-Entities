# Named Entity Word Frequency Analysis using PySpark/Scala and NLP Libraries

This project aims to compute word frequency for named entities in a large text file using a MapReduce approach with PySpark/Scala and NLP libraries. It follows these main steps:

## Steps

### 1. Data Collection
- Find a large text file from the Gutenberg project [here](https://www.gutenberg.org) and upload it to your Databricks cluster.

### 2. Named Entity Extraction
- Utilize an NLP library compatible with Scala/PySpark (e.g., NLTK or John Snow Labs) to extract only the named entities from the text file.

### 3. MapReduce Implementation
- Develop code for a MapReduce program that performs word count specifically on the extracted named entities.

### 4. Map Task Output
- Ensure the output from the map task is structured as (key, value) pairs, where the key represents the named entity, and the value denotes its count (i.e., the frequency of occurrences).

### 5. Reducer Output
- Sort the output from the reducer in descending order of count. This means that the named entity with the highest frequency should appear at the top of the output.

## Usage
- The notebook provided in this repository demonstrates how to perform these steps in a Databricks environment. You can find the notebook [here](link/to/your/notebook).

## Libraries Used
- NLTK library ([documentation](https://www.nltk.org/))

## Instructions
1. Clone this repository.
2. Follow the notebook instructions to execute the named entity word frequency analysis.
3. Feel free to modify the code according to your requirements or test it with different texts from the Gutenberg project.
