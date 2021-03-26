# Grab-Traces dataset

## Introduction
We are open sourcing our Grab-Traces query plans dataset. 

Grab-Traces contains 19,876 unique Presto query plans sampled from queries issued to Grab's datalake.

Instructions needed to read the data will be attached alongside the data itself. 

## How to access the data?

We will release the data only on a request basis.

All plans have been encoded to remove company confidential information. Only the shape, structure and contextual usage of tokens within the plans. 

A sample schema of the plans is listed below.

| Columns | Description |
| ------- | ----------- |
| logical_plan_anonymized | Logical plan after running Presto command <br> explain (format graphviz) <query> | 
| total_cpu_time_lg_norm | Recorded total CPU timing in minutes |

If you are interested to access it, please email grab.prestroid@grabtaxi.com with the following details
- Full name
- Company
- Purpose of usage
- Email address

In addition, please ensure that the following [NDA][NDA_grab_traces_dataset.pdf] form is signed and e-mailed to us. 

We will send the data over to your specified email address once approved.

### TPC-DS hive queries dataset
Please see [tpc-ds](TPC-DS/)