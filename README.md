# Paravia Cataloghi QA Dataset

Dataset per la valutazione delle capacità di information retrieval di Google NotebookLM sui cataloghi storici della Casa Editrice Paravia (1913-1978).

## Descrizione

Questo dataset contiene 40 domande strutturate per testare l'affidabilità di NotebookLM nell'estrazione di informazioni dai cataloghi didattici per asili e scuole materne pubblicati dalla G.B. Paravia & C.

Il corpus documentale analizzato comprende 13 cataloghi (852 pagine totali) conservati presso la Fondazione Tancredi di Barolo, distribuiti nell'arco temporale 1913-1978.

## Struttura del Dataset

### File Principali
- `set di dati.csv` - 40 domande con risposte gold standard
- `categorie.csv` - Descrizione delle 4 categorie di valutazione

### Categorie di Domande

| Categoria | Descrizione | Numero Domande | Metrica |
|-----------|-------------|----------------|---------|
| **Dati numerici** | Estrazione di valori numerici precisi | 10 | Exact Match |
| **Dati testuali puntuali** | Estrazione di attributi testuali specifici | 10 | Exact Match |
| **Elenchi chiusi** | Estrazione di liste complete | 10 | F1-Score |
| **Comparazione** | Confronto tra cataloghi di anni diversi | 10 | Accuracy |

## Utilizzo

Il dataset è progettato per la valutazione manuale di NotebookLM attraverso:

1. Caricamento dei cataloghi Paravia in NotebookLM
2. Formulazione delle domande dal dataset
3. Registrazione e valutazione delle risposte
4. Calcolo delle metriche per categoria

## Metodologia

Il dataset è stato sviluppato nell'ambito della ricerca "Intelligenza artificiale generativa e ricerca storico-educativa: sperimentazione sui cataloghi didattici Paravia".

### Criteri di Selezione
- **Fonti**: Cataloghi didattici per asili e scuole materne (1913-1978)
- **Bilanciamento**: 10 domande per categoria
- **Validazione**: Gold standard definiti tramite analisi manuale delle fonti

## Citazione

Se utilizzi questo dataset nella tua ricerca, cita come:

```
Palladino, F. (2025). Paravia Cataloghi QA Dataset: Information Retrieval Evaluation for NotebookLM. 
GitHub. https://github.com/FlorindoPalladino/paravia-notebooklm-dataset
```

## Licenza

Questo dataset è rilasciato sotto licenza MIT. Vedi il file [LICENSE](LICENSE) per i dettagli.

## Contatti

**Florindo Palladino**  
florindo.palladino@unimol.it

---

**Keywords**: NotebookLM, information retrieval, cataloghi storici, Paravia, storia dell'educazione, intelligenza artificiale generativa
