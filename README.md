# Paravia Cataloghi QA Dataset

Dataset per la valutazione delle capacità di information retrieval di Google NotebookLM sui cataloghi storici della Casa Editrice Paravia (1913-1978).

## Descrizione

Questo dataset contiene 40 domande strutturate per testare l'affidabilità di NotebookLM nell'estrazione di informazioni dai cataloghi didattici per asili e scuole materne pubblicati dalla G.B. Paravia & C.

Il corpus documentale comprende 13 cataloghi (852 pagine totali) conservati presso la Fondazione Tancredi di Barolo, distribuiti nell'arco temporale 1913-1978.

## Struttura del Dataset

### File Principali
- `dataset.csv` - 40 domande con risposte gold standard
- `categories.csv` - Descrizione delle 4 categorie di valutazione

### Categorie di Domande

| Categoria | Descrizione | Numero Domande | Metrica |
|-----------|-------------|----------------|---------|
| **Dati numerici** | Estrazione di valori numerici precisi | 10 | Accuracy |
| **Dati testuali puntuali** | Estrazione di attributi testuali specifici | 10 | Accuracy |
| **Elenchi chiusi** | Estrazione di liste complete | 10 | Accuracy, Precision, Recall |
| **Comparazione** | Confronto tra cataloghi di anni diversi | 10 | Accuracy, Precision, Recall |

## Notebook Sperimentale

Il notebook utilizzato per la sperimentazione è disponibile per la consultazione:
[Cataloghi Paravia - NotebookLM](https://notebooklm.google.com/notebook/a4e5106e-65ca-4e58-bbe9-807662e94092)

## Utilizzo

Il dataset è progettato per essere utilizzato con il notebook sperimentale già configurato:

1. Accedi al notebook tramite il link fornito
2. Esplora i cataloghi Paravia già caricati
3. Testa le 40 domande del dataset
4. Osserva le risposte generate e le citazioni inline
5. Valuta l'affidabilità del sistema RAG

## Contesto della Ricerca

Il dataset è stato sviluppato nell'ambito della ricerca "Intelligenza artificiale generativa e ricerca storico-educativa: sperimentazione sui cataloghi didattici Paravia" (in corso di pubblicazione).

## Citazione

Se utilizzi questo dataset nella tua ricerca, cita come:

```
Palladino, F. (2025). Cataloghi didattici Paravia (1913-1978): Dataset di valutazione per sistemi di information retrieval. 
Zenodo. https://doi.org/10.5281/zenodo.16100127
```

## Licenza

Questo dataset è rilasciato sotto licenza MIT. Vedi il file [LICENSE](LICENSE) per i dettagli.

## Contatti

**Florindo Palladino**  
florindo.palladino@unimol.it

---

**Keywords**: NotebookLM, information retrieval, cataloghi storici, Paravia, storia dell'educazione, intelligenza artificiale generativa
