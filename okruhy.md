# MPKS - Počítačové a komunikační sítě
1. Topologie sítí, způsoby přepínání, vlastnosti sítí typu store-and-forward, modely (ISO/OSI, TCP/IP), funkce jednotlivých vrstev.
2. Aplikační protokoly HTTP, FTP, SMTP, DNS.
3. Protokolová sestava TCP/IP: TCP (chybové řízení, řízení toku, metody proti zahlcení sítě), UDP, IP (směrování, fragmentace, adresování, NAT/PAT).
4. Přenosová média: kabeláž pro LAN, optická vlákna - základní vlastnosti, linkové kódy, detekce chyb.
5. Lokální počítačové sítě, přístupové metody ke sdílenému médiu, topologie.
6. Ethernet: princip, varianty-100M/1G/10G, aktivní prvky, VLAN, PoE, topologie, protokol Spanning Tree, strukturovaná kabeláž.
7. WLAN 802.11.
8. Multimediální aplikace: základní požadavky na přenos, protokoly RTP a SIP, služby VoIP, metody zajištění kvality služby v sítích IP.
9. Bezpečnost síťového provozu: základy kryptografie (symetrická, s veřejným klíčem, blokové a proudové šifry), autentizace, kryptografické otisky, certifikáty, SSL.
10. Vysokorychlostní sítě, techniky MPLS, MPlambdaS, fotonické sítě.

# MTEO - Teorie elektronických obvodů
1. Zákony a teorémy v elektronických obvodech.
2. Obvodové funkce a parametry, póly a nulové body, vlastnosti přenosových funkcí.
3. Maticové metody analýzy lineárních obvodů s regulárními a neregulárními prvky.
4. Aplikace metody grafů signálových toků na analýzu obvodů.
5. Citlivostní a toleranční analýza obvodů.
6. Šumová analýza obvodů.
7. Zpětná vazba a stabilita obvodů, oscilační podmínky.
8. Dynamické systémy, oscilátory a PID regulátory.
9. Syntéza pasivních příčkových RLC článků.
10. Analýza nelineárních rezistivních a setrvačných obvodů.

# MCVT - CAD v mikrovlnné technice
1. Základní parametry mikropáskových vedení (efektivní permitivita, šířka, ...).
2. Realizace reaktančních prvků a rezonančních obvodů mikropáskovými vedeními.
3. Postup návrhu kmitočtových filtrů.
4. Postup návrhu planárních filtrů.
5. Postup návrhu planárních antén.
6. Lokální optimalizační metody (nejstrmější sestup, Newtonova metoda).
7. Globální optimalizační metody (genetické algoritmy, metoda roje částic).
8. Princip numerické analýzy vlnovodu metodou konečných diferencí.
9. Princip numerické analýzy vlnovodu metodou konečných prvků.
10. Princip numerické analýzy drátové antény momentovou metodou.

# MMIA - Mikrokontroléry pro pokročilé aplikace
1. Speciální funkce ARM GCC. Optimalizace, volatile, inline, naked a weak funkce. Atomičnost a reentrance.
2. Proměnné globální/lokální, registrové proměnné, zapouzdření proměnných, proměnné v paměti programu. Oddělený překlad.
3. Použití ukazatelů, polí, řetězců. Dynamické paměťové struktury. Předávání proměnných funkcím. Paměťové segmenty.
4. RTOS, kooperativní a preemptivní multitasking. Princip supersmyčky a preemptivního přepínání úkolů. Signály a mutexy.
5. Metody odstraňování zákmitů tlačítek. Připojení optických zobrazovacích prvků, multiplexní řízení LED, posuvné registry.
6. Rozhraní UART (RS232, RS485). Sběrnice I2C, 1-wire a SPI. Použití jednotky DMA.
7. Čítače/časovače (SysTick, generování tónu, princip PWM). Hodiny reálného času.
8. LCD displeje, textové a grafické. Komunikace s řadiči displejů, způsob vykreslování grafiky.
9. Krokové motory, stejnosměrné motory, serva. H-můstek a dead-time.
10. Typy pamětí v mikrokontrolérech, zdroje hodin, úsporné režimy, watchdog, brown-out. Bootloader.

## Otázky pro absolventy MMIA/LMIA 2018/19 a dříve:
1. Speciální funkce AVR GCC. Optimalizace, volatile, inline a naked funkce. Atomičnost a reentrance.
3. Použití ukazatelů, polí, řetězců. Dynamické paměťové struktury. Předávání proměnných funkcím, paměťové nároky při předání proměnné a ukazatele, předávání řetězců v paměti programu.
6. Rozhraní UART (RS232, RS485). Sběrnice I2C, 1-wire a SPI.
7. Čítače/časovače AVR, režimy, princip generování PWM. Záchytná jednotka.

# MIKS - Implementace softwarových komunikačních systémů
1. Architektury vysílačů a přijímačů, pásmové vzorkování, koncept softwarového a softwarově definovaného rádia.
2. Reprezentace čísel, formát Qm, specifika aritmetiky v pevné řádové čárce
3. Algoritmus CORDIC.
4. Celočíselná změna vzorkovacího kmitočtu - interpolace a decimace.
5. CIC filtry - rozdíly, výhody/nevýhody oproti FIR.
6. Efektivní implementace FIR filtrů
7. Přímá číslicová syntéza (DDS), číslicová demodulace FM signálu.
8. Algoritmy pro časovou synchronizaci systémů s jednou (QAM) a s více nosnými (OFDM).
9. Ekvalizace komunikačních signálů.
10. Efektivní implementace FFT - radix 2/4, DIT/DIF, mixed/split-radix.