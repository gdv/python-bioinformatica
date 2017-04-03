# Ricerca di motivi

Date *k* stringhe lunghe *n*, un **motivo** lungo *l* è una stringa che è approssimativamente presente in tutte le stringhe in ingresso.

Date *k* lunghe *l*, il loro *consenso* è la stringa dove in ogni colonna viene preso il carattere più frequente.

Il consenso di:
```
ACCGATCA
AGCATGCA
ACTACGAC
``` 
è 
```
ACCAAGCA
```

Il valore del consenso è la somma, su tutte le posizioni, del numero di stringhe in ingresso in cui il carattere di consenso appare.
```
ACCGATCA
AGCATGCA
ACTACGAC
--------
ACCAAGCA
32212222 -> 16
```

###  Problema

Date *k* stringhe lunghe *n* e un numero *l*, trovare il motivo lungo *l* di massimo valore.
Eseguire il programma sul file [Human_BRCA2_orthologues2.fa](../data/Human_BRCA2_orthologues2.fa) 
