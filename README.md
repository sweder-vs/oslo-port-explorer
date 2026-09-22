# Port of Oslo Explorer

Interactive 3D dashboard built for a Port Economics assignment (Economic Characteristics &
Economic Dynamism of the Port of Oslo). A stylized low-poly diorama sits on top of Oslo Havn's
own official port-area map, with clickable landmarks at Vippetangen, Bjørvika, Sørenga,
Filipstad, Sydhavna and Aker Brygge, plus a KPI dashboard panel around it.

Open `index.html` directly in a browser, or serve the folder with any static file server
(e.g. `python3 -m http.server`) — it needs to be served over HTTP, not opened as a bare
`file://` path, for the map/photo textures to load.

## Data & content sources

- Base map: [Oslo Havn](https://www.oslohavn.no) official port area map (PDF, 2019),
  `oslo-map.jpg`.
- Landmark facts: Oslo Havn's own site, Store norske leksikon ("Oslo havn"), Wikipedia
  (Vippetangen, Bjørvika, Sørenga, Fjord City), and ferry operator sites (Color Line,
  Go Nordic Cruiseline, Stena Line, Norled/Nesoddbåten).
- KPI panel numbers are **sample/illustrative only** — see the in-app "Source" links on
  each stat for where to pull the real figures (Oslo Havn annual report, SSB, ENOVA,
  Kystverket, Norske Havner) before submitting.

## Photo credits (Wikimedia Commons, all CC-licensed)

| Site | Photographer | License |
|---|---|---|
| Bjørvika (Opera House) | Jorge Láscar | CC BY 2.0 |
| Sørenga | Annikdance | CC BY-SA 4.0 |
| Sydhavna (container terminal) | Niels Johannes | CC BY-SA 4.0 |
| Aker Brygge | W. Bulach | CC BY-SA 4.0 |
| Vippetangen | Tore Sætre | CC BY-SA 4.0 |
| Filipstad | Ssu | CC BY-SA 4.0 |

Built with [Claude Code](https://claude.com/claude-code) and Three.js.
