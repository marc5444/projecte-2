# ⚡ Solució Tasca 2 — Estudi i Tria d’un SAI (TecnoGestió S.L.)

## 1️⃣ Inventari d’equips

| Dispositiu | Quantitat | Connexió al SAI (Sí/No) | Justificació |
|------------|-----------|-------------------------|-------------|
| PC | 4 | Sí | Equip essencial per treballar i guardar dades. |
| Monitor | 4 | Sí | Necessari per poder continuar treballant durant tall. |
| Router WiFi | 1 | Sí | Manté connectivitat per accedir a serveis i dades remotes. |
| Impressora multifunció | 1 | No | Alt consum i no essencial durant tall de llum. |

---

## 2️⃣ Especificacions tècniques

| Dispositiu | Model/Referència | Consum (W) | Consum (VA) |
|------------|-----------------|------------|--------------|
| PC | HP ProDesk 400 G6 | 150 W | 200 VA |
| Monitor | Dell P2419H | 25 W | 30 VA |
| Router WiFi | TP-Link Archer C6 | 15 W | 20 VA |

> 💡 *Nota: VA calculat amb factor de potència aproximat 0,75.*

---

## 3️⃣ Càlcul de potència total

| Dispositiu | Quantitat | Potència (VA) | Total (VA) |
|------------|-----------|---------------|------------|
| PC | 4 | 200 | 800 |
| Monitor | 4 | 30 | 120 |
| Router | 1 | 20 | 20 |
| **Total** |  |  | **940 VA** |

**Marge de seguretat del 20%:** 940 × 0,20 = 188 VA  
**Potència final recomanada:** 940 + 188 ≈ **1.128 VA**  

> ✅ Requisit mínim del SAI: **≥1.200 VA**

---

## 4️⃣ Determinació de l’autonomia

- **Autonomia mínima requerida:** 10 minuts  
- **Justificació:** Permet desar treballs, tancar aplicacions i apagar correctament els equips sense perdre dades.

---

## 5️⃣ Models de SAI analitzats

| Marca i model | Potència (VA/W) | Autonomia (min) | Nombre de preses | Preu (€) | Observacions |
|---------------|----------------|-----------------|-----------------|-----------|--------------|
| APC Back-UPS BX1400U-GR | 1400 VA / 700 W | 8–10 | 6 Schuko | 160 € | Marca fiable, bona relació qualitat/preu |
| Eaton Ellipse ECO 1200 USB | 1200 VA / 750 W | 10–12 | 4 Schuko + USB | 180 € | Protecció de línia telefònica, port USB de gestió |
| Salicru SPS SOHO+ 1600 | 1600 VA / 960 W | 10–15 | 6 Schuko | 210 € | Més potència i autonomia, ideal per ampliacions futures |

---

## 6️⃣ Comparació i selecció final

| Característica | APC BX1400U | Eaton ECO 1200 | Salicru SPS 1600 |
|----------------|--------------|----------------|-----------------|
| Potència (VA/W) | 1400 / 700 | 1200 / 750 | 1600 / 960 |
| Autonomia (min) | 8–10 | 10–12 | 10–15 |
| Nombre de preses | 6 | 4 | 6 |
| Preu (€) | 160 | 180 | 210 |
| Funcions addicionals | Protecció línia | Port USB, línia telefònica | Protecció línia, escalable |

### 🏆 Selecció final
- **Model seleccionat:** Salicru SPS SOHO+ 1600 VA / 960 W  
- **Justificació:** Proporciona **suficient potència** amb marge de seguretat, **autonomia adequada** (10–15 min), suficients preses per tots els equips essencials i possibilitat d’ampliació futura. Tot i ser una mica més car, és la millor opció per la fiabilitat i escalabilitat.

---

## 7️⃣ Annexos / Imatges

Afegir captures dels models de SAI i altres recursos visuals dins la carpeta `img/`. Exemple Markdown per afegir imatge:

```markdown
![SAI Salicru SPS SOHO+](./img/salicru_sps.png "SAI Salicru SPS SOHO+ 1600 VA")

