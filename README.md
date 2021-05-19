# Starksbigdataproject

One of the major concerns of the world are accidents and it is a challenge faced by governments across the globe. In recent decades, accident analysis has been the main area of research.

Datasets:
https://www.kaggle.com/sobhanmoosavi/us-accidents
https://public.opendatasoft.com/explore/dataset/us-cities-demographics/table/?dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6InVzLWNpdGllcy1kZW1vZ3JhcGhpY3MiLCJvcHRpb25zIjp7fX0sImNoYXJ0cyI6W3siYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6ImNvbHVtbiIsImZ1bmMiOiJBVkciLCJ5QXhpcyI6Im1lZGlhbl9hZ2UiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjRkY1MTVBIn1dLCJ4QXhpcyI6ImNpdHkiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIn1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D


Steps:
1) Cleaned data using Pandas
2) Loaded cleaned data in S3
3) Transferred the data from S3 to redshift using AWS Glue job and scripts
4) Connnecting redshift with Tableau and Sagemaker
