# MiniSparkRDD


---

## Project Overview

MiniSparkRDD is a simplified implementation of Apache Spark's Resilient Distributed Dataset (RDD) framework developed using Python. The project demonstrates how distributed data processing works by implementing core concepts such as loading data, creating RDDs, applying transformations, building a Directed Acyclic Graph (DAG), optimizing execution, and executing operations on a dataset.

The project uses an Amazon product dataset stored in CSV format to perform data processing tasks and display the final results.

---

## Objectives

- To understand the working of the RDD programming model.
- To implement Map and Filter transformations.
- To simulate Spark's DAG execution process.
- To optimize the execution pipeline.
- To process CSV datasets efficiently using Python.

---

## Features

- CSV Data Loading
- RDD Creation
- Map Transformation
- Filter Transformation
- DAG Construction
- Query Optimization
- DAG Execution
- Result Display

---

## Project Structure

```
MiniSparkRDD/
│
├── Data/
│   └── amazon.csv
│
├── src/
│   ├── __init__.py
│   ├── loader.py
│   ├── parser.py
│   ├── rdd.py
│   ├── node.py
│   ├── dag.py
│   ├── optimizer.py
│   ├── executor.py
│   └── utils.py
│
├── main.py
├── README.md
└── requirements.txt
```

---

## Folder Description

### Data/

Contains the input dataset.

- **amazon.csv** – Amazon product dataset used for processing.

### src/

Contains the complete implementation of the MiniSparkRDD framework.

- **__init__.py** – Initializes the Python package.
- **loader.py** – Loads the CSV dataset.
- **parser.py** – Parses CSV records.
- **rdd.py** – Implements the RDD class and transformations.
- **node.py** – Defines nodes used in the execution graph.
- **dag.py** – Builds the Directed Acyclic Graph.
- **optimizer.py** – Optimizes the execution plan.
- **executor.py** – Executes the DAG.
- **utils.py** – Contains helper functions.

### main.py

Acts as the entry point of the application. It loads the dataset, creates the RDD, applies transformations, executes the DAG, and displays the final output.

---

## Technologies Used

- Python 3
- CSV
- Object-Oriented Programming (OOP)
- Resilient Distributed Dataset (RDD)
- Directed Acyclic Graph (DAG)

---

## Requirements

- Python 3.x

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## How to Run

Run the project using:

```bash
python main.py
```

---

## Expected Output

The application loads the Amazon dataset, performs RDD transformations, executes the optimized DAG, and displays the processed results in the terminal.

---

## Conclusion

MiniSparkRDD provides a simple understanding of how Apache Spark processes large datasets using the RDD programming model. It demonstrates the complete data processing pipeline, including data loading, transformations, DAG generation, optimization, and execution, making it an effective educational project for learning Big Data concepts.
