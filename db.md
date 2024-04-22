## DB car dealer
# Consegna:

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

# Presupposti:

Parliamo di un dealer che vende auto e modo sia nuove che usate di varie fasce

<!-- Colums -->

<!-- id -->
- **id** | INDEX | BIGINT | PRIMARY KEY | AUTO_INCREMENT | NOT NULL
<!-- es: moto/auto -->
- **type** | VARCHAR(10) | NOT NULL 
<!-- es: ford/ferrari/audi -->
- **brand** | VARCHAR(20) | NOT NULL
<!-- es: focus/audi/supra -->
- **model**  | VARCHAR(20) | NOT NULL
<!-- es: suv/sedan -->
- **category**  | VARCHAR(20) | NULL
<!-- es: 2020 -->
- **year** | YEAR | NOT NULL
<!-- es: black/red/blue -->
- **color** | VARCHAR(15) | NULL
<!-- es: 10000 -->
- **price** | MEDINT | NOT NULL
<!-- es: new/used -->
- **status** | TINYINT | NOT NULL | DEFAULT (0)
<!-- es: diesel/gas/electric -->
- **fuel** | VARCHAR(10) | NULL
<!-- es: 10000 -->
- **km** | VARCHAR(10) | NULL
<!-- es: nice car -->
- **description** | TEXT | NULL
<!-- es: url -->
- **image** | VARCHAR(255) | NULL | DEFAULT('https://placeholder-img...')
<!-- es: corporate/private -->
- **last-owner** | VARCHAR(10) | NULL
<!-- es: 1/2/3 etc -->
- **number-of-owners** | TINYINT | NULL
<!-- es: city/country -->
- **location** | VARCHAR(30) | NOT NULL
<!-- es: euro 1/euro 2/euro 3 etc -->
- **emissions** | VARCHAR(10) | NULL
<!-- es: 2020 -->
- **immatrication** | YEAR | NULL
<!-- es: 1/2/3 etc -->
- **warranty** | TINYINT | NULL
<!-- es: manual/automatic -->
- **gearbox** | VARCHAR(10) | NULL
<!-- es: l*KM -->
- **fuel-consumption** | TINYINT | NULL
<!-- es: true/false -->
- **is-available** | TINYINT | NOT NULL | DEFAULT (0)

<!-- End of columns -->

<!-- Table Structure -->

| id   | type | brand | model | category | year | color | price | status | fuel | km   | description | image | last owner | number of owners | location | emissions | immatrication | warranty | gearbox | fuel consumption |
| :--- | :--- | :---- | :---- | :------- | :--- | :---- | :---- | :----- | :--- | :--- | :---------- | :---- | :--------- | :--------------- | :------- | :-------- | :------------ | :------- | :------ | :--------------- |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |
|      |      |       |       |          |      |       |       |        |      |      |             |       |            |                  |          |           |               |          |         |                  |

<!-- End of table -->