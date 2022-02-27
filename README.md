# big-data-challenge
Repo for Big Data Homework

The level-1 folder contains 2 ipynb notebooks created with Google Colab.  Before running them use the schema.sql file to create a db in postgres.

After running the first notebook (I ran the video game file first) it would be advantageous to run the statements in the delete.sql file (also located in the resources folder) to empty the db to 
ensure no problems occur with duplicate keys between datasets.  Each notebook checks for duplicates within its own set, but does not then go and check against the db 
itself as this was not stipulated as a requirement in the instructions or the rubric.