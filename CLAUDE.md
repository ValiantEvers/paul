# paul — instruks for Claude Code-økter

Personlig side for Paul Evers. Live på **evers.no/paul**. Én enkelt `index.html`, ingen
rammeverk, ingen bygg-steg. Les `README.md`.

## Viktigst å forstå
- **Siden redigeres av en ikke-teknisk person (Paul) direkte i GitHub-web-UI-et.** Hold den
  triviell: alt redigerbart er merket med `ENDRE …` i `index.html`, og hjelpenotater står i
  HTML-kommentarer (`<!-- … -->`). **Bevar disse markørene** ved enhver endring.
- **ALDRI legg til en `CNAME`-fil her.** `evers.no/paul` fungerer fordi dette er en
  GitHub Pages *project page* som arver `www.evers.no` fra hovedsiten; en egen CNAME ødelegger
  adressen.

## Konvensjoner (gjelder alle endringer)
- Norsk i innhold. Datoer ISO 8601. Aldri Co-Authored-By-trailer.
- `git pull --rebase origin main` før push.
- Ingen rammeverk, ingen bundler, ingen bygg-steg — alt i `index.html`.

## Bygg / deploy
- Push til `main` → auto-publisert av GitHub Pages (project page under `evers.no`-siten).
  Ingen workflow, ingen build.
