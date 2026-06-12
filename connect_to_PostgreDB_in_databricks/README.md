# Databricks kapcsolódás PostgreSQL adatbázishoz

Ez a mappa rövid útmutatókat tartalmaz arról, hogyan lehet egy Neon PostgreSQL adatbázist létrehozni, majd Databricks környezetből elérni és adatokat beolvasni belőle.

## Tartalom

* [neon_postgres_leiras.md](./neon_postgres_leiras.md) – PostgreSQL adatbázis és teszttábla létrehozása Neon-ban.
* [databricks_neon_jdbc_leiras.md](./databricks_neon_jdbc_leiras.md) – Kapcsolódás Neon PostgreSQL adatbázishoz Databricks notebookból JDBC használatával.
* [databricks_postgresql_data_ingestion_leiras.md](./databricks_postgresql_data_ingestion_leiras.md) – PostgreSQL adatforrás beállítása és Data Ingestion pipeline előkészítése Databricks-ben.

## Cél

A példák bemutatják, hogyan lehet külső PostgreSQL adatforrást összekapcsolni Databricks-szel, majd az adatokat lekérdezni vagy ingestion folyamaton keresztül betölteni.

## Használt technológiák

* Databricks
* Neon PostgreSQL
* JDBC
* Apache Spark
* Databricks Data Ingestion
