# ETL Pipeline v1

## Introduction
This code contains the steps to build an ETL pipeline that carries out the following tasks:
- Extracts 400k transactions from Redshift
- Identifies and removes duplicates
- Loads the transformed data to a s3 bucket

## Requirements
The minimum requirements:
- Docker


## Instructions on how to execute the code

1. Clone the repository, and go to the week19 folder
````
git clone https://github.com/shaq31415926/Sep-Bootcamp.git
````

2. Copy the `.env.copy` file to `.env`and fill out the environment variabls.

4. Make sure you have Docker Desktop running

Create the image:
```
docker image build -t etl .
```
Run the etl pipeline using docker:
```