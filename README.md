# ETL pipeline for Patient Data

Implemented a pyspark data solution for implementing ETL data pipelines to transform patient data

As required, all the patient sensitive details are removed

raw data is cleaned and columns are transformed to the required data format.

The average of all glucose measurements is calculated and appropriate sugar_level values are given.

Unit tests are written for the functions used. All the appropriate test cases are passed.

The command to execute code is

## spark-submit main.py input_file_path output_file_path


