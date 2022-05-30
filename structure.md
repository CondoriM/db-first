# Auto Dealers

## Modello: Cars

- id:               BIGINT          PK(NOTNULL, AI, UNIQUE)
- VIN:              CHAR(17)        NULL UNIQUE
- Model:            VARCHAR(50)     NOTNULL
- car-brand:        VARCHAR(255)    NOTNULL
- photo:            VARCHAR(255)    NULL
- description:      TEXT            NULL
- price:            DECIMAL(12,2)   NULL
- production_year:  YEAR            NULL
- new_release:      TINYINT         NULL
- pecial_price:     DECIMAL(12,2)   NULL
- discount:         FLOAT(3,1)      NULL
- location:         VARCHAR(100)    NULL DEFAULT('italy')
- rarity:           TINYINT         NOTNULL DEFAULT(0)
- new:              TINYINT         NULL
- km_traveled:      FLOAT(10,0)     NULL
- car_rank:         FLOAT(3,1)      NULL
- note:             TEXT            NULL