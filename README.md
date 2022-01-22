# SNT-Project
Eindwerk voor 2de deel van avondschool Raspberry Pi in SNT
## Beschrijving
Opzetten van een Multifunctional Raspberry Pi, te gebruiken als media toestel (Kodi, Modity) maar ook als automation server (Node-RED, Home Assitant, Google Assitant integratie) met bestaande en nieuw komende intelligente devices.

Ik was eigenlijk alles al aan het noteren / beweren op een sites.google.com site: https://sites.google.com/view/krislonneville

Projec(ten) voor dit eindwerk zal ik hier opnoemen en telkens de link naar mijn google site opgeven.

### Voorbereidende werken
Nieuwe projecten voor dit "eindwerk" zal ik op mijn bestaande "server" Raspberry Pi installeren / configureren. 

Voorafgaande stappen van het opzetten van mijn Raspberry pi (zie ik niet echt in scope van dit SNT project, maar is misschien wel interessant)
- OS + configuratie OS (move naar SSD, aktieve sturing van koel ventilator met relais, ... )

        https://sites.google.com/view/krislonneville/it-home/raspberry-pi/raspi-tv/besturings-systeem-os

- installatie van Node-RED

        https://sites.google.com/view/krislonneville/it-home/raspberry-pi/raspi-tv/node-red
        
- installatie van Home Assitant (via Docker container)

        https://sites.google.com/view/krislonneville/it-home/raspberry-pi/raspi-tv/domotica-home-automation/home-assitant


### Nieuwe Projecten
**1. MCZ Maestro pellet kachel**

Om deze te besturen is er eigenlijk een goede app, die ik wel zal blijven gebruiken (alsook mijn gezin). Maar een tekortkoming, vind ik toch, is dat als de kachel in storing staat, we daar eigenlijk geen idee van hebben. We merken het als het kouder wordt natuurlijk.
Doel 1: De gegevens van de pellet kachel op de (bestaande) Home Assitaaast plaatsen
Doel 2: Een notificatie uit te sturen (onder welke vorm dan ook) als de kachel in fout staat (bvb. pellets op, aanzuig filter verstopt, ... -
Doel 3: Misschien zelfs de kachel al "resetten", wat eigenlijk inhoud om de Chrono thermostaat uit te zetten (als die is ingeschakeld) en dan de kachel gewoon uit doen.
        Dit laatste weet ik nog niet. Heb al gezien zeker mogelijk, maar is toch een aktie sturen i.p.v. het veilig lezen van de gegevens.

Op onderstaande url is de beschrijving van dit project.

https://sites.google.com/view/krislonneville/it-home/raspberry-pi/raspi-tv/varia-losse-projectencten/besturing-pellet-kachel

**2. Roborock S3 **

We hebben thuis ook een automatische stofzuig / dwijl robot die het zware werk van stopzuigen gedurende de nacht doet.

Ik zou deze dus ook willen zien in de Home Assistant, en (na wat surf werk) de kaart zichtbaar maken.

**3. Dobbelsteen **

Ik heb een aantal 8x8 LED matrix devices. Hiermee zou ik willen een dobbelsteen maken (dus random het bovenste vlak van een dobbelsteen tonen: random van 1 - 6). Dit zal zeker in Python zijn. Lijkt mij gewoon een leuk project


**4. Stroom verbruik meeting, zonder de echte digitale meter.

Ik heb zonnepannelen, dus wil ik zo lang mogelijk de digitale meter buitenhouden. MAAR toch zou ik een veel beter zicht willen hebben op mijn elektriciteitsverbruik. Hiervoor heb ik all een Shelly EM gekocht, maar nog geen spoelen/klemmen om de meeting echt te doen (had het besteld met het erbij zat, maar blijkbaar niet, dus voelde ik mij wat bekocht). Soit, we gaan hier toch mee door. Naast deze Shelly EM (via Wifi) heb ik ook 2 gestuurde stopcontacten gekocht, maar nu een type die een verbruiksmeeting doet (naast mijn bestaande zonder verbruiksmeeting).

Deze gaan ook worden geïntegreerd in de Home Assitant, en dan zien welke data daar kunnen uitkrijgen om slimmer met energie om te gaan.

**5. Zigbee integratie

Plan is ook dat ik een Zigbee netwerk opzet, met een conbee II USB stick, maar zien we later wel hoe en wat (zeker temp. en schakel contacten).

**6. ESP8266 integraties

Ik heb een aantal ESP8266 devices liggen waarmee ik ook wil leten spelen. Een project die ik hiermee zou willen doen is om regenwater put niveau te bekijken. Er zijn een 2 tal medestudenten die dit met de Raspberry Pi gaan doen, ik wil het proberen met een ESP8266 die dan zijn data "publiceerd" zodat de Raspberry Pi deze kan lezen en dus ook tonen en alarmen kan opzetten.


Voila, dat is het plan hopelijk kan ik er een aantal dit trimester van realiseren, anders doe ik gewoon verder in deze enorm facinerende Raspberry Pi wereld.


