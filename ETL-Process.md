# 👨‍💻 ETL Workflow

## Extract

Used Python and the CoinGecko API to collect live cryptocurrency market data. This was done with the packages requests, os, and pandas.

<img width="562" height="470" alt="image" src="https://github.com/user-attachments/assets/0ac1f54c-0a3d-464e-a11c-09d05f45dd04" />

## Transform

Used pandas to structure and clean the API data. Some timestamps and numeric fields required conversions for compatibility with MySQL.

<img width="571" height="459" alt="image" src="https://github.com/user-attachments/assets/9ee9e1f4-25dc-487f-bb2f-8c85d664e9f6" />

## Load

Used the mysql.connector package to insert processed data into my local MySQL database for persistence and future querying.

<img width="399" height="746" alt="image" src="https://github.com/user-attachments/assets/07c9a821-c067-4eb8-bc48-2d8bbc16f4e2" />

<img width="819" height="313" alt="image" src="https://github.com/user-attachments/assets/f89068c3-61a0-43b5-a6f0-2e6835269461" />
