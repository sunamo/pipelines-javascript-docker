---
schema_version: 11
type: notmine-sample
category_override: none
file_count: 12
file_extensions: noext:6, json:3, md:2, js:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 80
total_lines: 11
metrics_lm: 2026-10-01 16:40:46
move_to_legacy_percent: 60
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: https://github.com/MicrosoftDocs/pipelines-javascript-docker
origin_status: found
origin_checked: 2026-10-01
article_source_url: not found
article_status: none
article_checked: 2026-10-03
last_build_ok: not run
last_build_date: not run
last_tests_run_date: not run
covered_lines: 0
---

## Description

Oficiální ukázka Microsoftu: Node.js (Express) webový server na portu 8080 zabalený do Docker image pro Azure Pipelines / Kubernetes.
Obsahuje `app/server.js`, `app/package.json`, `app/Dockerfile` (node:12.18.1) a README s návodem.
Jde o stažený vzorový projekt bez vlastních úprav.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [MicrosoftDocs/pipelines-javascript-docker](https://github.com/MicrosoftDocs/pipelines-javascript-docker)

- Zdroj určen podle: shoda git blob hashů 5 souborů (`app/server.js`, `app/Dockerfile`, `app/package.json`, `app/package-lock.json`, `app/.dockerignore`) s `MicrosoftDocs/pipelines-javascript-docker`; shodný popis a licence Microsoftu (`LICENSE`, `LICENSE-CODE`).

Článek, ze kterého by kód byl opsaný, se nenašel (zjišťovalo se v souborech repa a podle názvu).

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **60 %** — kopie oficiální ukázky Microsoftu, dostupná na GitHubu

- Soubory shodné s `MicrosoftDocs/pipelines-javascript-docker`, nic vlastního.
- Ukázku lze kdykoli znovu stáhnout z upstreamu.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
