# TRACCIA:

    Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


# HUMAN CODE:

1) Trovare un nome per la nostra tabella.

2) Definire il tipo di dato dei nostri dati nella tabella.

3) Inserire eventuali attributi

# TABELLA: Cars


# COLONNE:


    -ID: Number - INT - [PRIMARY KEY, AUTO_INCREMENT]
    
    -CASA_PRODUTTRICE: String - VARCHAR(15) - [NOTNULL]

    -MODELLO: String - VARCHAR(70) - [NOTNULL]

    -IMAGE: String - VARCHAR(256) - [DEFAULT(placeholer img)]

    -IMMATRICOLAZIONE: Date - DATE - [NOTNULL]

    -CHILOMETRI: Number - FLOAT(8, 2) - [NOTNULL]

    -PREZZO: Number - DECIMAL(8, 2) - [NOTNULL]

    -ALIMENTAZIONE: String - VARCHAR(10) - [NOTNULL]

    -CAMBIO_AUTOMATICO: Number - TINYINT - - [DEFAULT(0)]
    
    -TIPOLOGIA_CAMBIO_AUOTMATICO: String - VARCHAR(3) - [DEFAULT('Non è dotata di cambio automatico')]

    -POSTI: Number - TINYINT - [NULL]

    -CILINDRATA: - Number SMALLINT - [NOTNULL]

    -PORTE: Number - TINYINT - [NULL]

    -POTENZA: Number - TINYINT - [NOTNULL]

    -CONSUMI: Number - TINYINT - [NULL]

    -CLASSE: String - CHAR(2) - [NOTNULL]

    -N.PROPRIETARI: Number TINYINT  - [NULL]

