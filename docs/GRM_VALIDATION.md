# GRM acceptance — 2026-11-26

Factory TON-Observatory-Template 1.3.0, source commit 6578013. Previous main f487a8ffe7a35aca4420312d3a866ab7dc1cb6ea remains recoverable.

Verified exact master raw/friendly identity and decimals=9 against TonAPI. Three direct TON pools verified from successful matching JettonSwap events; primary chosen by indexed liquidity.

Factory: 49 Python + 15 JavaScript + 6 scheduler tests passed. Generated project: 17 Python + 15 JavaScript tests passed; JS syntax, bundle integrity and identity validation passed.

Browser checks on standalone HTML: 360/390/768/1280 iframe widths (content widths 345/375/753/1265 after scrollbar), scrollWidth equals clientWidth at every width; RU/EN toggle; holders 10→20→10; all internal anchors resolve; saved data retained after remote snapshot failure before publication. No external scripts, CSS, images or fonts.

Official logo fetched from metadata image URL and visually matched to supplied example. Section flag extracted from owner catalogue flag-162. OG/+888/4N/burn rules and DEX flags come from shared factory. No token-specific DEV/NFT/staking labels inherited.

Publication target is main in Freebielife/GRM. No TON Storage upload or DNS change is claimed. External Cloudflare live configuration is unavailable; existing runner was not changed. update.yml provides workflow_dispatch and a backup schedule. Runtime run status must be read from GitHub separately.
