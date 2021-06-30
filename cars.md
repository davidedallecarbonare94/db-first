# Database Rivendita Auto

## (table) Cars
- id                        BINGINT PRIMARY KEY UNIQUE NOTNULL INDEX AUTO_INCREMENT
- marca                     VARCHAR(30) NOTNULL 
- modello                   VARCHAR(40) NOTNULL
- anno                      YEAR NOTNULL
- kilometraggio             INT NOTNULL
- alimentazione             VARCHAR(30) NOTNULL
- emissioni                 VARCHAR(10) NOTNULL
- porte                     TINYINT NULL
- cilindrata                INT NOTNULL
- cavalli                   SMALL NONULL
- targa                     VARCHAR(7) NOTNULL
- numero_serie              CHAR(17) NOTNULL
- condizioni                VARCHAR(50) NULL
- disponibile               SMALL NULL
- dimensione_cerchi         SMALL NULL
- colore                    SMALL NOTNULL
- tipo vernice              VARCHAR(20) NULL
- revisione                 TINYINT NOTNULL
- tagliando                 TINYINT NOTNULL
- ex_proprietari            VARCHAR(255) NULL
