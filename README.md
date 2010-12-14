SpendChart Banksync
-------------------
SpendChart Banksync er en applikasjon for � hente kontoutskrifter fra din 
nettbank og laste de opp til SpendChart.no. P� denne m�ten kan du enkelt kan f� oversikt
over ditt forbruk og din �konomi. 

Klienten er gjort tilgjengelig for at du skal kunne verifisere at applikasjonen
gj�r det den lover og at du eventuelt kan modifisere den etter egne behov.

SpendChart tilbyr signert installer av applikasjonen til windows p� spendchart.no. Vi garnanterer
at denne er bygd fra kildekoden som er gjort tilgjengelig p� http://github/spendchart/banksync. 

### Byggeinstruksjoner: ###
For � bygge Banksync trenger du simple build tool. Den kan du laste ned her: http://code.google.com/p/simple-build-tool/ 

Med simple build tool installert kan du g� fram som f�lger:
   
		git clone git://github.com/spendchart/banksync.git
		cd banksync
		sbt proguard

Den ferdige jar filen kan du finne i !target/scala_2.8.1/banksync_.2.8.1-1.0.min.jar!

For � kj�re programmet direkte kan du benytte:

		sbt run

Script for generering av .exe fil er gjort tilgjengelig i nis katalogen.

### Sikkerhet: ###
Om du skulle komme over sikkerhetsmessige s�rbarheter i kildekoden setter vi pris
p� om du tar kontakt med oss direkte.

### Endrings�nsker / patcher: ###
Endrings�nsker mottas med takk. Det samme pull requests. Vi vil selvsagt verifisere all
kode som legges ut p� http://github/spendchart/banksync
