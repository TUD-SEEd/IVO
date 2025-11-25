# Speciale Weerstanden: NTC en PTC

## Inleiding

In de elektronica komen we verschillende soorten weerstanden tegen. Twee bijzondere types zijn **thermistoren**: weerstanden waarvan de weerstandswaarde afhangt van de temperatuur. We onderscheiden twee hoofdtypen:

- **NTC** (Negative Temperature Coefficient)
- **PTC** (Positive Temperature Coefficient)

## NTC-weerstanden

### Wat is een NTC?

Een NTC-weerstand heeft een **negatieve temperatuurcoëfficiënt**. Dit betekent:
- Als de temperatuur stijgt → de weerstand daalt
- Als de temperatuur daalt → de weerstand stijgt

### Eigenschappen

De weerstand van een NTC volgt ongeveer deze relatie:

R(T) = R₀ · e^(B/T)

Waarbij:
- R(T) = weerstand bij temperatuur T (in Kelvin)
- R₀ = weerstand bij referentietemperatuur
- B = materiaalconstante (B-waarde)
- e = grondgetal natuurlijke logaritme

### Toepassingen

1. **Temperatuurmetingen** - thermometers, koelkasten
2. **Inschakelbegrenzing** - bescherming van elektronische circuits
3. **Branddetectie** - in rookmelders

## PTC-weerstanden

### Wat is een PTC?

Een PTC-weerstand heeft een **positieve temperatuurcoëfficiënt**. Dit betekent:
- Als de temperatuur stijgt → de weerstand stijgt
- Als de temperatuur daalt → de weerstand daalt

### Gedrag visualisatie

Hier zie je het gedrag van een NTC in actie:

![NTC gedrag](IVO/Figuren/NTC.gif)

### Eigenschappen

Bij PTC's onderscheiden we vaak twee zones:
- **Lineaire zone**: geleidelijke toename van weerstand
- **Schakelzone**: sterke toename bij kritische temperatuur (Curie-temperatuur)

### Toepassingen

1. **Zelfbegrenzende verwarmingen** - vloerverwarming, ontdooiing
2. **Overcurrent beveiliging** - als stroombeveiliging
3. **Motorbeveiliging** - tegen oververhitting
4. **Startstroom begrenzing** - in voedingen

## Vergelijking NTC vs PTC

| Eigenschap | NTC | PTC |
|------------|-----|-----|
| Temperatuur ↑ | Weerstand ↓ | Weerstand ↑ |
| Materiaal | Metaaloxiden (Co, Ni, Mn) | Bariumtitanaat (keramiek) |
| Hoofdtoepassing | Temperatuurmeting | Zelfregulerende verwarming |
| Gedrag | Exponentieel | Vaak abrupt bij Tc |


## Bronnen en verder lezen

- [Wikipedia: Thermistor](https://nl.wikipedia.org/wiki/Thermistor)
- Natuurkundeboek hoofdstuk elektrische schakelingen

---

*Gemaakt voor het vak Natuurkunde - TUD-SEEd IVO*
