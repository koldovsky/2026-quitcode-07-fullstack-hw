# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: yuriivynar
- Ваше репо: https://github.com/yuriivynar/property-workflows
- SHA: 6bc21cd712f5e2e5bfef55cd8f0e546261afd419
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows-eta.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/yuriivynar/property-workflows/pull/12
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/yuriivynar/property-workflows/pull/21 (знімок 2026-10-27; переклад уточнень — PR «Специфікація» https://github.com/yuriivynar/property-workflows/pull/22, зміна `clarify-template-versions`: MODIFIED AC-EDITOR-02, 03; ADDED AC-EDITOR-10–29, AC-DSYS-05–08)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/25, https://github.com/solomchaak/property-workflows-spec/issues/26, https://github.com/solomchaak/property-workflows-spec/issues/27, https://github.com/solomchaak/property-workflows-spec/issues/28, https://github.com/solomchaak/property-workflows-spec/issues/29, https://github.com/solomchaak/property-workflows-spec/issues/30, https://github.com/solomchaak/property-workflows-spec/issues/31, https://github.com/solomchaak/property-workflows-spec/issues/34 (пропозиція), коментар https://github.com/solomchaak/property-workflows-spec/issues/26#issuecomment-6403641883
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/yuriivynar/property-workflows/pull/14
- Дизайн-система — PR (B): https://github.com/yuriivynar/property-workflows/pull/13
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/DESIGN.md · джерело: AI-чат: Claude Code (Claude Opus 5.5), промпт — в описі PR #13
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/yuriivynar/property-workflows/actions/runs/40580369726
- Знімки «до/після» (B): https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-before-login-light.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-before-login-dark.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-after-login-light.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-after-login-dark.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-before-runs-light.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-before-runs-dark.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-after-runs-light.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-after-runs-dark.png (усі 5 сторінок × 2 теми — `docs/img/ws7-before-*`, `docs/img/ws7-after-*`, таблицею в описі PR https://github.com/yuriivynar/property-workflows/pull/13)
- Зміна `impl-<зріз2>` (C): https://github.com/yuriivynar/property-workflows/tree/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/openspec/changes/archive/2026-10-26-impl-template-versions (PR «Специфікація» https://github.com/yuriivynar/property-workflows/pull/15)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/yuriivynar/property-workflows/pull/17, https://github.com/yuriivynar/property-workflows/pull/18, https://github.com/yuriivynar/property-workflows/pull/19, https://github.com/yuriivynar/property-workflows/pull/20, https://github.com/yuriivynar/property-workflows/pull/23 (правила після уточнень PM 27.10), https://github.com/yuriivynar/property-workflows/pull/24 (AC-DSYS-08)
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/yuriivynar/property-workflows/actions/runs/40333425879 (AC-EDITOR-08), https://github.com/yuriivynar/property-workflows/actions/runs/40333927209 (AC-EDITOR-02)
- ADR (D): https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/decisions/0003-authz-in-actions-and-database.md, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/decisions/0002-template-versions-jsonb-snapshot.md
- Архітектурне правило, крім `check:design` (D): власне правило — job «Перевірка входу й ролі в кожній дії» (`scripts/check-actions-claims.mjs`); також «Секретний ключ лише на сервері» (`check:boundary` з `materials/`); доказ — вивід скрипта на навмисних порушеннях в описі PR https://github.com/yuriivynar/property-workflows/pull/19 (розділ «Доказ, що правило ловить порушення»); job зелений на main: https://github.com/yuriivynar/property-workflows/actions/runs/40580369726
- Акаунти для PM (E): pm-manager@example.test (manager), pm-admin@example.test (admin)
- Скріни за ролями (E): https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-admin-templates.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-admin-editor.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-admin-editor-error.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-admin-versions.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-manager-template.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-manager-editor-denied.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-manager-runs-empty.png, https://github.com/yuriivynar/property-workflows/blob/6bc21cd712f5e2e5bfef55cd8f0e546261afd419/docs/img/ws7-role-visitor-run-link.png (також в описі PR https://github.com/yuriivynar/property-workflows/pull/19)
- AC зрізу 2 (E; 37 AC, з них «реалізовано» — 27): AC-DSYS-01 (реалізовано), AC-DSYS-02 (реалізовано), AC-DSYS-03 (реалізовано), AC-DSYS-04 (реалізовано), AC-EDITOR-01 (реалізовано), AC-EDITOR-02 (реалізовано), AC-EDITOR-03 (реалізовано), AC-EDITOR-04 (реалізовано), AC-EDITOR-05 (реалізовано), AC-EDITOR-06 (реалізовано), AC-EDITOR-07 (реалізовано), AC-EDITOR-08 (реалізовано), AC-EDITOR-09 (реалізовано), AC-EDITOR-10 (реалізовано), AC-EDITOR-11 (реалізовано), AC-EDITOR-12 (реалізовано), AC-EDITOR-13 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#23; реалізація — наступним PR «Реалізація»)), AC-EDITOR-14 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#23; реалізація — наступним PR «Реалізація»)), AC-EDITOR-15 (реалізовано), AC-EDITOR-16 (реалізовано), AC-EDITOR-17 (реалізовано), AC-EDITOR-18 (реалізовано), AC-EDITOR-19 (реалізовано), AC-EDITOR-20 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#28; реалізація — наступним PR «Реалізація»)), AC-EDITOR-21 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#29; реалізація — наступним PR «Реалізація»)), AC-EDITOR-22 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#29; реалізація — наступним PR «Реалізація»)), AC-EDITOR-23 (реалізовано), AC-EDITOR-24 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#30; реалізація — наступним PR «Реалізація»)), AC-EDITOR-25 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#31; реалізація — наступним PR «Реалізація»)), AC-EDITOR-26 (реалізовано), AC-EDITOR-27 (реалізовано), AC-EDITOR-28 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#36; реалізація — наступним PR «Реалізація»)), AC-EDITOR-29 (реалізовано), AC-DSYS-05 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#34; реалізація — наступним PR «Реалізація»)), AC-DSYS-06 (відкладено (новий AC з відповіді PM 27.10 у день здачі WS7 — solomchaak/property-workflows-spec#34; реалізація — наступним PR «Реалізація»)), AC-DSYS-07 (реалізовано), AC-DSYS-08 (реалізовано)
- Відхилення від PM (E): не надходило. Відкладено 10 нових AC з відповідей PM 27.10, тобто з дня здачі: AC-EDITOR-13, 14, 20, 21, 22, 24, 25, 28, AC-DSYS-05, 06. Для кожного в `docs/conformance.md` вказано причину й issue PM; реалізація — наступними PR «Реалізація».

## Бонус

Цикл візуальної перевірки в браузері агента (Playwright MCP) — PR https://github.com/yuriivynar/property-workflows/pull/13, розділ «Бонус»: агент зняв 5 сторінок у світлій і темній темі, порівняв з `DESIGN.md` і знайшов відхилення, якого не ловить `check:design`: посилання мали колір акценту (`text-primary` — формально токен), тож головна дія губилась серед них, а «Вигляд і тон» відводить акцент лише головній дії. Виправлено (`TextLink` — колір тексту), правило записано в `DESIGN.md`, знімки до/після — у PR. Висновок: скрипт перевіряє синтаксис (токен чи ні), а браузерна перевірка — зміст (той токен чи ні); дизайн-системі потрібні обидві.

## Після строку (для інформації; оцінюється SHA вище)

Завдання WS7 (блоки A–E і бонус) виконано в строк, на SHA `6bc21cd712f5e2e5bfef55cd8f0e546261afd419` (27.10). На цьому
SHA з 37 AC зрізу 2 «реалізовано» 27, а 10 нових AC з відповідей PM від 27.10 — «відкладено» з причиною. PM відповів на питання
до вимог лише 27.10 о 12:09–12:11 за Києвом, тобто в день строку
(issues #21–#38 у https://github.com/solomchaak/property-workflows-spec). Відповіді змінили 2 AC і додали
24 нові (AC-EDITOR-10–29, AC-DSYS-05–08).

Того ж дня зроблено:
- синхронізацію вимог — https://github.com/yuriivynar/property-workflows/pull/21;
- переклад у специфікацію — https://github.com/yuriivynar/property-workflows/pull/22;
- реалізацію 14 нових AC — https://github.com/yuriivynar/property-workflows/pull/23,
  https://github.com/yuriivynar/property-workflows/pull/24.

Решту 10 AC на SHA здачі позначено «відкладено» з причиною й посиланням на issue PM.

28.10, вже після строку, ці 10 AC реалізовано за процесом:
- план `impl-clarify-template-versions` — https://github.com/yuriivynar/property-workflows/pull/25;
- задачі — https://github.com/yuriivynar/property-workflows/pull/26, https://github.com/yuriivynar/property-workflows/pull/27, https://github.com/yuriivynar/property-workflows/pull/28, https://github.com/yuriivynar/property-workflows/pull/29, https://github.com/yuriivynar/property-workflows/pull/30, https://github.com/yuriivynar/property-workflows/pull/31;
- знімки вибору теми й archive плану — https://github.com/yuriivynar/property-workflows/pull/33.

Окремо:
- патч безпеки Next.js 16.4.0 → 16.4.3 (critical RCE; ADR 0005) — https://github.com/yuriivynar/property-workflows/pull/32;
- `zod` 4.6.7 (ADR 0006) — https://github.com/yuriivynar/property-workflows/pull/34.

Стан `main` після цього — `5c4ef5bda555b91a524d2e2918bb687892262b5b`: 67 з 67 AC «реалізовано»
(https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/docs/conformance.md).
