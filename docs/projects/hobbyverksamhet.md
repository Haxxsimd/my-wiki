---
tags:
  - projects
  - business
  - electronics
  - batteries
  - scooter
---

# Hobbyverksamhet — Elektronikreparation & Batteriservice

Planeringsdokument för en eventuell hobbyverksamhet/eget företag tillsammans med
en kompis (elektriker, 20+ års erfarenhet, tidigare eget företag). Ursprungligen
skrivet 2026-08-11 till 2026-08-20.

**Rollfördelning:** Jag hanterar mikroelektronik, firmware och programmering.
Kompisen hanterar starkström, installation och praktiskt arbete.

## Affärsidé & Nischer

Planerade tjänster:

- **Batterireparationer** — cellbyte i elcyklar, elsparkcyklar, laptops, elverktyg (Bosch/Makita)
- **Firmware-optimering** — flasha om elcyklar (inom lagliga ramar), slippa dyra trimboxar
- **Reparation & service** — elsparkcyklar, elcyklar, billjud
- **IoT & smarta hem** — installation + konfigurering (han drar kablar, jag konfigurerar nätverk/appar)
- **Allmän elektronikreparation** — datorer, telefoner, Li-Ion-celler, lödsvetsning

Målgrupp: föräldrar med barns trasiga elsparkcyklar, äldre/teknikovana som vill
ha smarta hem-lösningar, folk som vill laga istället för köpa nytt.

## Företagsform & Juridik

!!! warning "Viktigast att lösa innan uppstart"
    Båda har skulder hos Kronofogden → enskild firma/handelsbolag är riskabelt
    eftersom intäkter kan utmätas direkt.

**Alternativ som diskuterats:**

- **Aktiebolag (AB)** — bolaget är egen juridisk person, men styrelseledamöter
  måste vara "skötsamma" för vissa tillstånd.
- **Trovärdig kamrat utan skulder** som formell ägare/VD, medan vi arbetar mot
  lön/konsultarvode. Kräver skrivet avtal och absolut tillit.
- Börja som hobby/BDB eller under någon annans befintliga F-skatt som underleverantörer.

**Nästa steg:** Boka gratis första samtal med redovisningskonsult — förklara
situationen öppet och se vad som är möjligt.

**Säkerhet & regler:**

- **Elsäkerhetslagen:** Kompisen har behörighet, men se till att anmälan/egenkontroll sköts rätt.
- **Li-Ion-batterier:** Brandsäker laddningsväska/gjutjärnsgryta, brandsläckare klass D + ABF,
  arbeta aldrig med skadade celler.
- **GDPR:** Spara aldrig kunddata i Messenger/WhatsApp. Använd krypterad lagring.
  Skriv enkelt personuppgiftsbiträdesavtal om vi använder molntjänst.
- **Miljöfarligt avfall:** Batterier och elektronikskrot till auktoriserad mottagare.
- **Dokumentera allt:** Före/efter-bilder, kvitton, Swish/banköverföring (undvik kontanter).

## Utrustning & Inköpslista

### 🔴 Hög prioritet (köp nu)

| Pryl | Var | Pris |
|---|---|---|
| Punktsvetsare (Sunkko 709A el. liknande) | AliExpress / Begagnat | 1 500–2 500 kr |
| Celltestare (LiitoKala Lii-500 / Opus) | AliExpress / Amazon.de | 350–500 kr |
| 10S BMS 30A med balansering | AliExpress | 150–250 kr |
| 18650-celler (Samsung, LG, Molicel) | NKON.nl (EU, ingen tull) | 25–40 kr/cell |
| Buntband storpack | Biltema | 30–80 kr |
| Krympslang blandat | Biltema / Electrokit | 50–100 kr |

### 🟡 Medium prioritet (inom 2–4 veckor)

