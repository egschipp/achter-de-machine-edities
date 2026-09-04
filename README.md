# Achter de Machine — weekedities

Publieke databron voor [Achter de Machine](https://ainews.schippers-online.nl).

- `current.json`: de actuele voorpagina-editie.
- `archive/YYYY-MM-DD.json`: onveranderlijke weekarchieven.
- `schema.json`: het verplichte gegevensmodel.

Een cloudtaak onderzoekt iedere vrijdag om 06.00 uur in `Europe/Amsterdam` het AI-nieuws, valideert de editie en werkt daarna het archief en `current.json` bij. De site leest `current.json` rechtstreeks uit dit repository. Daardoor zijn voor de wekelijkse vernieuwing geen nieuwe site-deployment en geen ingeschakelde laptop nodig.
Gestructureerde weekedities voor Achter de Machine
