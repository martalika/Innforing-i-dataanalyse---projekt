# Innf-ring-i-dataanalyse---projekt
Kort sammendrag (2025-10-15 22:17):

- Datakilde: CSV (eksisterende df_all gjenbrukt) — Pris (ørekWh) per time for prisområder NO1, NO2, NO3, NO4, NO5 (1).csv
- Områdevalg: postnummer → område 
- Datoperiode brukt: alle datoer (september 2023 til september 2025, antall dager: 768)
  
- Metode (Del 5: realistisk forbruksmønster):
  • Morgen-vindu 06–09 med 35% av døgnet
  • Kveld-vindu  16–22 med 50% av døgnet
  • Resterende forbruk fordelt jevnt på øvrige timer
  
- Beregninger:
  
  • Peak-vindu-snitt (kun 06–09 & 16–22)
  • 24t vektet snitt (etter mønsteret over)
  • 24t flatt snitt (referanse)
  
- Resultater (øre/kWh):
  • Peak-vindu: 64.61
  • Vektet 24t: 62.35
  • Flatt 24t : 56.47
  
- Sammenligning med Norgespris = 40.00 øre/kWh:
- Område NO1, zip 0768
  • Peak  vs Norgespris: +24.61 øre → dyrere enn Norgespris
  • Vektet vs Norgespris: +22.35 øre → dyrere enn Norgespris
  • Flatt  vs Norgespris: +16.47 øre → dyrere enn Norgespris

  <img width="520" height="320" alt="image" src="https://github.com/user-attachments/assets/e5ca0775-135f-4a5c-8113-f0e2546065d9" />

