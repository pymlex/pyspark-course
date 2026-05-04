# PySpark Course

<img width="800" height="451" alt="image" src="https://github.com/user-attachments/assets/b5e421ce-ff2f-4fcf-a1ba-28aa8c033b41" />

## Overview

These are lectures on PySpark. The material covers the main concepts behind distributed data processing, together with practical examples of data manipulation, SQL, joins, windows, caching, partitioning, and optimisation. The material is organised as a learning path from core architecture to more advanced engineering patterns.

## Content

- Big Data concepts and Spark architecture
- Lazy evaluation, jobs, stages, and tasks
- Driver, executors, resource managers, and YARN
- PySpark data reading and writing
- Schemas, transformations, and basic DataFrame operations
- String processing, date handling, null processing, and UDFs
- Aggregations, joins, pivots, and window functions
- Spark SQL and query planning
- AQE, caching, repartitioning, and coalesce
- Auto Loader, Delta Lake, SCD, and streaming
- RDDs, partitions, salting, and Z-ordering

## Topics

### 1. Spark architecture

First, we discuss how Spark splits work between the driver, executors, and the resource manager, and how jobs are converted into stages and tasks.

### 2. Data processing

Practical examples of reading CSV and JSON files, defining schemas, filtering, selecting, sorting, deduplicating, joining, and aggregating data.

### 3. Spark SQL

The SQL part covers query execution, logical and physical plans, Catalyst optimisation, joins, broadcast, and window functions.

### 4. Performance and engineering

Here we examine advanced concepts such as AQE, partition pruning, caching, Parquet, Delta Lake, Auto Loader, SCD, dynamic allocation, salting, and Z-ordering.

## Provenance 

Most of the practice is based on materials by [Ansh Lamba](https://www.youtube.com/@AnshLambaJSR).
