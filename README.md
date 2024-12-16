# dbt_demo1

## Description
This project aims to examine how DBT (Data Building Tool) is used in building and managing SQL pipelines in a BigQuery (GCP).

## Data
We are using the BQ public dataset called 'medicare'.

## Methodology
1. Set up DBT, GitHub and a Google Cloud Platform (GCP) accounts (free is ok).
2. Set up a repository at GitHub for your project.
3. Create a JSON key from your project in GCP.
4. Connect DBT to GCP using said key.
5. Connect DBT to GitHub (or any other Version Control System of choice) so that you save your files
6. Create a new Dataset under your project in BQ.
7. Run DBT to produce two tables under your dataset in BQ.
8. Run a basic SQL Transformation query in BQ, under your dataset.
9. Copy the SQL query in DBT, under models.
10. Run DBT. It will materialze the resulting query as a view.
11. To change the view to a table, we can change the query in DBT to include code to materalize as a table.

I would like to acknowledge the YouTube channel 'SkillCurb' and its video [Google BigQuery and DBT| Build SQL Data Pipeline - Hands on lab](https://youtu.be/_C_pYeuF6_s?si=CrY2Vf8XqNJtsYtU)

## Results
In this small project, we have been able to use DBT connected to BQ making a simple transformation.
The takeaway for me was that you can engineer SQL scripts and run them in a sequence of dependency that you have previously set up in DBT.
It is basically handling the set up of pipelines in an orderly fashion where you can execute the run of the whole DBT model from one place. 

## Usage
To run the code, clone this repository and ensure you follow the steps in Methodology.

## License
This project is licensed under the MIT License.

## Contact
For inquiries, please reach out to [Micael Gustavsson](mailto:micael.gustavsson@intrepid.se).
