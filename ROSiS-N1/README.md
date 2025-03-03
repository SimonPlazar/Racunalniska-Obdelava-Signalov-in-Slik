# 1. Naloga

V programskem jeziku Python (Jupyther Notebook) izdelajte program, ki omogoča snemanje in prikazovanje zvočnih signalov (lahko enokanalnih). S programom nato posnemite 3 sekunde dolge zvočne signale pri:

izgovorjavi samoglasnika »a« pri konstantni intenzivnosti in tonu (frekvenci) - dve različni višini tona
izgovorjavi samoglasnika »i« pri konstantni intenzivnosti in tonu (frekvenci) - dve različni višini tona
izgovorjavi samoglasnika »o« pri konstantni intenzivnosti in tonu (frekvenci) - dve različni višini tona
čimbolj čisto žvižganje pri konstantni intenzivnosti in tonu (frekvenci) - dve različni višini tona
izgovorjavi besede "erozija" pri konstantni intenzivnosti in hitrosti - dve različni hitrosti izgovorjave, obe z enako višino tona, ki naj bo podoben eni višini tona pri črkah
Posnete signale (skupaj 10) prikažite z grafi (prikažite celoten signal ter krajši odsek signala na 3-4 periode - torej dva grafa za en signal - najbolje prikazana eden ob drugem levo-desno), pri čemer pazite, da bodo vse osi grafa pravilno označene in po standardih inženirske prakse (ne uporabljajte premajhnih velikosti črk itd.). X os naj bo izražena v sekundah.

Primerjajte oblike signalov samostojnih samoglasnikov (točke 1-3) s posnetki samoglasnikov v besedi "erozija".
Kaj opazite?
Ali lahko s pomočjo križne korelacije v besedi "erozija" na podlagi predposnetih glasov "a", "i", "o" določimo čas nastopa posameznih črk?
Predposnete glasove pred računanjem obrežite na približno enako dolžino, kot je dolžina posamezne črke v izgovorjavi besede "erozija"
Katera znana krivulja prevladuje v posnetku žvižga?
Snemanje opravite z veliko natančnostjo (brez šuma iz okolice), saj boste posnetke potrebovali tudi pri prihodnjih vajah. V primeru žvižga, se lahko z vami igra "noise cancellation" (zaznamo kot nenaden padec amplitude), kar lahko v večini primerov rešite z ustrezno nastavitvijo gonilnikov mikrofona oz. lahko začetek signala, ki izstopa po amplitudi odrežete.

Oddaja naloge

Poročilo in program naj bo izdelan v Jupyther Notebook (.ipynb), zaledne funkcije lahko implementirate v ločenih .py datotekah. Na sistem oddajte datoteko naloga.zip, ki naj vsebuje porocilo.ipynb datoteko in njeno .html različico (izvoz). Prav tako oddajte vse lastne datoteke, ki se nanašajo na delovanje programa (.py datoteke). Ostalih datotek ne oddajajte! Poročilo naj v celicah vsebuje morebitne odgovore na zastavljena vprašanja, vse potrebne grafe ali slike ter ustrezno komentirane poglavitne dele kode programa. V primeru nespoštovanja predpisane oblike poročanja bo naloga zavrnjena in ocenjena z 0 točkami.

