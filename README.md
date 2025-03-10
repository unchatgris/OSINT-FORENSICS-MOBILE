![Immagine11](https://user-images.githubusercontent.com/98583912/199345295-191b152d-657f-42fc-a317-52f93b5be3d3.gif)

# INDICE
- [1 - Elenchi Telefonici - Ricerca Numero](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#1---elenchi-telefonici---ricerca-numero)
- [2 - Analisi Celle Telefoniche](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#2---analisi-celle-telefoniche)
- [3 - Ricerca Operatori Telefonici](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#3---ricerca-operatori-telefonici)
- [4 - Codice IMEI](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#4---codice-imei)
- [5 - Applicazioni Android](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#5---applicazioni-android)
- [6 - Messaggistica](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#6---messaggistica)
- [7 - Android/iOS Forense](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#7---androidios-forense)
- [8 - Immagini ed Emulatori Android](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#8---immagini-ed-emulatori-android)
- [9 - LE BEST PRACTICES DELLA MOBILE FORENSICS](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/edit/main/README.md#9---le-best-practices-della-mobile-forensics)

![smartphonemagnify-300x240](https://user-images.githubusercontent.com/98583912/190924812-fd8c70f6-8223-47d3-bf8e-b37bec16f2b4.png)

## Elenchi Telefonici - Ricerca Numero 
### Italia
- [Elenchi Telefonici](http://www.elenchitelefonici.it/home/)
- [Agcom](https://www.agcom.it/numerazionicallcenter) - Anagrafica della/le società esercente/i l'attività di call center 
- [Pagine Bianche](https://www.paginebianche.it/)
### Stranieri
- [Truecaller](https://www.truecaller.com/auth/sign-in)
- [Sync.me](https://sync.me/it/)
- [Infobel](https://www.infobel.com/fr/world)
- [Webmii](https://webmii.com/)
- [National Cellular Directory](https://www.nationalcellulardirectory.com/)
- [Annuario 118712 Francia](https://www.118712.fr/) 
- [Spokeo](https://www.spokeo.com/)
- [Phone Books](https://www.phonebooks.com/)
- [This Number](https://www.thisnumber.com/)
- [Phoneinfoga](https://demo.phoneinfoga.crvx.fr/#/)

## Analisi Celle Telefoniche
### Le Sim MOBILE
![2022-09-19 15_59_59-Carta SIM - Wikipedia](https://user-images.githubusercontent.com/98583912/191035415-86079c40-ab6d-4057-a9cc-42de86c0de17.png)
![2022-09-19 16_06_05-Come vengono tracciati i telefoni cellulari - il Valore Italiano](https://user-images.githubusercontent.com/98583912/191036569-2bf6617f-8c62-4aa4-bca5-30cdef2afe0a.png)

- [LTE ITALY - Mappa Antenne 4G](https://lteitaly.it/it/)
- [OpenCelliD](https://opencellid.org/#zoom=16&lat=37.77888&lon=-122.41941)
- [MLS - Overview](https://location.services.mozilla.com/)
- [Unwired Labs Location API](https://unwiredlabs.com/)
- [CellMapper](https://www.cellmapper.net)
- [Infrapedia - Global Internet Infrastructure Map](https://www.infrapedia.com)

  - USA 
    - [Antenna Search](https://www.antennasearch.com/)
  - Inghiterra
    - [MASTDATA](https://mastdata.com/)
## Ricerca Operatori Telefonici
- [Twilio - Ricerca per API](https://www.twilio.com/lookup)
- [Reverse Phone Lookup - Ricerca per Numero telefonico](http://www.reversephonelookup.com/)
- [Spy Dialer - Ricerca per Numero Telefonico](http://spydialer.com/)
- [Phone Validator - Ricerca e Convalida numero telefonico](https://www.phonevalidator.com/index.aspx)
- [Free Carrier Lookup - Ricerca Operatore Telefonico](http://freecarrierlookup.com/)

  - USA 
    - [Ricerca Numero](https://www.thisnumber.com/)

## Codice IMEI 
![COdice Imei](https://spyproject.com/img/landing/b/imei1.jpg)
![Imei](https://it.tab-tv.com/wp-content/uploads/2019/11/IMEI-codice-che-significa-spiegazione-it.jpg)
```
International Mobile Equipment Identity

L'IMEI si può visualizzare digitando *#06#, ovvero il comando AT + CGSN.
"Oppure nel retro nella scatola del telefono oppure dietro la batteria dello stesso"
È composto da 15 cifre, suddiviso in 4 parti:

AAAAAA BB CCCCCC D

dove:
- AAAAAA rappresenta il TAC (Type Approval Code) che identifica la casa costruttrice e il modello del telefonino;
- BB rappresenta il FAC (Final Assembly Code) che identifica il luogo di costruzione o di assemblaggio del prodotto;
- CCCCCC indica il numero di serie del cellulare;
- D viene definita SP (Spare) o CD (Check digit) ed è una cifra riservata di controllo che verifica la correttezza del codice IMEI, calcolato con la formula di Luhn.
La sigla TAC, inoltre, ha cambiato significato ed è divenuto acronimo di Type Allocation Code.
Alcuni numeri IMEI hanno 16 cifre; l'ultima parte di due cifre, detta SV (Software Version), indica la versione del firmware dell'apparecchio, mentre la cifra spare è rimossa.

Fonte: 
https://it.wikipedia.org/wiki/International_Mobile_Equipment_Identity
```

- [SNDeepInfo](https://sndeep.info/en)
- [IMEI tools](http://imei-number.com/imei-number-lookup/)
- [Nobbi](http://www.nobbi.com/tacquery.php)
- [CONTROLLO IMEI](https://www.imei.info/)
- [Telefono sotto controllo](https://www.telefonosottocontrollo.com/imei-marca-modello-cellulare/)
- [Analisi dei numeri IMEI](https://www.numberingplans.com/?page=analysis&sub=imeinr)

## Applicazioni Android
### CELLE 
- [Securcube BTS Tracker](https://play.google.com/store/apps/details?id=net.securcube.btstracker&hl=en_US&gl=US)
- [Cell Tower Locator](https://play.google.com/store/apps/details?id=ru.v_a_v.celltowerlocator&hl=en&gl=US)
- [Opensignal - 5G, 4G Speed Test](https://play.google.com/store/apps/details?id=com.staircase3.opensignal&hl=en&gl=US)
- [NetMonitor Cell Signal Logging](https://play.google.com/store/apps/details?id%3Dru.v_a_v.netmonitor)
- [CellMapper](https://play.google.com/store/apps/details?id=cellmapper.net.cellmapper&hl=it&gl=US)

### WIFI 
- [WIGLE - Wifi](https://play.google.com/store/apps/details?id=net.wigle.wigleandroid&hl=en_US&gl=US)
- [Fing - Network Tools](https://play.google.com/store/apps/details?id=com.overlook.android.fing&hl=it&gl=US)
- [WifiAnalyzer](https://play.google.com/store/apps/details?id=cz.webprovider.wifianalyzer&hl=it&gl=US)
- [SignalMonitoring](https://play.google.com/store/apps/details?id=com.signalmonitoring.gsmsignalmonitoring&hl=it&gl=US)
- [SpeedTest](https://play.google.com/store/apps/details?id=org.zwanoo.android.speedtest&hl=it&gl=US)

## ALTRE APP
- [FAKE GPS](https://play.google.com/store/apps/details?id=com.gsmartstudio.fakegps&hl=it&gl=US)

# Messaggistica
## Whatsapp
![Whatsapp_37229](https://user-images.githubusercontent.com/98583912/190934139-b3b41790-aecd-4a9d-9b00-59249a70d0eb.png)
### Analisi/Esportazione Chat 
![esportazione-chat-whatsapp](https://user-images.githubusercontent.com/98583912/190933662-164db90f-eda8-42da-9bd7-d21034feb6d5.jpg)

- [Chat Visualizer](https://chatvisualizer.com/)
- [WhatsAnalyze ](https://whatsanalyze-80665.web.app/)
### Ricerca Gruppi 
- [Whatsgrouplink](https://whatsgrouplink.com/#0-pubg-whatsapp-group)
### Altri Strumenti
- [Watools](https://watools.io/download-profile-picture)

## Telegram
![telegram_icon-icons com_72055](https://user-images.githubusercontent.com/98583912/190934092-0fb3047e-697f-4d75-946b-a94dde6870d4.png)
- [Telegram Web](https://web.telegram.org/k/)
### Esportazione Chat Telegram
![esportare-chat-telegram](https://user-images.githubusercontent.com/98583912/190934176-ba345478-258a-44ab-b8e4-73789135c84a.jpg)

### Ricerca Gruppi
- [telegramdb](https://telegramdb.org/)
- [Telegram Search Engine](https://xtea.io/ts_en.html)
- [Global Telegram Database](https://t.me/s/privatelinks)
- [TGStat](https://tgstat.com/) - Catalogo canali e gruppi Telegram
- [Telegago](https://cse.google.com/cse?&cx=006368593537057042503:efxu7xprihg#gsc.tab=0)
- [SocialFinder](https://socialfinder.app/list/Telegram)
- [lyzem.com](https://lyzem.com/)
- [Telegram Channels](https://telegramchannels.me/)


# Android/iOS Forense
![Senzanome](https://user-images.githubusercontent.com/98583912/190924780-e187ac6b-4512-454e-8ff0-fcc62a16f75c.png)


- [Gsmarena - Ricerca e Caratteristiche Smartphone](https://www.gsmarena.com/)
- [Mobile Phone Museum - Collezione storica dei telefoni cellulari e Smartphone](https://www.mobilephonemuseum.com/catalogue/)
- [Cruscotto - Android Secure Coding Standard](https://wiki.sei.cmu.edu/confluence/display/android)
- [HardReset](https://www.hardreset.info/) - Cancellare tutti i dati sul tuo dispositivo
- [DoubleBlak Digital Forensics](https://www.doubleblak.com/index.php)

## Tools Github
![icon](https://user-images.githubusercontent.com/98583912/191048022-a1edc21b-e5a5-4152-bb52-ca1f439846a2.svg)
- [GitHub - Scrcpy](https://github.com/Genymobile/scrcpy/releases) 
 - Questa applicazione fornisce la visualizzazione e il controllo dei dispositivi Android collegati tramite USB o tramite TCP/IP. 
   Non richiede alcun accesso come root. Funziona su GNU/Linux, Windows e macOS.
- [GitHub - Andriller CE](https://github.com/den4uk/andriller) - Software con una raccolta di strumenti forensi per smartphone
- [GitHub - ALEAPP](https://github.com/abrignoni/ALEAPP) - Android registra eventi e protobuf parser
- [GitHub - MEAT](https://github.com/jfarley248/MEAT) - MEAT - Mobile Evidence Acquisition Toolkit
- [GitHub - AvillaForensics](https://github.com/AvillaDaniel/AvillaForensics) - Strumento gratuito di analisi forense mobile Avilla Forensics
- [GitHub - Mobile Verification Toolkit](https://github.com/mvt-project/mvt)
- [GitHub - ashishb / Android-Security-Awesome: una raccolta di risorse relative alla sicurezza Android](https://github.com/ashishb/android-security-awesome)

# Immagini ed Emulatori Android
- [Genymotion](https://www.genymotion.com/download/)
- [Osboxes](https://www.osboxes.org/android-x86/)
- [Android-x86](https://www.android-x86.org/)

# LE BEST PRACTICES DELLA MOBILE FORENSICS

- [SWGDE Best Practices for Mobile Phone Forensics.pdf](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/files/9600300/SWGDE.Best.Practices.for.Mobile.Phone.Forensics.pdf)
- [TipiLoschi.net - Best Practices per iPhone e iDevice](https://www.tipiloschi.net/drupal/best-practice-iphone-ios)
