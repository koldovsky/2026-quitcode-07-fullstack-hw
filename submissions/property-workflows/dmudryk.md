# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: dmudryk
- Ваше репо: https://github.com/dmudryk/property-workflows
- SHA: d8e40c03fb64706af085c49ddd53e95181362b76
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows-bravo16.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: `Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27`
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/dmudryk/property-workflows/pull/11
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/dmudryk/property-workflows/pull/21 (знімок 2026-10-27: 24 нові AC, 2 змінені); зміна специфікації з ADDED / MODIFIED — https://github.com/dmudryk/property-workflows/pull/22 (`update-ws7-clarifications`)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/37, https://github.com/solomchaak/property-workflows-spec/issues/38
- PR «Специфікація» з `add-<зріз2>` (A): `add-ws7-templates` — https://github.com/dmudryk/property-workflows/pull/14 (посилання на питання — https://github.com/dmudryk/property-workflows/pull/19)
- Дизайн-система — PR (B): https://github.com/dmudryk/property-workflows/pull/13 (тема «Nettinx», назва й лого, бічна панель, власні списки, стани обробки — https://github.com/dmudryk/property-workflows/pull/18; вибір теми System / Light / Dark — https://github.com/dmudryk/property-workflows/pull/25)
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/DESIGN.md · джерело: AI-чат: Claude Code (промпт — в описі PR #13), основа вигляду — тема tweakcn https://tweakcn.com/themes/cmqbb3gdw000104l29dvzaqja, адаптована під «Вигляд і тон» PM і контраст
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/dmudryk/property-workflows/actions/runs/40525932418
- Знімки «до/після» (B): https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-before-login-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-before-runs-dark.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-after-login-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-after-runs-dark.png
- Зміна `impl-<зріз2>` (C): `impl-ws7-templates` — https://github.com/dmudryk/property-workflows/tree/d8e40c03fb64706af085c49ddd53e95181362b76/openspec/changes/archive/2026-10-27-impl-ws7-templates (план — PR https://github.com/dmudryk/property-workflows/pull/15, archive — PR https://github.com/dmudryk/property-workflows/pull/20); план уточнень — https://github.com/dmudryk/property-workflows/tree/d8e40c03fb64706af085c49ddd53e95181362b76/openspec/changes/archive/2026-10-27-impl-ws7-clarifications (PR https://github.com/dmudryk/property-workflows/pull/23, archive — PR https://github.com/dmudryk/property-workflows/pull/25)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/dmudryk/property-workflows/pull/16, https://github.com/dmudryk/property-workflows/pull/17, https://github.com/dmudryk/property-workflows/pull/24, https://github.com/dmudryk/property-workflows/pull/25
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/dmudryk/property-workflows/actions/runs/40377246018 (AC-EDITOR-08, AC-DSYS-02), https://github.com/dmudryk/property-workflows/actions/runs/40378069654 (AC-EDITOR-07); таблиця для AC-EDITOR-11, 12, 23, 26, 29 — в описі PR https://github.com/dmudryk/property-workflows/pull/24
- ADR (D): https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/decisions/0002-template-versions-as-snapshots.md (також https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/decisions/0003-theme-choice-cookie.md)
- Архітектурне правило, крім `check:design` (D): job «Запис лише через функції бази» (`scripts/check-writes-via-rpc.mjs`) у `.github/workflows/architecture.yml`; червоний прогін на коміті з навмисним порушенням — https://github.com/dmudryk/property-workflows/actions/runs/40380522899 (PR https://github.com/dmudryk/property-workflows/pull/17, потім revert)
- Акаунти для PM (E): pm-admin@example.test (admin), pm-manager@example.test (manager)
- Скріни за ролями (E): https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-admin-templates-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-admin-versions-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-admin-editor-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-manager-templates-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-manager-template-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-manager-editor-denied-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-manager-versions-denied-light.png, https://github.com/dmudryk/property-workflows/blob/d8e40c03fb64706af085c49ddd53e95181362b76/docs/img/ws7-role-anon-run-to-login-light.png (прод, PR https://github.com/dmudryk/property-workflows/pull/20); стани уточнень PM — `docs/img/ws7-clar-*` (PR https://github.com/dmudryk/property-workflows/pull/25)
- AC зрізу 2 (E): AC-DSYS-01 (реалізовано), AC-DSYS-02 (реалізовано), AC-DSYS-03 (реалізовано), AC-DSYS-04 (реалізовано), AC-DSYS-05 (реалізовано), AC-DSYS-06 (реалізовано), AC-DSYS-07 (реалізовано), AC-DSYS-08 (реалізовано), AC-EDITOR-01 (реалізовано), AC-EDITOR-02 (реалізовано), AC-EDITOR-03 (реалізовано), AC-EDITOR-04 (реалізовано), AC-EDITOR-05 (реалізовано), AC-EDITOR-06 (реалізовано), AC-EDITOR-07 (реалізовано), AC-EDITOR-08 (реалізовано), AC-EDITOR-09 (реалізовано), AC-EDITOR-10 (реалізовано), AC-EDITOR-11 (реалізовано), AC-EDITOR-12 (реалізовано), AC-EDITOR-13 (реалізовано), AC-EDITOR-14 (реалізовано), AC-EDITOR-15 (реалізовано), AC-EDITOR-16 (реалізовано), AC-EDITOR-17 (реалізовано), AC-EDITOR-18 (реалізовано), AC-EDITOR-19 (реалізовано), AC-EDITOR-20 (реалізовано), AC-EDITOR-21 (реалізовано), AC-EDITOR-22 (реалізовано), AC-EDITOR-23 (реалізовано), AC-EDITOR-24 (реалізовано), AC-EDITOR-25 (реалізовано), AC-EDITOR-26 (реалізовано), AC-EDITOR-27 (реалізовано), AC-EDITOR-28 (реалізовано), AC-EDITOR-29 (реалізовано)
- Відхилення від PM (E): не надходило

## Бонус

—
