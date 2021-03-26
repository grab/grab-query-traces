# prestroid-sigmod-double-blind-release

## Introduction
We are open sourcing our MTX Presto query plan dataset. 
Instructions needed to read the data are attached alongside the data itself. 

**We have set up this temporary site to access the data for Sigmod's double blinded review phase**

## How to access the data?

### MTX-Traces queries dataset
We will release the data only on a request basis.

All plans have been encoded to remove company confidential details, yet preserve the shape, structure and contextual usage of tokens within the plans. 

| Columns | Description |
| ------- | ----------- |
| logical_plan_anonymized | Logical plan after running Presto command <br> explain (format graphviz) <query> | 
| total_cpu_time_lg_norm | Recorded total CPU timing in minutes |

If you are interested to access it, please email mtx-prestroid@googlegroups.com with the following details
- Full name
- Company
- Purpose of usage
- Email address

We will send the data over to your specified email address once approved.

### TPC-DS hive queries dataset
Please see [tpc-ds](TPC-DS/)

### Licensing 
All MTX related data is under the MIT open source licensing scheme. 
For more details, please see [licensing](LICENSE)