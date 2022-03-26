# Skripte i konfiguracije

Moje osobne skripte i konfiguracije za razne programe koje koristim. 

Skripte se nalaze u ```.local/bin```, a konfiguracije u ```.config``` direktoriju.

## rijecdana

Skripta dohvaća riječ dana s Hrvatskog jezičnog portala i sprema je u datoteku. Preporuka za korištenje je skriptu dodati u crontab da se izvršava svakih 5-15 minuta (samo navesti punu putanju do skripte, i osigurati da skripta ima dopuštenje za izvršavanje, u skripti se prvo provjerava starost datoteke, tako da nije intenzivno na resurse), te zatim u konfiguraciju shella (```.bashrc```, ```.zshrc``` i sl.) dodati liniju ```[ -f ~/.cache/rijecdana.txt ] && cat ~/.cache/rijecdana.txt```.

Dependency: ```w3m```

## wordoftheday

Slično kao i ```rijecdana```. Preporuka je dodati skriptu u crontab da se periodično izvršava, te u konfiguraciji shella (```.bashrc```, ```.zshrc``` i sl.) dodati liniju ```[ -f ~/.cache/wordoftheday.txt ] && cat ~/.cache/wordoftheday.txt```.

## 1rm

Alat za teretanu koji računa maksimalnu težinu koju možemo podignuti.

## bingo

Privremeno generira šest pseudoslučajnih brojeva.

## calc

Kratka skripta za brzo računanje, zaokružuje na tri decimale pomoću scale argumenta.

## dmenumount / dmenuumount

Mountanje i unmountanje diskova, Androida i USB-ova pomoću dmenua.

## eduroam

Skripta za spajanje na eduroam mrežu i proizvoljno stvaranje hotspota (dependency - create_ap) - credentialsi za WiFi su fake 😛

## emoji i emoji.txt

Generira dmenu izbornik s listom svih emojija i kopira ih u clipboard (dependency - xclip)

## lyrics

Dohvaća lyricse nakon što se upišu izvođač i naziv pjesme.

## yt

Skripta za brzo reproduciranje i skidanje sadržaja s YouTubea (dependency - mpv i youtube-dl)
