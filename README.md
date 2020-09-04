# concat-large-files

This repo is an example about how to concat large files using Node.js

## Running

Restore dependencies with `npm ci`

1. There are the concatener in [./index.js](index.js) that will concat all `.csv` files and generate the `final.csv` file with all entries. It will convert data from csv, on `name` field it will replace spaces by underscore ( `_` ) then convert to csv again and finally save its output on `final.csv`.

## Download files from Kaggle

2018: https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey?select=survey_results_public.csv
2017: https://www.kaggle.com/stackoverflow/so-survey-2017?select=survey_results_public.csv
