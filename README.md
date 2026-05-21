# Claude Plugin — Immobilier France

Plugin Claude Code pour analyser le marché immobilier français via les APIs publiques data.gouv.fr.

## Ce que fait ce plugin

- Analyse des prix immobiliers par commune, quartier ou adresse
- Recherche de transactions DVF (Demandes de Valeurs Foncières)
- Estimation de biens (appartements, maisons)
- Comparaison de marchés locaux
- Données cadastrales et zonage PLU

## APIs utilisées

- **DVF** — Transactions réelles DGFiP (api.dvf.etalab.gouv.fr)
- **BAN** — Géocodage d'adresses (api-adresse.data.gouv.fr)
- **API Géo** — Communes et découpage administratif (geo.api.gouv.fr)
- **GPU** — Zonage PLU (apicarto.ign.fr)

## Installation

```
/plugin marketplace add votre-username/claude-plugin-immobilier
/plugin install immobilier-france@votre-username
```

## Exemples d'utilisation

- "Quel est le prix au m² des appartements à Bordeaux Chartrons ?"
- "Estime mon T3 de 68m² à Nantes centre"
- "Compare les prix entre Lyon 6e et Lyon 3e sur 2 ans"
- "Analyse le marché des maisons dans un rayon de 20km autour de Tours"
