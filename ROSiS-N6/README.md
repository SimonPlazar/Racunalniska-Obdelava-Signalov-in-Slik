# Filtri

	
Izdelajte program za dinamično načrtovanje filtrov za odstranjevanje poljubnih višjih harmonikov iz signalov.

Vhod je torej zaporedna številka višjega harmonika (npr. 2,3 in 6 harmonik) in pa bazna frekvenca.

Osnovno frekvenco lahko določite avtomatsko (FFT in max, find_peaks, cepstrum, autocorrelation) ali ročno (vizualno določanje vrha).

Zahteve:

filtre načrtujte na dva načina (oba tipa IIR):
glavnični filter (comb filter) z metodo yulewalker
OPOZORILO: Pri uporabi knjižnice prihaja do težav pri načrtovanju filtrov
Filitirajte le harmonike, ki so nad 500 Hz 
pri načrtovanju filtra lahko uporabite širino zapiranja največ +- 50 Hz glede na filtrirano frekvenco 
kaskada filtrov (poljubno izberite med butter, cheby1, cheby2, eliptic, ...) - red filtra naj bo fiksno število
pri načrtovanju filtra lahko uporabite širino zapiranja največ +- 10 Hz glede na filtrirano frekvenco 
lahko uporabite sos (second-order-sections)
pazite, da bodo vsi vaši filtri čim bolj učinkoviti (v časovnem in frekvenčnem smislu) ter stabilni
filtre uporabite nad vsemi posnetimi izgovorjavami črk iz naloge 1
za vsako izvedeno filtriranje dodajte graf FFT pred in po filtriranju
za vsak načrtovan filter dodajte graf frekvenčnega odziva filtra (pri glavničnemu filtru tudi frekvenčno karakteristiko)
za vsak signal (posnetek izgovorjave črke) si zapišite osnovno frekvenco (za namene zagovora)
pazite na uporabo pravilne funkcije za aplikacijo filtra na signal
pazite na pravilne oznake osi
Odgovorite in grafično (s primeri) ponazorite odgovore na naslednja vprašanja:

Kako je frekvenčna učinkovitost filtra odvisna od reda filtra (t.j. od števila koeficientov a in b)?
Kako lahko višje harmonike odstranimo s kaskado filtrov in kaj s tem pridobimo v primerjavi z uporabo enega samega filtra?
Kako je frekvenčna učinkovitost kaskade filtrov primerljiva s filtriranjem v frekvenčnem prostoru?