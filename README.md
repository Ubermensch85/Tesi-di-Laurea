# La Blockchain come garanzia di integrità della prova digitale nel sequestro probatorio

<p align="center">
  <b>UNIVERSITÀ DEGLI STUDI DI PERUGIA</b><br>
  <i>Dipartimento di Giurisprudenza</i><br>
  Corso di Laurea Magistrale in Giurisprudenza<br>
  Anno Accademico 2025/2026
</p>

---

## 📋 Informazioni Accademiche

| Voce | Dettaglio |
| :--- | :--- |
| **Candidato** | **Francesco Marra** (Matricola: `245183`) |
| **Relatore** | **Prof.ssa Mariangela Montagna** |
| **Materia** | Diritto Processuale Penale / Diritto dell'Informatica |
| **Documento Finale** | [`Tesi_Definitiva.pdf`](./Tesi_Definitiva.pdf) |

---

## 📖 Sinossi e Abstract

La pervasiva digitalizzazione della società e dell'economia ha mutato radicalmente la fisionomia della criminalità, imponendo all'ordinamento processuale penale una costante opera di adeguamento ermeneutico e normativo. Rispetto all'accertamento tradizionale imperniato sulla tangibilità del *corpus delicti*, la prova contemporanea è frequentemente costituita dal **dato informatico** (*digital evidence*): un'entità per sua natura immateriale, delocalizzata, replicabile all'infinito e fortemente vulnerabile a manipolazioni od omissioni involontarie.

Questa ricerca monografica affronta la discrasia tra l'impianto codicistico formale e la prassi giudiziaria nel momento topico del **sequestro probatorio penale di materiale informatico** (art. 253 c.p.p.), evidenziando come la catena di custodia cartacea costituisca spesso l'anello debole dell'accertamento. Lo studio indaga l'integrazione della **tecnologia Blockchain e dei registri distribuiti (DLT)** quale architettura di validazione e certificazione crittografica della *Chain of Custody* (CoC).

### Principali nodi tematici indagati:
1. **La crisi dell'Art. 253 c.p.p.**  
   Il contrasto tra una norma concepita per cose materiali e la dematerializzazione del dato; la censura della cd. *fictio iuris* del «sequestro di massa» indifferenziato alla luce del canone di proporzionalità (Cass. Sez. Unite n. 31022/2015, *sentenza Fazzo*) e i recenti moniti della Corte di Giustizia dell'Unione Europea (CGUE) sui diritti fondamentali e la riservatezza.
2. **Best Practice forensi e Catena di Custodia**  
   L'analisi della Convenzione di Budapest sui reati informatici e degli standard internazionali (**ISO/IEC 27037**). Dal punto tecnico (copia bit-stream forense, calcolo di funzioni hash crittografiche SHA-256) all'atto pratico della gestione documentale: le criticità della gestione cartacea tradizionale nei tribunali.
3. **Validazione crittografica e Smart Contracts**  
   Il registro distribuito come presidio di notarizzazione temporale immutabile (*timestamping*) e integrità distribuita, e l'impiego di smart contract per automatizzare le autorizzazioni di accesso, perizia e passaggio di consegne del reperto informatico.
4. **Valore probatorio nell'ordinamento italiano**  
   L'inquadramento ex **Art. 8-ter D.L. n. 135/2018** (conv. in L. n. 12/2019) e il raccordo con l'art. 41 del Regolamento europeo **eIDAS** (validazione temporale elettronica); l'ammissibilità della prova digitale notarizzata su DLT nell'alveo della prova atipica (art. 189 c.p.p.) e il libero convincimento motivato del giudice penale.
5. **Sfide tecniche, dogmatiche ed etiche**  
   - Il limite ontologico del **GIGO (*Garbage In, Garbage Out*)**: la blockchain garantisce la persistenza e l'immutabilità del dato dal momento della marcatura, ma non l'attendibilità della sorgente antecedente, imponendo rigorosi protocolli di acquisizione certificata *ab origine*.
   - Il contrasto tra l'immodificabilità della blockchain e la normativa privacy europea (**GDPR**, diritto all'oblio e cancellazione dei dati ex art. 17).
   - Il **trilemma della blockchain** (decentralizzazione, scalabilità, sicurezza) nei sistemi di giustizia penale e le prospettive di una disciplina organica de iure condendo.

