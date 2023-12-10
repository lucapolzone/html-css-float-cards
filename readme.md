# Esercizio: Floating Cards *(05/12/2023)*

nome repo: `html-css-float-cards`

## Descrizione
Riproduzione di un micro layout contenente 6 cards di un ipotetico team.


Partiamo dal realizzare la struttura base della nostra sezione solo con i blocchi colorati per definire struttura e dimensioni di colonne e cards. Una volta definita la struttura inserire  testi, immagini etc. e pensare al dettaglio.

## Consigli
1. Quando date float ad un elemento, date automaticamente anche il clearfix al suo genitore per evitare problemi.
2. Se usate la "tecnica della row":
    - `container` e `col-*` hanno padding positivo, `row` ha margin negativo (stesse quantità)
    - la `row` deve essere *per forza* discendente del `container`
    - la `row` può contenere *esclusivamente* delle `col-*`
    - `container` e `col-*` possono contenere qualsiasi cosa vogliate
    - dare altre proprietà alla griglia potrebbe romperla. si può lavorare su tutti gli altri elementi
<br><br>
> **Punizione divina:** Verrà applicata a coloro che realizzeranno un layout con float, a parte oggi