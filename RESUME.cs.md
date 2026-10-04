---
schema_version: 11
type: notmine-sample
category_override: JavaScript_Projects
file_count: 11
file_extensions: noext:5, json:2, md:2, js:1, yml:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 83
total_lines: 11
metrics_lm: 2026-10-01 16:41:06
move_to_legacy_percent: 85
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

Ukázková Node.js aplikace s webovým serverem Express (port 8080), Dockerfilem v `app/Dockerfile` a Azure Pipelines definicí `azure-pipelines.yml`. Slouží jako vzor pro sestavení kontejneru a nasazení v pipeline. Jde o oficiální dokumentační ukázku od Microsoftu bez vlastního vývoje.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [MicrosoftDocs/pipelines-javascript-docker](https://github.com/MicrosoftDocs/pipelines-javascript-docker)

- Zdroj určen podle: remote `sunamo/pipelines-javascript-docker` je podle GitHub API fork tohoto repa, hash `app/server.js` a `app/Dockerfile` je shodný s originálem, README je původní od Microsoftu..

Článek, ze kterého by kód byl opsaný, se nenašel (zjišťovalo se v souborech repa a podle názvu).

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **85 %** — oficiální dokumentační ukázka Microsoftu, znovu dostupná na GitHubu

- Malé repo (11 souborů) s Express appkou, Dockerfilem a azure-pipelines.yml.
- Poslední obsahový commit je z 2025-03-31 a jde o kopii MicrosoftDocs/pipelines-javascript-docker.
- Nic vlastního zde není.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
