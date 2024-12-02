# DB STRUCTURE

Modellare la struttura di una tabella per memorizzare tutti i dati
riguardanti delle `auto usate` messe in vendita da un concessionario

## TABLE NAME:

- used cars

## TABLE STRUCTURE:

- ID | BIGINT - AUTO_INCREMENT - PRIMARY_KEY (UNIQUE, NOT NULL)
- car_name | CHAR(20) - NOT NULL
- car_brand | CHAR(20) - NOT NULL
- year_of_registration | YEAR - NOT NULL
- type_of_fuel | CHAR(20) - NOT NULL
- km | SMALLINT - NOT NULL
- price | FLOAT(8,2) - NOT NULL
- sole_owner | CHAR(20) - NULL
- multi_owner | CHAR(20) - NULL
- color | CHAR(20) - NOT NULL
- never_crashed | CHAR(20) - NULL
- displacement (cilindrata veicolo) | SMALLINT - NOT NULL
- manual_transmission | CHAR(20) - NULL
- automatic_transmission | CHAR(20) - NULL
