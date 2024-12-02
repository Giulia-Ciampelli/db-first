# Consegna:
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Nome tabella:
Cars

## Struttura tabella:
- ID | BIGINT - AUTO_INCREMENT - PRIMARY_KEY(NOTNULL, UNIQUE)
- model | VARCHAR(30) - NOTNULL
- price | INT - FLOAT(8, 2) - NOTNULL
- registration_year | DATE - NOTNULL
- mileage | VARCHAR(12) - NULL
- fuel_type | VARCHAR(16) - NULL
- gearbox_type | VARCHAR(12) - NULL
- power | VARCHAR(20) - NULL
- engine_size | VARCHAR(10) - NULL
- seller | VARCHAR(20) - NULL
- seat_number | TINIYINT - NULL
- door_number | TINIYINT - NULL
- smoker | TINYINT - DEFAULT(0)
- origin_country | VARCHAR(30) - NULL
- description | TEXT(300) - NULL