# CLAUDE.md

Repo di **guide personali per Baldur's Gate 3** (PS5, UI italiana, Patch 8). Contiene solo Markdown: niente build, niente test. Gli script Python di supporto stanno in `.claude/` (o `.Codex/`), entrambe **gitignorate**.

```
run-1-buona/            prima partita, eroica — completata
run-2-pulsione-oscura/  partita corrente
riferimenti/            build e oggetti, validi per entrambe le run
archivio/               alternative superate, tenute solo come confronto
trophy-images/          screenshot dei trofei
```

## Stato della partita (aggiornato al 21 settembre 2026)

- **Partita corrente:** seconda run, origine **Pulsione Oscura**, protagonista **Bardo delle Lame** (*College of Swords*; nei file più vecchi "Bardo delle Spade"), elfo dei boschi, modalità **Stratega**, combattimento in mischia.
- **Criterio confermato dal giocatore:** Pulsione Oscura **opportunista per massimizzare armi, equipaggiamento e bonus**. Salvare PNG e conservare mercanti serve alle ricompense, non è un vincolo morale. Ai bivi si confronta il guadagno immediato con gli oggetti e i bonus futuri che si perdono. **Non consigliare la redenzione per motivi etici** (valeva per la prima run).
- **Piano di classe:** Bardo 6 → Paladino 2 → Bardo 10. È l'obiettivo finale, **non** il livello già raggiunto. Il Collegio delle Lame dà competenza in **armature medie e scimitarre**, non negli scudi: quelli arrivano con Paladino 2, le armature pesanti mai.
- **Marchio dell'Assoluta:** scelta del giocatore, **non riceverlo**. Non proporlo come recupero.
- **Progressi dichiarati:** gnoll uccisi · Zhentarim Rugan e Olly salvati (carico, Zarys e Brem da confermare) · gnomo al mulino liberato · notte della Pulsione avvenuta, tiefling uccisa e mantello ricevuto (**se era Alfira, la Veste Potente non è più ottenibile**) · Kagha uccisa, idolo rubato, incarico di Mol completato · **livello 6, arrivato a Grymforge** con le missioni precedenti chiuse.
- **Punto del percorso:** **PO-15, Forgia Adamantina**. Deciso: forgiare **Armatura di Scaglie Adamantina** (protagonista) e **Corazza di Piastre Adamantina** (Lae'zel); niente armi, niente scudo. Grym si affronta al livello 6 senza il maglio, per il trofeo *Un Gramo Destino*. Poi **PO-16, Passo e Creche**, ultima tappa dell'Atto 1: ⚠️ non prendere l'ascensore di Grymforge verso le Terre Maledette prima di averla fatta.
- **Prima run (buona/eroica): completata.** I suoi file restano il riferimento per mappe, tattiche e tappe 1-50.

## Gerarchia dei file (chi vince in caso di conflitto)

1. **[percorso_pulsione_oscura_bardo.md](run-2-pulsione-oscura/percorso_pulsione_oscura_bardo.md)** — guida operativa della partita corrente, 50 tappe **PO-00 … PO-50**, stato della run, vincoli reali, priorità del Bardo. **Per ordine delle missioni e prerequisiti prevale su tutto il resto.**
2. **[checklist_missioni_pulsione_oscura.md](run-2-pulsione-oscura/checklist_missioni_pulsione_oscura.md)** — catalogo di **147 voci** di missione, ognuna con link alla pagina bg3.wiki, tappe PO di riferimento e stato (`Da verificare` / `In corso` / `Fatto`). "Da verificare" significa *non dichiarato dal giocatore*, non *incompiuto*.
3. **Roadmap dell'origine** — [Atto 1](run-2-pulsione-oscura/roadmap_atto1_pulsione_oscura.md), [Atto 2](run-2-pulsione-oscura/roadmap_atto2_pulsione_oscura.md), [Atto 3](run-2-pulsione-oscura/roadmap_atto3_pulsione_oscura.md): approfondimenti e varianti, non l'itinerario. L'ordine 01-21 con **assedio del Boschetto** è un'**alternativa storica** (il ramo attivo risolve i tre capi nel campo). Ogni file si apre con un box `> **Aggiornamento operativo — 17 settembre 2026**` che rimanda alle tappe PO: mantenerlo coerente.
4. **Build del protagonista:** [bardadino_opportunista_livello_per_livello.md](run-2-pulsione-oscura/bardadino_opportunista_livello_per_livello.md) (piano attivo) e [oggetti_exploit_opportunista.md](run-2-pulsione-oscura/oggetti_exploit_opportunista.md) (exploit per atto/tappa/destinatario).
5. **Riferimenti trasversali:** [build_completa_livello_1-12.md](riferimenti/build_completa_livello_1-12.md) (tutti gli 11 personaggi) e [oggetti_e_build_definitive.md](riferimenti/oggetti_e_build_definitive.md) (catalogo oggetti per slot e setup finali).
6. **Prima run:** [Atto 1](run-1-buona/roadmap_atto1_run_buona.md), [Atto 2](run-1-buona/roadmap_atto2_run_buona.md), [Atto 3](run-1-buona/roadmap_atto3_run_buona.md) — tappe 1-50, mappe, tattiche, atlante delle location. Le guide dell'origine vi rimandano invece di duplicarle.
7. **`archivio/`** — piani superati del protagonista (confronto Guerriero, Lockadin). Conservati solo come confronto: **non sommare i loro numeri, premi e talenti alla build attiva**.
8. **[README.md](README.md)** — indice di tutto: va aggiornato ogni volta che si aggiunge un file o cambia l'impostazione della run.

## Convenzioni

- **Lingua: italiano.** Nomi di classi, sottoclassi, incantesimi, talenti, oggetti, luoghi, PNG e trofei nella **localizzazione italiana ufficiale di BG3**, mai quella del cartaceo D&D 5e, con l'inglese tra parentesi come ancora di ricerca. Se la dicitura a schermo non è confermata: ⚠️ e invito a verificare su PS5 (vince sempre lo schermo).
- **Simboli comuni a tutte le roadmap:** 🏆 trofeo · ⚠️ missabile · ⏱️ a tempo · 🚩 punto di non ritorno · 📈 livelli/build · 🎒 equipaggiamento · 🩸 evento della Pulsione.
- **Struttura ricorrente:** tabelle `Tappa | Azione | Premio | Vincolo/rinuncia`, sezione **Scelte opportuniste** per atto, link a bg3.wiki accanto a ogni affermazione verificata.
- **Onestà sullo stato della run:** distinguere sempre *dichiarato dal giocatore* da *da verificare*. Non si leggono i salvataggi: le caselle non certificano nulla. Non presentare come acquisite ricompense incompatibili fra loro, né trasformare il catalogo in obbligo di completismo.
- **Ordine ≠ obbligo:** la numerazione PO è una proposta costruita sui vincoli documentati; i vincoli veri stanno nell'ultima colonna.
- **Verificare prima di scrivere**, non fidarsi della memoria, per nomi, regole, coordinate e condizioni dei trofei. Fonti: bg3.wiki (primaria), absolutegamer.it, videogiochitalia.it, uagna.it (lista trofei PSN IT), nextgentech.it, game8.co.
- **File grandi** (fino a ~270 KB): modificarli chirurgicamente, mai riscrivendoli.
- **Spostando file**, controllare i link relativi fra guide e quelli del README.

## Strumenti locali (`.claude/`, non versionati)

- `audit_quests.py` — scarica le pagine bg3.wiki in `research_2026_09_17/sources.json`.
- `build_catalog.py` — genera il catalogo missioni mappando gli slug wiki sulle tappe PO.
- `update_guides.py` — applica patch testuali ai file `.md` con `assert` sui marcatori (fallisce se il testo atteso non c'è).
- `read_audit.py` — lettura rapida dei dati scaricati.

Per modifiche ripetitive su più guide conviene estendere `update_guides.py` invece di editare a mano ogni file.

## Git

Messaggi di commit in italiano, all'imperativo (es. "Aggiorna piano Bardadino, roadmap opportuniste e oggetti exploit"). Committare solo su richiesta esplicita.
