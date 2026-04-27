# Commercialista AI

Strumento di calcolo fiscale per regime forfettario (ATECO 86.90.29 – Osteopatia).

## 📊 Caratteristiche

- **Dati verificati RPF 2022-2025**: tutti i dati dalle dichiarazioni ufficiali
- **Calcoli corretti**: Base imponibile = Ricavi × 78% − INPS effettivamente versata
- **Tab Mensile**: traccia ricavi mese per mese (2026+), calcola acconti automatici
- **Tab Acconti**: prospettiva cassa dei pagamenti (saldi + acconti)
- **Tab Calcolo**: imposta e INPS versate per ogni anno
- **Consulente AI**: chiedi analisi, confronti, simulazioni (aggiungi la tua API key Anthropic)
- **Export/Import**: backup e ripristino dati in JSON

## 🚀 Come usare

1. **Apri l'app**: [https://nicholas-rossetti.github.io/commercialista-ai/](https://nicholas-rossetti.github.io/commercialista-ai/)
2. **Aggiungi API key** (opzionale):
   - Campo in alto a destra
   - Usa la tua chiave Anthropic (`sk-ant-...`)
   - Si salva automaticamente nel browser
3. **Seleziona un anno** nella sidebar sinistra
4. **Compila i dati** nel tab Dati (ricavi, acconti, note)
5. **Usa i tab** per visualizzare calcoli, scadenze, confronti

## 📋 Dati precompilati

| Anno | Ricavi | Acconti I | Acconti N | Fonte |
|---|---|---|---|---|
| 2022 | €4.795 | €0 | €0 | RPF 2023 |
| 2023 | €17.177 | €672 | €785 | RPF 2024 |
| 2024 | €11.174 | €1.000 | €1.000 | RPF 2025 |
| 2025 | €12.031 | €554 | €1.722 | F24 verificati |
| 2026+ | Vuoto | — | — | Da compilare mese per mese |

## 🔧 Tecnologia

- HTML5 + JavaScript vanilla (no dipendenze)
- localStorage per salvataggio dati
- Fetch API per integrazione Anthropic (opzionale)
- Responsive design

## 💾 Dati e Privacy

- **Dati locali**: tutto rimane nel tuo browser (localStorage)
- **API key**: solo se aggiungi tu manualmente, non salvata da noi
- **Backup**: esporta JSON dal menu

## 📝 Modifiche e Sviluppo

Per modificare il codice:

1. **Online** (GitHub web): clicca sul file → edit button (✏️) → modifica → commit
2. **Localmente**: clona il repo, modifica, push
3. **Collaborare**: apri una issue o una pull request

Dopo ogni modifica, GitHub Pages aggiorna automaticamente il sito in pochi secondi.

## 🤝 Supporto

Per bug, migliorie o domande, apri una [GitHub Issue](https://github.com/nicholas-rossetti/commercialista-ai/issues).

---

**Autore**: Nicholas Rossetti  
**Ultimo aggiornamento**: 27 aprile 2026  
**Licenza**: Privato (per uso personale)
