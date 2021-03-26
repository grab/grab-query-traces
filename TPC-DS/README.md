# TPC-DS hive queries dataset

## Introduction
We are open sourcing our TPC-DS query plans dataset. 

Our TPC-DS contains a total of 5,586 queries constructed from 83 publicly available TPC-DS templates. 

You may download the query plans and the instructions needed to read the data from this repository. 

A sample schema of the plans is listed below.

| Columns | Description |
| ------- | ----------- |
| logical_plan | Logical plan after running Presto command <br> explain (format graphviz) <query> | 
| query | Raw query strings |
| query_name | TPC-DS query template name |
| total_cpu_time | Recorded total CPU timing in minutes |