---

## 🗂️ Struttura dell'Opera e Indice

```
TESI DI LAUREA
│
├── Introduzione ................................................. Pag. 5
│
├── Capitolo 1: La Prova Digitale nel Sistema Processuale Penale . Pag. 7
│   ├── 1.1 Art. 253 c.p.p.: Dalla Realtà Analogica al Contesto Digitale
│   └── 1.2 Garanzie Preventive Indebolite Sotto la Lente della CGUE
│
├── Capitolo 2: Best Practice e Catena di Custodia: Un Obiettivo Mancato . Pag. 28
│   ├── 2.1 La Convenzione di Budapest
│   ├── 2.2 Tecniche di acquisizione forense
│   └── 2.3 Frattura tra atto tecnico e gestione procedurale
│
├── Capitolo 3: Blockchain come Strumento di Validazione della Prova ..... Pag. 56
│   ├── 3.1 Il Registro Distribuito come Garanzia di Integrità nella Digital Forensics
│   └── 3.2 Smart Contracts: Da Registro Passivo a Piattaforma Attiva
│
├── Capitolo 4: Framework Operativi e Valore Probatorio nel Contesto Italiano . Pag. 77
│   ├── 4.1 Modelli Applicativi come «Forensic-Chain»
│   ├── 4.2 Riconoscimento da Parte del Nostro Ordinamento Giuridico (D.L. Semplificazioni)
│   └── 4.3 Blockchain come Prova Atipica
│
├── Capitolo 5: Sfide e Prospettive Future ....................... Pag. 102
│   ├── 5.1 Contrasto con il GDPR
│   ├── 5.2 Il Trilemma della Blockchain
│   └── 5.3 Necessario Intervento Normativo
│
├── Conclusioni ................................................. Pag. 128
│
└── Bibliografia ................................................ Pag. 131
```

---

## 📁 Organizzazione dei File nel Repository

| Percorso | Formato | Descrizione |
| :--- | :--- | :--- |
| [`Tesi_Definitiva.pdf`](./Tesi_Definitiva.pdf) | PDF (136 pagg.) | Testo integrale e impaginato definitivo della tesi di laurea |
| [`docx/Indice.docx`](./docx/Indice.docx) | Word (DOCX) | Indice analitico e sommario dell'opera |
| [`docx/Introduzione.docx`](./docx/Introduzione.docx) | Word (DOCX) | Testo dell'Introduzione |
| [`docx/Capitolo 1.docx`](./docx/Capitolo%201.docx) | Word (DOCX) | Capitolo 1: *La Prova Digitale nel Sistema Processuale Penale* |
| [`docx/Capitolo 2.docx`](./docx/Capitolo%202.docx) | Word (DOCX) | Capitolo 2: *Best Practice e Catena di Custodia: Un Obiettivo Mancato* |
| [`docx/Capitolo 3.docx`](./docx/Capitolo%203.docx) | Word (DOCX) | Capitolo 3: *Blockchain come Strumento di Validazione della Prova* |
| [`docx/Capitolo 4.docx`](./docx/Capitolo%204.docx) | Word (DOCX) | Capitolo 4: *Framework Operativi e Valore Probatorio nel Contesto Italiano* |
| [`docx/Capitolo 5.docx`](./docx/Capitolo%205.docx) | Word (DOCX) | Capitolo 5: *Sfide e Prospettive Future* |
| [`docx/Conclusioni.docx`](./docx/Conclusioni.docx) | Word (DOCX) | Conclusioni finali e prospettive dogmatico-forensi |

---

## ⚖️ Citazione Bibliografica Consigliata

Se utilizzi o citi questo lavoro di ricerca per fini accademici, si prega di fare riferimento alla seguente citazione:

```bibtex
@thesis{marra2026blockchain,
  author       = {Francesco Marra},
  title        = {La Blockchain come garanzia di integrità della prova digitale nel sequestro probatorio},
  school       = {Università degli Studi di Perugia, Dipartimento di Giurisprudenza},
  year         = {2026},
  type         = {Tesi di Laurea Magistrale in Giurisprudenza},
  note         = {Relatore: Prof.ssa Mariangela Montagna, A.A. 2025/2026}
}
```

---
*Università degli Studi di Perugia — Tutti i diritti riservati all'autore.*
