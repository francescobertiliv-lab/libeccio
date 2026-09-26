# Case sulla linea Luxembourg

Mappa giornaliera delle case in vendita vicino alle stazioni con treno per Bruxelles-Luxembourg.

- Mappa pubblicata: https://claude.ai/artifact/VkknvC4FZtsZNjwj9sH2Wq (dati nel suo database: `meta`, `geo`, `listings`, `days`, `stars`).
- `page.src.html`: sorgente della pagina. `scripts/build_page.py` produce `index.html` inserendo il CSS di Leaflet.
- `scripts/trains.py`: tempi e frequenze verso Bruxelles-Luxembourg dal GTFS ufficiale NMBS/SNCB.
- La procedura giornaliera è in `.claude/agents/monitor-case.md`.
