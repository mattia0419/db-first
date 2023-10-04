## DB FIRST
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!
Esempio:
COLONNA | TIPO | ATTRIBUTI
-- | -- | --
marca | varchar(50) | NOT NULL
modello | varchar(50) | NOT NULL
ecc..
##
COLONNA | TIPO | ATTRIBUTI
-- | -- | --
Chassis|BIGINT|PRIMARY KEY
Brand|VARCHAR(50)|NOTNULL
Model|VARCHAR(50)|NOTNULL
Displacement|SMALLINT|UNSIGNED, NULL
Production Year|YEAR|NOTNULL
Price|MEDIUMINT|NOTNULL, UNSIGNED
Number Of Owners|TINYINT|UNSIGNED, DEFAULT(1)
Note|TEXT|NULL
Plate|CHAR(7)|NOTNULL
Km|MEDIUMINT|UNSIGNED, NOTNULL
Fuel|VARCHAR(25)|NOTNULL






