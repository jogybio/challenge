### Reference Documentation

# Challenge
Sources ETL Challenge


## Prerequisities
To run this ETL challenge, you´ll need the next prerequisites:

  ###Create buckets
    - gsutil mb -p #PROJECT_ID -c standard -l us-central1 -b on gs://landing-buckets-dev2/re
  ###Upload files .csv   
    - upload result.csv in gs://landing-buckets-dev/result/data/
  ###Create Dataset in #PROJECT_ID
     - bq --location=us-central1 mk --dataset --description "shiny section for videogames (result data engineer challenge)" #PROJECT_ID:challenge

