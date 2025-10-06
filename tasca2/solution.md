# ⚡ Informe tècnic: Estudi i selecció d’un SAI per a TecnoGestió S.L.

## 1️⃣ Inventari d’equips

Dispositius que es connectaran al SAI:

- 4 ordinadors de sobretaula + monitors (imprescindibles per al treball diari)
- 1 router d’accés a Internet (per garantir connexió mentre es fa el tancament de tasques)
- 1 impressora-fotocopiadora multifunció → **No es connectarà al SAI**

**Justificació:**  
Les impressores làser/multifunció tenen un consum molt alt en el moment d’impressió (picos > 1000 W) i no són crítiques en cas de tall elèctric. El SAI es destinarà a mantenir els equips de treball i la xarxa actius uns minuts per poder desar i apagar correctament.

---

## 2️⃣ Especificacions dels dispositius

| Dispositiu | Model aproximat | Consum (W) | Consum (VA) |
|------------|----------------|------------|-------------|
| PC sobretaula (ofimàtica, CPU i placa base) | Dell OptiPlex 7010 | 200 W | 250 VA |
| Monitor LED 24’’ | Dell P2419H | 30 W | 40 VA |
| Router (tipus SOHO) | TP-Link Archer AX20 | 15 W | 20 VA |

**Càlcul de consum:**

- Per unitat PC + monitor: 200 W + 30 W = 230 W (≈ 290 VA)  
- Total per 4 ordinadors amb monitors: 4 × 230 W = 920 W (≈ 1160 VA)  
- Router: 15 W (20 VA)

**TOTAL:**  
- Potència activa (W): 935 W  
- Potència aparent (VA): 1180 VA

---

## 3️⃣ Càlcul de potència amb reserva

Es recomana afegir un **20% de marge de seguretat**:

- W totals amb marge = 935 × 1,2 = 1122 W  
- VA totals amb marge = 1180 × 1,2 = 1416 VA

**Conclusió:** Necessitem un SAI d’almenys **1500 VA i 1100 W**.

---

## 4️⃣ Determinació de l’autonomia

- **Objectiu:** Mantenir funcionament mínim de 10 minuts per desar i apagar.  
- Per una càrrega d’uns 900–1000 W, buscarem SAIs que ofereixin **10–15 minuts d’autonomia** en aquest rang.

---

## 5️⃣ Models de SAI analitzats

### Eaton 5SC 1500i
- Potència: 1500 VA / 1050 W  
- Autonomia: ~10 minuts al 50% de càrrega (més curta al 100%)  
- Sortides: 8 preses IEC C13  
- Preu: ~400 €  
- Observacions: Marca fiable, orientada a pimes

### APC Back-UPS Pro BR1500G
- Potència: 1500 VA / 865 W  
- Autonomia: ~13 min al 50% de càrrega  
- Sortides: 6 Schuko  
- Preu: ~350 €  
- Observacions: Marca molt reconeguda, però pot quedar curta en W (865 W < 935 W necessaris)

### Salicru SPS SOHO+ 1600VA
- Potència: 1600 VA / 960 W  
- Autonomia: 12 min al 50% de càrrega  
- Sortides: 4 Schuko + USB de gestió  
- Preu: ~300 €  
- Observacions: Fabricant estatal, bon preu/prestacions, suficient per a la càrrega real (935 W ≈ límit)

---

## 6️⃣ Comparació resumida

| Model | VA/W | Autonomia | Preu aprox. | Observacions |
|-------|------|-----------|------------|--------------|
| Eaton 5SC 1500i | 1500 / 1050 | ~10 min | 400 € | Seguretat, professional |
| APC BR1500G | 1500 / 865 | ~13 min | 350 € | Marca top, però pot quedar curta en W |
| Salicru SPS SOHO+ 1600 | 1600 / 960 | ~12 min | 300 € | Bona relació qualitat-preu |

---

## 7️⃣ Selecció final i justificació

**Model recomanat:** Eaton 5SC 1500i  

**Raons de la selecció:**
- Supera els requisits de potència (1050 W > 935 W + marge)  
- Marca de confiança amb bona gestió i fiabilitat  
- Permet assegurar els 10 minuts mínims d’autonomia amb càrrega propera al 80%

**Alternativa més econòmica:** Salicru SPS SOHO+ 1600VA, vàlida si el pressupost és molt ajustat, però amb menor marge de seguretat.

**Conclusió:**  
Per garantir **continuïtat de servei** i **protecció dels equips**, es recomana la compra del SAI **Eaton 5SC 1500i**.

---

📄 **Autor/a:** *[El teu nom]*  
📅 **Data:** *Octubre 2025*  
🏢 **Projecte:** EverPia – Tasca 2: Tria SAI per a TecnoGestió S.L.


