# javacard-ci-demo

Projet JavaCard avec pipeline d'intégration continue (GitHub Actions).

TD réalisé par : DIACK Amadou (madptitprince)

## Workflows

- `javacard.yml` : compilation et tests de l'applet à chaque push/pull request.
- `sast-semgrep.yml` : analyse statique de sécurité (SAST) du code.
- `javacard-release.yml` : publication automatique d'une release GitHub avec le `.cap`, déclenchée par un tag `v*`.
