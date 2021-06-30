# Database Concessionaria

## Car

- id                                        BIGINT PRIMARY KEY UNIQUE - NOTNULL INDEX
- prezzo                                    DECIMALE (7,2)            - NOTNULL 
- descrizione                               TEXT                      - NULL
- marchio                                   VARCHAR(100)              - NOTNULL
- modello                                   VARCHAR(255)              - NOTNULL
- comfort                                   TEXT                      - NULL
- cavalli                                   SMALLINT                  - NULL
- colore                                    VARCHAR(50)               - NOTNULL
- tipo di colore                            VARCHAR(50)               - NULL
- lunghezza                                 DOUBLE(3,2)               - NOTNULL
- larghezza                                 DOUBLE(3,2)               - NOTNULL
- peso                                      DECIMALE (5,2)            - NULL                      
- altezza                                   DOUBLE(2,2)               - NOTNULL
- alimentazione                             VARCHAR(50)               - NOTNULL
- materiale interni                         TEXT                      - NULL
- trasmissione                              VARCHAR(100)              - NOTNULL
- chilometraggio                            DECIMALE (6,2)            - NOTNULL
- data di immatricolazione                  DATE                      - NOTNULL
- targa                                     VARCHAR(10) UNIQUE        - NOTNULL INDEX
- target/tipologia                          VARCHAR(20)               - NULL
- nazione                                   VARCHAR(30)               - NULL