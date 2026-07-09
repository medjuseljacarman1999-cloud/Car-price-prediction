Projekat: Predikcija cene polovnih automobila
1. Opis projekta:
Razvijen model mašinskog učenja za procenu tržišne vrednosti automobila na osnovu karakteristika (marka, godina, kilometraža, vrsta goriva, zapremina motora).

2. Tehnološki stek:

Jezik: Python

Biblioteke: Pandas (obrada podataka), Scikit-Learn (treniranje modela), Joblib (čuvanje modela)

Model: Random Forest Regressor

3. Ključni koraci u radu:

Čišćenje podataka: Uklonjene ekstremne vrednosti (autlajeri) i rešeni nedostajući podaci (imputacija/brisanje).

Feature Engineering: Pretvaranje kategorijskih podataka u brojeve pomoću get_dummies metode.

Treniranje: Podaci podeljeni u trening (80%) i test skup (20%). Korišćen Random Forest algoritam.

4. Rezultati:

Tačnost modela (R^2): 0.99

Prosečna greška modela (MAE): 987.92 $

Zaključak: Model ima visoku preciznost i spreman je za praktičnu primenu u predikciji cena automobila.