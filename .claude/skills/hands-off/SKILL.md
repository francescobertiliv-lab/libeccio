---
name: hands-off
description: Comprime l'intera conversazione in un documento di passaggio di consegne pulito, che si incolla o si allega in una chat nuova per riprendere il lavoro senza perdere il contesto — decisioni prese, vincoli, stato attuale, prossimo passo. Usare SEMPRE quando l'utente dice che la chat è troppo lunga o rallenta, chiede di "riassumere tutto per ricominciare", "fammi un handoff", "passa il contesto a una chat nuova", "dammi un documento per ripartire", quando sta per esaurire il contesto disponibile, o quando deve passare il lavoro a un collega. Usare anche quando un progetto lungo si interrompe e l'utente vuole poterlo riprendere fra qualche giorno.
---

# hands-off

Il risultato è un documento che, letto a freddo da chi non ha visto questa conversazione, permette di riprendere il lavoro esattamente da dove si è fermato.

Il criterio di riuscita è uno solo: **una chat nuova, con solo questo documento, deve poter fare il passo successivo senza fare domande all'utente.** Ogni scelta su cosa tenere e cosa buttare si decide contro questo criterio.

## Cosa tenere e cosa buttare

**Tieni:**
- Le decisioni prese e, dove non è ovvio, il motivo. Il motivo evita che la chat nuova riapra una questione già chiusa.
- I vincoli: scadenze, formati, lunghezze, destinatari, cose che l'utente ha escluso.
- Le preferenze emerse: correzioni che l'utente ha fatto, tono richiesto, cose che ha bocciato e perché.
- Lo stato reale di ogni pezzo di lavoro: fatto, in bozza, non iniziato.
- Nomi esatti: file, percorsi, linee di bilancio, riferimenti di procedura, persone. Gli identificativi vanno riportati letteralmente, non parafrasati — sono la cosa che la chat nuova non può ricostruire.
- I vicoli ciechi. "Abbiamo provato X, non funziona perché Y" vale quanto una decisione presa: evita di rifare il giro.

**Butta:**
- Il ping pong conversazionale, le riformulazioni, i "perfetto, procedi".
- Le versioni intermedie superate. Solo l'ultima, salvo che il confronto sia esso stesso l'oggetto del lavoro.
- Le spiegazioni generali che la chat nuova sa già da sé.
- Le esplorazioni abbandonate senza conclusione utile.

## Struttura del documento

```markdown
# Handoff — [oggetto del lavoro]
[data]

## In una riga
[Cosa si sta facendo e per quando.]

## Stato
[Dove siamo. Cosa è concluso, cosa è aperto.]

## Decisioni prese
- [Decisione] — [motivo, se non è ovvio]

## Vincoli
- [Scadenze, formati, destinatari, esclusioni]

## Materiali
- [File, documenti, link, con nome e percorso esatti]

## Preferenze dell'utente
- [Tono, formato, cose bocciate e perché]

## Già provato senza esito
- [Cosa, e perché non ha funzionato]

## Prossimo passo
[La prima cosa da fare, formulata in modo che sia eseguibile.]

## Domande aperte
[Cose che aspettano una risposta dall'utente o da terzi.]
```

Salta le sezioni vuote. Un handoff con sei intestazioni e un contenuto è peggio di quattro paragrafi densi.

## Come scriverlo

**Scrivi per chi non c'era.** Niente "come dicevamo", "il documento di prima", "quella versione". Ogni riferimento deve reggersi da solo.

**Sii denso, non breve.** L'obiettivo non è la brevità: è che non ci sia una riga inutile. Un handoff di due pagine che contiene tutto è un successo; uno di dieci righe che costringe l'utente a rispiegare metà del contesto è un fallimento.

**Non riassumere il contenuto del lavoro se il lavoro esiste già come file.** Se c'è una bozza salvata, indica dov'è e riporta solo cosa manca. Duplicarla nel documento la fa divergere dall'originale.

**Formula il prossimo passo come un'istruzione.** Non "resta da rivedere la sezione 3" ma "rivedere la sezione 3 del file X: mancano i dati di esecuzione 2025, l'utente li fornirà".

## Consegna

Crea il documento come file `.md` e presentalo, così l'utente può allegarlo alla chat nuova invece di copiarlo a mano. Se l'utente preferisce il testo da copiare, dallo in chat in un blocco.

Se il lavoro sta in un Progetto, segnala che il documento può essere caricato nella knowledge del Progetto, dove resta disponibile a tutte le chat successive senza doverlo riallegare ogni volta.

## Prima di consegnare

Rileggi il documento fingendo di non aver visto la conversazione e chiediti: con solo questo, saprei fare il prossimo passo?

Se la risposta è no, il pezzo che manca è quasi sempre uno di questi tre: un identificativo esatto dato per scontato, un vincolo emerso a metà conversazione e mai più ripetuto, o il motivo per cui una strada è stata scartata.