| Pryl | Var | Pris |
|---|---|---|
| Mindre lödkolv / SMD-penna (TS100) | AliExpress / Amazon.de | 300–600 kr |
| Större lödstation med varmluft (60–80W) | AliExpress / Begagnat | 600–1 200 kr |
| Lödhållare + förstoringsglas + LED | Electrokit / Kjell | 200–450 kr |
| Antistatmatta + armband | Electrokit / Kjell | 100–200 kr |
| Ninebot G30 styrenhet (ESC) | AliExpress / eBay | 800–1 500 kr |
| Ninebot G30 kablage komplett | AliExpress / eBay | 200–400 kr |
| Ninebot G30 framdäck + slang (10") | AliExpress / Cykelbutik | 150–300 kr |
| Oscilloskop (Hantek 6022BE / DSO138) | AliExpress / Begagnat | 400–1 200 kr |
| DDR4 16GB 3200MHz+ | SweClockers / Tradera | 300–500 kr |
| Ryzen 5 5600 / 5600X / 3700X | SweClockers / Tradera | 800–1 400 kr |

### 🟢 Låg prioritet (när tillfälle ges)

| Pryl | Var | Pris |
|---|---|---|
| Arduino UNO/Nano/Pro Mini (3–5 st) | AliExpress / Electrokit | 40–80 kr/st |
| ESP32 DevKit (5 st) | AliExpress / Amazon.de | 40–60 kr/st |
| Breadboard 830-håls + 2× mini | AliExpress / Electrokit | 30–60 kr/st |
| Hopp-sladdar M-M/M-F/F-F (120 st) | AliExpress / Electrokit | 40–80 kr |
| Resistor-kit + kondensator-kit + LED-kit | AliExpress / Electrokit | 100–180 kr |
| CH340 USB-TTL (5 st) | AliExpress | 100–200 kr |
| FT232RL FTDI (3 st) | AliExpress | 120–180 kr |
| USB-kablar Micro-USB + USB-C (5 st vardera) | AliExpress / Kjell | 100–200 kr |
| RFID-läsare/programmerare (RC522 / PN532) | AliExpress / Electrokit | 50–150 kr |
| RFID-taggar/kort/brickor (10–20 st) | AliExpress | 30–80 kr |
| Mindre multimeter (portabel) | Kjell / Biltema | 100–300 kr |
| Större multimeter (kvalitetsmärke) | Kjell / Electrokit | 400–800 kr |
| 9V-batterikontakt | Tradera (BAMJO-ELEKTRONIK) | 36 kr |
| Smältlim + limpistol (lågtemp) | Biltema / Clas Ohlson | 50–150 kr |
| Elektroniksilikon / RTV-silikon | Biltema / Kjell | 50–100 kr |
| Kabelskor / ringkabelskor (M4–M6) | Biltema / Electrokit | 30–60 kr |
| Dubbelhäftande tejp / 3M VHB | Biltema / Clas Ohlson | 50–100 kr |
| Kabelkanaler / sleevad kabel | Biltema / Electrokit | 50–150 kr |
| Bordslampa LED med flexarm | IKEA TERTIAL / Kjell | 60–200 kr |
| Lödspetsar blandade | AliExpress / Electrokit | 50–100 kr |
| Lödpasta + flussmedel | Electrokit / Kjell | 50–100 kr |

### PC-komponenter (begagnat)

| Pryl | Var | Pris |
|---|---|---|
| DDR4 16GB 3200MHz+ | SweClockers / Tradera | 300–500 kr |
| DDR3 ECC REG till X79 – 8 st identiska | Tradera / Blocket | 150–400 kr |
| Chassi ATX/mATX | Blocket / FB Marketplace | 100–300 kr |
| GPU 8GB+ (RX 5700 XT / RTX 2070S / 2080) | SweClockers / Tradera | 1 200–2 500 kr |

!!! note "X79 + Xeon E5-2680 v2"
    Kontrollera om moderkortet är kinesiskt (Huanan/Machinist/Jingsha) – då krävs
    DDR3 ECC REG (serverminne), inte vanlig DDR3. 8×4GB ECC REG kan kosta 150 kr
    totalt begagnat. Se [[desktop-x79]] för nuvarande specs.

## AliExpress 2026 — Så Funkar Det Nu

- Moms 25% gäller på allt utanför EU (sedan 2021).
- Från 1 juli 2026: fast tull på 3 euro (~33 kr) per varutyp på paket under 1 655 kr.
- Per varutyp, inte per paket: BMS + ESP32 + CH340 i samma paket = 3 varutyper = 9 euro i tull.
- Från november 2026: EU-hanteringsavgift ~2 euro per försändelse.
- IOSS: se till att säljaren har det (står i kassan), annars tar PostNord 100–250 kr extra.

**Strategi:** Samla till en stor order — färre varutyper = mindre tull. Större/dyrare
prylar lönar sig mer (punktsvetsare, celltestare, lödstation). Småbeställningar under
200 kr har dött — blir dyrare än svenskt alternativ. Celler köps från NKON.nl
(Nederländerna, ingen tull, snabb frakt, garanterat äkta).

## Batterier & 18650-celler — Arbetsflöde

**Säkerhetsregler:**

1. Skadad cell (bukt, rost, varm) = kastas direkt.
2. Ladda aldrig obevakat. Brandsäker väska eller gjutjärnsgryta med lock.
3. Tejpa alltid pluspolen med isolertejp när cellerna ligger lösa.

**Testa laptop-celler:**

1. Mät vilospänning: >3.0V = OK. 2.5–3.0V = testa långsamt. <2.5V = kassera.
2. Ladda: 4.20V, 0.5A (500mA). Håll koll på värme.
3. Vila 24h: mät igen. >4.10V = godkänd. <4.10V = hög självurladdning, kassera
   eller använd till ficklampa.
4. Kapacitetstest: 12V bilglödlampa 21W eller 10 ohm resistor. Klocka tiden från
   4.2V till 3.0V. Beräkna: Ah = ström(A) × timmar.

**Ninebot G30-batteri efter 2 år:**

- Mät totalspänning: 36–42V = bra. Under 30V = öppna och mät varje cellgrupp.
- BMS kan ha gått i djupvila — vissa väcks med "jump start" (avancerat).
- Ninebot G30 är 10S4P eller 10S5P. Cellgrupper ska ligga inom 0.05V från varandra.

**BMS:** räkna seriekopplingar (S) — 10 celler i serie = 10S BMS. Ström: välj minst
30A kontinuerligt för marginal. Aktiv balansering helst, annars passiv.

## Ninebot G30 — Bygga Ihop Eller Sälja Delar?

Se även [[scooter]] för teknisk historik kring firmware/BLE på en annan Xiaomi-enhet.

**Har:** batteri (oklart skick, legat 2 år), motor, chassi
**Saknas:** styrenhet (ESC): 800–1 500 kr, kablage: 200–400 kr, framdäck + slang: 150–300 kr.
Totalt: ~1 150–2 200 kr.

| Alternativ | Intäkt | Kommentar |
|---|---|---|
| Sälja motor + batteri | 1 100–2 700 kr | Troligen ~1 500 kr, batteriet osäkert |
| Bygga ihop hel sparkcykel | 3 000–5 000 kr | Investera ~1 500 kr → dubbelt så lönsamt |

**Beslutsträd:**

1. Mät batteriet: >36V och tar laddning = behåll och bygg ihop.
2. Under 30V eller tar inte laddning = sälj motor + batteri som paket på Blocket
   för 1 000–1 500 kr, var ärlig med skicket.
3. Om vi måste ha pengar till punktsvetsaren NU och har en kund som väntar = sälj,
   men försök låna/be förskott först.

## Priser & Tjänster Att Erbjuda

**Paket 1: "Elsparkcykel-klar"**

- Felsökning: 300 kr (dras av vid reparation)
- Bromsjustering + däck + smörjning: 400–600 kr
- Batteridiagnos + cellbyte: 800–1 500 kr
- Firmware-uppgradering: 300–500 kr
- XT30 → XT60 + säkerhetsgenomgång: 200–300 kr

**Paket 2: "Batteridoctor"**

- Elcykelbatteri – cellbyte: 1 500–3 000 kr
- Laptop-batteri – cellbyte: 400–800 kr
- Elverktyg-batteri (Bosch, Makita): 600–1 200 kr

**Paket 3: "Smart hem för vanligt folk"**

- Installera smarta brytare, sensorer, kameror: 500–1 000 kr/timme tillsammans

Varför batterireparationer är guld: Ny elcykelbatteri = 4 000–8 000 kr. Vi erbjuder
cellbyte för 2 500 kr med 1 års funktionsgaranti. Vinstmarginal: 40–60%.

## Server, VPS & Fildelning

**Internt nu – gratis:**

| Lösning | Vad den gör | Kostnad |
|---|---|---|
| Syncthing | P2P-fildelning mellan alla enheter, krypterat | 0 kr |
| Tailscale | VPN mellan alla prylar, fasta IP-adresser | 0 kr |
| Nextcloud | Egen Dropbox, webbgränssnitt (på Xeon-servern) | 0 kr |

**För kunder – senare:**

| Behov | Lösning | Kostnad |
|---|---|---|
| Hemsida | GitHub Pages / Netlify / Cloudflare | 0 kr |
| Bildgalleri | Nextcloud på VPS, eller privat FB/IG | 0–50 kr/mån |
| Bokning/kalender | Calendly (gratis) | 0 kr |
| Fakturering | Fakturino / Bokio / Fortnox | 0–200 kr/mån |

**VPS-leverantörer (när det behövs):**

| Leverantör | Pris/mån | Spec |
|---|---|---|
| Oracle Cloud Free Tier | 0 kr | 2 vCPU, 1GB RAM – för alltid |
| Hetzner CX11 | ~40 kr | 1 vCPU, 2GB RAM |
| Contabo VPS S | ~55 kr | 4 vCPU, 8GB RAM, 200GB SSD |

**Roadmap:** Syncthing + Tailscale nu → Nextcloud på Xeon-servern om 1–2 månader →
gratis hemsida vid 5+ kunder → Oracle Cloud Free Tier vid 10+ kunder.

## Termux På Samsung Tab A8 (Rootad)

Se [[phones-tablets]] för fullständig hårdvarustatus på surfplattan.

**Användbara kommandon installerade:**

```bash
pkg update && pkg upgrade -y
pkg install python git vim wget fzf zsh
pip install esptool pyserial
pkg install stlink openocd
```

**Oh My Zsh – byt tema:**

```bash
ls ~/.oh-my-zsh/themes/
omz theme set bira
sed -i 's/ZSH_THEME=".*"/ZSH_THEME="bira"/' ~/.zshrc
echo 'DEFAULT_USER="you"' >> ~/.zshrc
source ~/.zshrc
```

**Anpassad prompt (lägg i `~/.zshrc`):**

```bash
PROMPT='%F{cyan}⚡%f %F{yellow}%~%f $(git_prompt_info) %F{green}$%f '
```

**USB-OTG + programmering:**

```bash
ls /dev/tty*                    # Se ansluten enhet
st-info --probe                 # Testa ST-Link
esptool.py --port /dev/ttyUSB0 flash_id   # Testa ESP32
picocom -b 115200 /dev/ttyUSB0  # Seriell monitor
```

**Interaktiv pakethanterare (`pkgu`):**

```bash
cat > $PREFIX/bin/pkgu << 'EOF'
#!/data/data/com.termux/files/usr/bin/bash
if ! command -v fzf &> /dev/null; then
    echo "fzf saknas. Installerar..."
    pkg install fzf -y
fi
PKG=$(pkg list-all | fzf --prompt="Sök paket (ESC=avbryt): " --height=80% --reverse --header="Piltangenter=navigera | Enter=välj | ESC=avbryt")
[ -z "$PKG" ] && { echo "Inget valt."; exit 0; }
NAME=$(echo "$PKG" | awk '{print $1}')
echo "Valt: $NAME"
read -p "Installera? [Y/n]: " CONFIRM
CONFIRM=${CONFIRM:-Y}
[[ "$CONFIRM" =~ ^[Yy]$ ]] && pkg install "$NAME" -y || echo "Avbrutet."
EOF
chmod +x $PREFIX/bin/pkgu
```

**Snabbkommandon för projektet (lägg i `~/.zshrc`):**

```bash
alias nb='cd ~/ninebot'
alias flash='esptool.py --port /dev/ttyUSB0'
alias st='st-info --probe'
alias ls='ls --color=auto'
alias ll='ls -lah --color=auto'
```

## Nästa Steg — Konkret Agenda

**Denna vecka:**

- [ ] Mät Ninebot G30-batteriet (vilospänning, tar det laddning?)
- [ ] Ladda upp "Köpes"-annons på SweClockers (DDR4, Ryzen 5 5600, chassi)
- [ ] Beställ buntband + krympslang + smältlim på Biltema
- [ ] Lägg en stor AliExpress-order: punktsvetsare, celltestare, BMS, nickelremsa,
      CH340, FTDI, ESP32, Arduino-kit, XT-kontakter
- [ ] Installera Syncthing på Tab A8, telefon och Xeon-server
- [ ] Installera Tailscale på samma enheter

**Nästa vecka:**

- [ ] Träffa kompisen – gör live-demo med 4 laptop-celler + BMS
- [ ] Diskutera: juridik/företagsform, första tjänst, investeringar, arbetsfördelning
- [ ] Beställ 18650-celler från NKON.nl
- [ ] Kolla Tradera/Blocket efter DDR3 ECC REG till X79

**Inom 1 månad:**

- [ ] Första betalda jobbet (batterireparation eller elsparkcykel-service)
- [ ] Sätt upp Nextcloud på Xeon-servern i garaget
- [ ] Utvärdera samarbetet – fungerar det? Dags att formalisera?

## Kontakter & Resurser

- [NKON.nl](https://www.nkon.nl) — 18650-celler inom EU
- Electrokit — elektronikkomponenter i Sverige
- Kjell & Company — verktyg, tillbehör
- Biltema — buntband, krympslang, lim, silikon
- SweClockers marknad — begagnade PC-komponenter
- Scooterhacking.org — Ninebot-dokumentation och firmware
- GitHub — sök "ninebot g30 firmware", "esptool", "bms-tools"

---

*Skapat: 2026-08-11 till 2026-08-20. Sammanfattar en konversation om att starta
hobbyverksamhet inom elektronikreparation och batteriservice. Alla priser och
lagar är aktuella per augusti 2026.*
