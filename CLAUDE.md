# kosmos

Front de visualisation du projet test : carte 2D des pensées de Marc Aurèle (projection des vecteurs de `memento`) et dashboard d'éval par run. La spec est dans `mr-orchestrator/docs/brief.md`.

## Règles

- `kosmos` ne calcule pas d'embeddings : il lit les exports JSON produits par `memento`.
- Le choix du framework front fait partie du premier ticket kosmos : ne pas l'ajouter sans plan validé.
- Pendant un run, travailler sur une branche issue de `run/NNN` et ouvrir la PR vers `run/NNN`, jamais vers `main`.

## Commandes

- `uv sync` : installer
- `uv run pytest` : tests

## Définition de fini

- Tests ajoutés pour tout code ajouté, `uv run pytest` vert.
- Une capture d'écran dans la PR pour tout changement visible.
