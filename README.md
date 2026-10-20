# Electronic Load

<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/KiCad-Schematic-314CB0?style=flat&logo=kicad&logoColor=white" alt="KiCad"></a>
  <a href="#"><img src="https://img.shields.io/badge/LTspice-Simulation-blue?style=flat" alt="LTspice"></a>
  <img src="https://img.shields.io/badge/Status-Work%20in%20Progress-orange?style=flat" alt="Work in Progress"/>
</p>

Un progetto open-source per la progettazione e simulazione di un **Carico Elettronico Bipolare** (Electronic Load), ideato per il test e la caratterizzazione di alimentatori, batterie e circuiti di potenza.

---

## Caratteristiche del Progetto

* **Simulazioni LTspice**: Analisi del comportamento dinamico e della risposta del circuito di controllo.
* **Sbrogliato KiCad**: Schemi elettrici e layout PCB completi per la realizzazione dell'hardware.
* **Modalità di funzionamento**: Progettato per operare in corrente costante (*CC*).

---

## Struttura del Repository

```text
electronic_load/
├── LTspice/       # File di simulazione (.asc, .plt)
├── KiCad/         # Schemi (.kicad_sch) e PCB (.kicad_pcb)
└── README.md
