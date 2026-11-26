# Grm Observatory

## О проекте / токене

The first-ever PoW jetton on TON Blockchain.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-26):

- <https://tonapi.io/v2/jettons/EQC47093oX5Xhb0xuk2lCr2RhS8rj-vul61u4W2UH5ORmG_O>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
The snapshot contains independently fetched GRM data; incomplete sections are explicitly reported.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions backup schedule is configured at :17/:47 UTC; Cloudflare dispatch can invoke update.yml.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Проверенные источники GRM

Проверка: 2026-11-26. Сайт https://gramcoin.org/ перенаправляет на https://grmcoin.org/. Контракт на сайте совпадает с project.json и TonAPI; decimals = 9. Канал https://t.me/grmcoinorg связан с официального сайта и ссылается обратно. Проект описывает GRM как первый PoW-jetton TON; это самоописание, а не независимое заключение.

Логотип загружен из metadata image https://gramcoin.org/img/icon.png и встроен в HTML. Флаг: №162 из предоставленного пользователем TONecoFlags-catalog-standalone.html (элемент flag-162).

Репозиторий до создания сайта содержал только шаблон (f487a8ffe7a35aca4420312d3a866ab7dc1cb6ea), workflow обновления отсутствовал. Создан update.yml с workflow_dispatch и резервным GitHub schedule :17/:47 UTC. Существующий внешний Cloudflare runner не изменялся; его действующая конфигурация не предоставлена и плановый запуск требует отдельного наблюдения.

Первичные источники: https://grmcoin.org/ ; https://t.me/grmcoinorg ; https://tonapi.io/v2/jettons/EQC47093oX5Xhb0xuk2lCr2RhS8rj-vul61u4W2UH5ORmG_O
