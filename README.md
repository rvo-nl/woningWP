# Energie Vraagprofiel van een Woning met Warmtepomp en boiler
Effect van een woning met 5 kW Warmtepomp op laag spanning net.

Dit project bevat een eenvoudige **HTML/JavaScript simulatie** van een woning met:
- Warmteweerstand (Rc)
- Oppervlakte warmteuitwisseling (A)
- Warmtecapaciteit van de woning (C_woning)
- Boiler/waterbuffer (C_boiler, instelbaar in liters)
- Warmtepomp met instelbare COP
- Regelingen:

  + Thermostaat gestuurd
  + Modulerend met 2 kW per graad C verschil tussen binnen en buitentemperatuur
  + Zonder verwarming.

De tool laat zien hoe de binnentemperatuur, boiler en warmtepompvermogen reageren op buitentemperatuurschommelingen.  
Het model is een **1R2C-netwerk** en kan gebruikt worden om effecten van isolatie, buffercapaciteit en regeling op het **piekvermogen van het elektriciteitsnet** te onderzoeken.

---

## 🌐 Live Demo
Je kunt de simulatie rechtstreeks openen via GitHub Pages:

👉 [Bekijk de simulatie](https://rvo-nl.github.io/woningWP/)


---

## ⚙️ Gebruik
1. Download of clone de repository:
   ```bash
   git clone https://github.com/rvo-nl/woningWP.git
