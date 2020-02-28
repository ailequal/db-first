# db-first

A skeleton of a database prototype.

## Used cars

|  ID  |           Label           | Data type |    Size    |     Attribute     |
| :--: | :-----------------------: | :-------: | :--------: | :---------------: |
|  1   |          Modello          | TINYTEXT  |  255 CHAR  |      NOTNULL      |
|  2   |           Targa           | TINYTEXT  |  255 CHAR  | UNIQUE && NOTNULL |
|  3   |       Proprietario        | TINYTEXT  |  255 CHAR  |      NOTNULL      |
|  4   |        KM percorsi        |    INT    |  4 BYTES   |      NOTNULL      |
|  5   | Litri di benzina presenti | SMALLINT  |  2 BYTES   |       NULL        |
|  6   |          Graffi           |   TEXT    | 65535 CHAR |       NULL        |
|  7   |   Parti non funzionanti   |   TEXT    | 65535 CHAR |      NOTNULL      |
|  8   |          Prezzo           |    INT    |  4 BYTES   |      NOTNULL      |
|  9   |         Optional          |   TEXT    | 65535 CHAR |       NULL        |
|  10  |     Data di acquisto      | DATATIME  |  8 BYTES   |      NOTNULL      |

