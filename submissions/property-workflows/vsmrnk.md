# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: vsmrnk
- Ваше репо: https://github.com/vsmrnk/property-workflows
- SHA: fe0a990ea2d384f204a22c3349a89ae8721ab899
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/vsmrnk/property-workflows/pull/15 — PR у репо розробника, гілка `sync/2026-10-25`, знімок 2026-10-25, злито 25.10
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/vsmrnk/property-workflows/pull/25 — знімок 2026-10-27; зміна специфікації з MODIFIED / ADDED — https://github.com/vsmrnk/property-workflows/pull/26
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/21, https://github.com/solomchaak/property-workflows-spec/issues/22
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/vsmrnk/property-workflows/pull/16
- Дизайн-система — PR (B): https://github.com/vsmrnk/property-workflows/pull/17
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/DESIGN.md · джерело: AI-чат: Claude Code (Claude Opus 5.5)
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/vsmrnk/property-workflows/actions/runs/40563040622
- Знімки «до/після» (B): https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-before-login-light.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-after-login-light.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-before-login-dark.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-after-login-dark.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-before-home-light.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-after-home-light.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-before-home-dark.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-after-home-dark.png
- Зміна `impl-<зріз2>` (C): https://github.com/vsmrnk/property-workflows/tree/fe0a990ea2d384f204a22c3349a89ae8721ab899/openspec/changes/archive/2026-10-26-impl-template-versions, https://github.com/vsmrnk/property-workflows/tree/fe0a990ea2d384f204a22c3349a89ae8721ab899/openspec/changes/archive/2026-10-27-impl-template-versions-2
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/vsmrnk/property-workflows/pull/20, https://github.com/vsmrnk/property-workflows/pull/22, https://github.com/vsmrnk/property-workflows/pull/24, https://github.com/vsmrnk/property-workflows/pull/28, https://github.com/vsmrnk/property-workflows/pull/29
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/vsmrnk/property-workflows/actions/runs/40204628136 (AC-EDITOR-07), https://github.com/vsmrnk/property-workflows/actions/runs/40236560241 (AC-EDITOR-08) — таблиця в https://github.com/vsmrnk/property-workflows/pull/20
- ADR (D): https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/decisions/0002-auth-check-in-every-action.md
- Архітектурне правило, крім `check:design` (D): job «Кожна дія перевіряє вхід» (`actions-claims`) в `architecture.yml`; червоний прогін на справжньому порушенні: https://github.com/vsmrnk/property-workflows/actions/runs/40236889995, PR https://github.com/vsmrnk/property-workflows/pull/21
- Акаунти для PM (E): pm-admin@example.test (admin), pm-manager@example.test (manager)
- Скріни за ролями (E): https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-admin-templates.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-admin-editor.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-admin-versions.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-manager-templates.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-manager-editor-denied.png, https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/docs/img/ws7-role-anon-editor-login.png
- AC зрізу 2 (E): AC-DSYS-01 (реалізовано), AC-DSYS-02 (реалізовано), AC-DSYS-03 (реалізовано), AC-DSYS-04 (реалізовано), AC-DSYS-05 (реалізовано), AC-DSYS-06 (реалізовано), AC-DSYS-07 (реалізовано), AC-DSYS-08 (реалізовано), AC-EDITOR-01 (реалізовано), AC-EDITOR-02 (реалізовано), AC-EDITOR-03 (реалізовано), AC-EDITOR-04 (реалізовано), AC-EDITOR-05 (реалізовано), AC-EDITOR-06 (реалізовано), AC-EDITOR-07 (реалізовано), AC-EDITOR-08 (реалізовано), AC-EDITOR-09 (реалізовано), AC-EDITOR-10 (реалізовано), AC-EDITOR-11 (реалізовано), AC-EDITOR-12 (реалізовано), AC-EDITOR-13 (реалізовано), AC-EDITOR-14 (реалізовано), AC-EDITOR-15 (реалізовано), AC-EDITOR-16 (реалізовано), AC-EDITOR-17 (реалізовано), AC-EDITOR-18 (реалізовано), AC-EDITOR-19 (реалізовано), AC-EDITOR-20 (реалізовано), AC-EDITOR-21 (реалізовано), AC-EDITOR-22 (реалізовано), AC-EDITOR-23 (реалізовано), AC-EDITOR-24 (реалізовано), AC-EDITOR-25 (реалізовано), AC-EDITOR-26 (реалізовано), AC-EDITOR-27 (реалізовано), AC-EDITOR-28 (реалізовано), AC-EDITOR-29 (реалізовано)
- Відхилення від PM (E): не надходило

## Бонус

Цикл візуальної перевірки в браузері агента — https://github.com/vsmrnk/property-workflows/pull/17 (розділ «Бонус»). Claude Code знімав сторінки headless-Chromium (Playwright) під роллю admin у світлій і темній темі, на 1280 і 390 px, і звіряв з `DESIGN.md`. Знайшов і виправив: межу полів 1.2:1 → токен `input` 3.2–3.6:1, невирівняні колонки таблиць задач, обрізану панель підтвердження «Mark as done», вихід колонки прогресу за картку на 390 px. Пропустив індиго поза основною дією (навігація, прогрес, логотип) — це знайшла звірка з «Вигляд і тон» PM. Висновок: знімки ловлять геометрію й контраст, але правила тону й акценту треба звіряти з текстом вимог окремо.
