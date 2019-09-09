# flightradar24
Specific files for own flightradar24 tracking project

FR24 [Live traffic - local](https://www.flightradar24.com/50.88,9.73/10)

FR24 [Share your ADS-B data](https://www.flightradar24.com/share-your-data)

FR24 [Installationshandbuch](fr24feed-manual.pdf) (abgerufen 2019-09-06)

jetvision [download support](https://rtl1090.com) (abgerufen 2019-09-06)

jetvision [DVB-T Dongle - Quick_Start Guide](Quick_Start_Dongle_20171231.pdf)(abgerufen 2019-09-06)

J.Sun [decoding ADS-B](the_1090mhz_riddle-junzi_sun_2019-09-07.pdf) (abgerufen 2019-09-07)


## other projects

mode-s.org: [ADS-B decoding](https://github.com/junzis/the-1090mhz-riddle)

rtl-sdr.com: [RTL1090 versions](https://www.rtl-sdr.com/tag/rtl1090/)

squix: [ESP8266 plane spotter](https://blog.squix.org/2016/07/esp8266-based-plane-spotter-how-to.html)

rasspberry.tips: [Laufraumüberwachung](http://raspberry.tips/raspberrypi-tutorials/lueftraumueberwachung-mit-dem-raspberry-pi/)

---

### references

ADS-B (Automatic Dependent Surveillance - Broadcast - [Wiki de](https://de.wikipedia.org/wiki/Automatic_Dependent_Surveillance)

DVB-T (Digital Video Broadcasting – Terrestrial) - [Wiki de](https://de.wikipedia.org/wiki/DVB-T)

Mode-S (Standard Mark XII - Sekundärradar) - [Wiki de](https://de.wikipedia.org/wiki/Sekund%C3%A4rradar#Mode_S)

SDR (Software Defined Radio - RTL-SDR) - [Wiki de](https://de.wikipedia.org/wiki/Software_Defined_Radio)

SSR (Secondary Surveillance Radar - Sekundärradar) - [Wiki en](https://en.wikipedia.org/wiki/Secondary_surveillance_radar)

---

#### remarks

+ Squitter-Mode

Eine Besonderheit der Mode-S-fähigen Transponder ist der sogenannte Squitter-Mode, bei dem der Transponder unabhängig von einer Abfrage und in regelmäßigen Abständen zum Beispiel GPS- Position und Identifizierung als Rundspruch sendet (ADS-B Automatic Dependent Surveillance – Broadcast). Die Unterstützung dieses Modes ist in Deutschland jedoch keine Pflicht. Auch sind noch nicht alle Mode-S-fähigen Transponder technisch in der Lage, eine solche Nachricht zu versenden.

Dieser Mode ermöglicht, mit einem einfachen über eine USB-Schnittstelle an einen Computer angeschlossenen Empfänger auf der Frequenz 1090 MHz ein virtuelles Radar aufzubauen, das mit einer kleinen Stabantenne die kommerziellen Flüge im Umkreis von etwa 40 km auf dem Computerdisplay in Echtzeit darstellen kann. Durch die Verknüpfung vieler solcher kleinen Empfangsstationen über ein Netzwerk sind lückenlose Darstellungen der Bewegungen im Luftraum möglich.

+ RTL-SDR
 
The RTL-SDR is an ultra cheap software defined radio based on DVB-T TV tuners with RTL2832U chips. The RTL-SDR can be used as a wide band radio scanner. It may interest ham radio enthusiasts, hardware hackers, tinkerers and anyone interested in RF

+ Squawk (Flugfunktranspondercode)

Betriebsarten:
1. Mode A: nur der Squawk wird übermittelt
2. Mode C: Squawk und Flugfläche (Flughöhe über Normaldruck gerundet auf 100 ft) werden übermittelt
3. Mode S: Zusätzlich zu Squawk und Flugfläche wird eine eindeutige Fleugzeugkennung (24-bit) übermittelt

[]()
