# STDFT

Opravite analizo nestacionarnosti govornih signalov iz prve naloge, tako da preučite, kako se frekvenčna vsebina spreminja s časom. V ta namen uporabite različne dolžine intervalov, nad katerimi izračunate DFT oz. opravite kratkočasovno Fourierovo transformacijo.

Uporabite dolžine intervalov 10 ms, 20 ms, 50 ms in 100 ms ter stopnje prekrivanja intervalov 0 %, 50 % in 75 %.

Kratkočasovno Fourierovo transformacijo implementirajte sami, pri čemer lahko uporabite DFT iz prejšnje naloge ali pa FFT funkcijo implementirano v izbranem jeziku (priporočena je uporaba FFT - zaradi hitrosti izračunavanja). Pri ponazoritvah analiz se grafično približajte izrisu s funkcijo pcolormesh (Python). Z obzirom na dolžino intervala in stopnjo prekrivanja signal ustrezno "podaljšajte" (na konec dodajte ničle - padding), da bo dolžina zadostovala večkratniku intervala s prekrivanjem. Vse izvedene analize izvedite brez in z uporabo Hammingovega okna.

Za analizo uporabite vse signale iz prve naloge.

 

Odgovorite in grafično (s primeri) ponazorite odgovore na naslednja vprašanja:

Kako je nestacionarnost signalov odvisna od hitrosti izgovarjave oz. ali se optimalna izbira dolžine intervalov za DFT in stopnje njihovega prekrivanja razlikuje od hitrosti izgovarjave?
Kako se z izbiro dolžine intervalov spreminja zaznava višjih harmonikov v frekvenčni sliki posameznih intervalov?
Kako izbira dolžine intervalov spreminja razlikovanje med samoglasniki slovenske abecede?