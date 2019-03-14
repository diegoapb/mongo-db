FROM mongo
COPY db.csv /db.csv
CMD mongoimport --host mongodb --db cancerColon --collection arts --type csv --headerline --file /db.csv