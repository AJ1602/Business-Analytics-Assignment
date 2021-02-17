# Business-Analytics-Assignment
Code 1
SELECT *  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 5
Code 2
SELECT AVG(fertility_rate_15_19)  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 5
Code 3
SELECT max(fertility_rate_15_19)  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 5
Code 4
SELECT min(fertility_rate_15_19)  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 5
Code 5
SELECT sum(fertility_rate_15_19)  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 5
Code 6
SELECT AVG(total_fertility_rate), country_name as COUNTRY  FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` 
WHERE year > 1980
group by country_name
LIMIT 1000
