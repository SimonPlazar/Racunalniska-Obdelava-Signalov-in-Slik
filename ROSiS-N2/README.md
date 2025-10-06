# DFT

Izdelajte program za analizo frekvenčne vsebine, ki jo opravite preko skalarnega produkta z lastno izbranimi sinusoidami. Slednje zaradi večje učinkovitosti analize prilagodite frekvenčni vsebini signala (omejite se na prvih N frekvenc, ki so v signalu).

Pri grobi analizi frekvenčne vsebine si pomagajte z obstoječimi algoritmi (hitre) diskretne Fouriereve transformacije, vendar morate dokončno frekvenčno analizo opraviti z lastno implementiranim skalarnim produktom in z lastno izbiro sinusoid. Implementirajte dve različici frekvenčne analize - z realnimi in kompleksnimi sinusoidami!

Pri implementaciji pazite, da boste zagotovili ortogonalnost sinusoid, s katerimi analizirate frekvenčno vsebino.

Z izdelanim programom testirajte izgovorjavo samoglasnikov »a«, »i« in »o«. Povsod izrisujte grafe.

Odgovorite in grafično (s primeri) ponazorite odgovore na naslednja vprašanja:

Ali lahko frekvenčno sliko signala nedvoumno določimo preko skalarnega produkta med posnetim signalom in izbrano realno sinusoido? Zakaj?
Ali lahko frekvenčno sliko signala nedvoumno določimo preko skalarnega produkta med posnetim signalom in izbrano kompleksno sinusoido? Kako na to vpliva dolžina opazovanega intervala signala? Zakaj?
Katere vse frekvence so prisotne v izgovorjavi samoglasnikov »a«, »i« in »o« (osredotočite se na frekvence, ki predstavljajo vsaj 1 % celotne energije signala)?
Tukaj lahko preračunate energije po frekvencah ali pa vizualno določite po aplitudi izstopajoče frekvence
Kako so frekvence, ki so prisotne v izgovorjavi samoglasnikov »a«, »i« in »o« odvisne od višine tona izgovorjave?
Kako se z višino tona izgovorjave spremeni pojav višjih harmonikov v frekvenčni sliki?
Opozorilo

Če je čas izvajanja analize daljši od ~15 minut
Niste upoštevali nasveta o predhodni analizi signala s FFT ali pa o omejitvi na prvih N frekvenc (N je lahko nejke med 0-5000 Hz)
Nepravilno ste implementirali skalarni produkt - pazite na range spremenljivk k in n
Pazite na pravilno skalo x osi (pravilno izračunane frekvence - frekvenčne razdelke)
Pri vseh analizah izrišite graf FFT in vaše implementacije - poravnajte osi med grafi (rišite isti odsek na vseh grafih, ...)
Pri analizi ohranite samo prvo polovico frekvenčne vsebine (do Fs/2 oziroma do frekvence N)
Vizualno primerjajte grafa FFT in vaše implementacije DFT - morata biti podobna