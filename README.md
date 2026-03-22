# 🧪 Soil Science & Enzymatic Activity Protocols

### 📂 Overview
Questa sezione documenta le procedure analitiche standardizzate per la valutazione della qualità del suolo, focalizzandosi sulla dinamica del carbonio e sulla funzionalità biochimica microbica.

---

## 1. Caratterizzazione Fisico-Chimica

### 💧 Soil Moisture Content (M.C.)
Determinazione della frazione acquosa tramite metodo gravimetrico per la normalizzazione dei dati successivi sul peso secco (*dry weight basis*).
$$M.C. (\%) = \frac{Fresh\ Weight - Dry\ Weight}{Dry\ Weight} \cdot 100$$

### 🍂 Sostanza Organica (SOM)
Analisi quantitativa della frazione organica totale tramite metodo per incenerimento (*Loss on Ignition*). Il protocollo integra rampe termiche differenziate per distinguere l'umidità igroscopica dalla materia organica ossidabile in muffola.
$$O.M. (\%) = \frac{W_{160°C} - W_{400°C}}{W_{105°C}} \cdot 100$$

---

## 2. Dinamica del Carbonio: Active Carbon (POXC)
Stima del Carbonio Organico Permanganato-Ossidabile (POXC), indicatore della frazione energetica prontamente disponibile per il microbiota.

* **Principio:** Ossidazione selettiva via $KMnO_4$ in ambiente leggermente alcalino.
* **Analisi:** Monitoraggio spettrofotometrico della riduzione del Manganese a **550 nm**.
* **Espressione dei Risultati:** Dati elaborati tramite retta di taratura e normalizzati in $mg/kg$ di carbonio ossidato.

---

## 3. Profilo Enzimatico (Functional Diversity)
Quantificazione delle attività enzimatiche extracellulari come bio-indicatori della salute del suolo.

| Enzima | Funzione Ecologica Target | Rilevazione (nm) |
| :--- | :--- | :--- |
| **FDA Hydrolase** | Attività metabolica microbica totale | 490 |
| **Dehydrogenase (DHA)** | Metabolismo intracellulare attivo | 546 |
| **$\beta$-Glucosidase (BGA)** | Ciclo del Carbonio (idrolisi celluloide) | 398 |
| **Phosphatase (AcP/AlP)** | Ciclo del Fosforo (mineralizzazione P) | 398 |
| **Arylsulphatase** | Ciclo dello Zolfo (esteri del solfato) | 398 |

---

## 🛠️ Standard Metodologici Generali

> [!TIP]
> Per garantire la riproducibilità del dato, tutti i protocolli seguono rigidi standard di controllo:

* **Pre-trattamento:** I campioni sono setacciati (1-2 mm) e conservati a 4°C per preservare l'integrità dei complessi enzimatici prima dell'analisi.
* **Sistemi Tampone:** Reazioni condotte in *Modified Universal Buffer* (MUB) o tamponi specifici (Tris-HCl, Maleato) calibrati sul pH ottimale del target.
* **Correzione del Background:** Ogni saggio include "Bianchi" analitici (suolo + reagente senza incubazione) per sottrarre l'assorbanza intrinseca della matrice.
* **Output Statistico:** Le attività sono espresse come $\mu g$ di prodotto (pNP, TPF o Fluoresceina) per grammo di suolo secco per ora ($\mu g \cdot g^{-1} \cdot h^{-1}$).
