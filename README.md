# HDS oppstartsmanual
Dette er oppstartsmanualen for [Helsedatasenteret ved St. Olavs hospital](https://www.stolav.no/avdelinger/sentral-stab/forskningsavdelingen/helsedatasenter/).
Manualen er skrevet i Markdown og bruker [Zensical static site generator](https://github.com/zensical/zensical) for å generere nettstedet. Nettstedet bygges og publiseres via GitHub Actions.

## Hvordan redigere
Endringer gjøres i Markdown-filer. Zensical tilbyr mange ekstra funksjoner, men for å holde dokumentasjonen portabel har vi vært forsiktige med hvilke tillegg som brukes. Se også den gode [Zensical-dokumentasjonen](https://zensical.org/docs/get-started).

### Full funksjonalitet
For full funksjonalitet kan du sette opp Zensical via `pip` eller `uv` i Python-miljøet ditt.
Med `uv` kan dette gjøres slik:

```cmd
uv sync
source .venv/bin/activate
```

### For raske endringer
Endringer kan gjøres direktet på GitHub eller ved å koble repositoriet til [vscode.dev](https://vscode.dev/).

### Legge til nye filer
For å legge til en ny side eller seksjon må du også legge den inn i `nav` i konfigurasjonsfilen [zensical.toml](zensical.toml).