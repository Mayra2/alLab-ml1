# Zadaća 2 — EDA na vlastitom datasetu 🐈

**Dataset:** [Pet Cats UK](https://github.com/rfordatascience/tidytuesday/tree/master/data/2023/2023-01-31) (TidyTuesday): 101 kućna mačka u Engleskoj, sa podacima o spolu, starosti, sterilizaciji, satima provedenim u kući i plijenu koji donesu kući.

**Notebook:** [`Zadaca_dio2_macke.ipynb`](Zadaca_dio2_macke.ipynb)

**Riješeni problemi u podacima:**
1. `hunt` nedostaje za 9 mačaka → sve donose 0 plijena, pa je upisano `False`
2. `Neutered` / `Spayed` znače isto → jedna kolona `sterilisana` (da/ne)
3. sati u kući su odgovori iz upitnika → pretvoreni u grupe (`0-5 h`, `5-10 h`...)

**Uvid:** spol ne utiče na lov, ali mačke koje su skoro stalno napolju donose oko **7 plijena mjesečno**, a one koje su skoro stalno u kući manje od 1.
