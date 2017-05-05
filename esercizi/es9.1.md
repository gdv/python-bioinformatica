# Ricerca motivi (cambio formulazione)

Riprendere l'algorimo branch-and-bound per il calcolo dei motivi.
L'enumerazione di tutte le possibili soluzioni viene fatta generando
tutte le possibili stringhe di consenso.

Per ogni stringa di consenso devo cercare il migliore punto di inizio
all'interno di ogni stringa.

Ad esempio, date le stringhe 
`ACGACTACGTAC
ACGACGACGACT
ACGGACTACGAC
`
e la possibile stringa di consenso `GGAG`, ottengo i punti di inizio
(1, 1, 2).
