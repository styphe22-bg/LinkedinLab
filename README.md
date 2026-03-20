# LinkedinLab


## Architecture

Le projet suit une architecture medallion :

Bronze : ingestion brute depuis S3

Silver : nettoyage, structuration, enrichissement

Gold : datasets métiers pour analyses et visualisations

## Technologies

Snowflake SQL

External Stage S3

COPY INTO

JSON / VARIANT

Streamlit in Snowflake

## Analyses produites

top 10 titres par industrie 

top 10 postes les mieux rémunérés par industrie

répartition des offres par taille d’entreprise

répartition par secteur

répartition par type d’emploi
