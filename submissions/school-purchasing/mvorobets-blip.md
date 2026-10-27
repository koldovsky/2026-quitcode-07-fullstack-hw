# Здача WS7

## Дані

- Роль: dev
- Команда: school-purchasing
- GitHub-логін: mvorobets-blip
- Ваше репо: https://github.com/mvorobets-blip/school-purchasing
- SHA: 4e4db1c47ac11dd04703e8d04fbc9c292a75b066
- Репо вимог PM: https://github.com/ValiaBihun/2026-quitcode-dream-team
- Прод-URL: https://therapy-scheduling-ten.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/ValiaBihun/2026-quitcode-dream-team · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/mvorobets-blip/school-purchasing/pull/13 — знімок 2026-10-23 (вимоги PM 47, 48, 49); далі https://github.com/mvorobets-blip/school-purchasing/pull/15 — знімок 2026-10-25
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/mvorobets-blip/school-purchasing/pull/26 — знімок 2026-10-27 (AC-APR-08 … 10 і підпис «Author» після відповіді PM на https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/62); /requirements-sync 2026-10-27
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/54, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/55, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/56, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/61 — усі чотири власні issues; PM відповів на всі (журнал — https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/spec-reading.md)
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/mvorobets-blip/school-purchasing/pull/16 — `add-purchase-approval`; уточнення після відповіді PM — https://github.com/mvorobets-blip/school-purchasing/pull/27 (`clarify-purchase-approval`, ADDED AC-APR-08 … 10)
- Дизайн-система — PR (B): https://github.com/mvorobets-blip/school-purchasing/pull/14
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/DESIGN.md · джерело: «AI-чат: Claude Code» (модель Claude Opus 5.5, шаблон `materials/DESIGN.template.md`; промпт і таблиця контрасту — в описі PR #14)
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/mvorobets-blip/school-purchasing/actions/runs/40585723596
- Знімки «до/після» (B): https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-before-login-light.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-after-login-light.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-before-login-dark.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-after-login-dark.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-before-departments-light.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-after-departments-light.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-before-departments-dark.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-after-departments-dark.png
- Зміна `impl-<зріз2>` (C): https://github.com/mvorobets-blip/school-purchasing/tree/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/openspec/changes/archive/2026-10-26-impl-purchase-approval (план — PR https://github.com/mvorobets-blip/school-purchasing/pull/17, уточнення — https://github.com/mvorobets-blip/school-purchasing/pull/19; 22/22 задач відмічено); доповнення для AC-APR-08 … 10 і виправлень за відгуком — https://github.com/mvorobets-blip/school-purchasing/tree/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/openspec/changes/archive/2026-10-27-impl-purchase-approval-2 (PR https://github.com/mvorobets-blip/school-purchasing/pull/33)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/mvorobets-blip/school-purchasing/pull/20, https://github.com/mvorobets-blip/school-purchasing/pull/21, https://github.com/mvorobets-blip/school-purchasing/pull/22, https://github.com/mvorobets-blip/school-purchasing/pull/23, https://github.com/mvorobets-blip/school-purchasing/pull/24, https://github.com/mvorobets-blip/school-purchasing/pull/28; за відгуком — https://github.com/mvorobets-blip/school-purchasing/pull/31, https://github.com/mvorobets-blip/school-purchasing/pull/32, https://github.com/mvorobets-blip/school-purchasing/pull/34, https://github.com/mvorobets-blip/school-purchasing/pull/36; за рев'ю PM (тести AC-LANG на видимому тексті, повідомлення про задовгий текст, прод у README) — https://github.com/mvorobets-blip/school-purchasing/pull/38
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/mvorobets-blip/school-purchasing/actions/runs/40315629281 (AC-FRM-02 — прибрано перевірку FORBIDDEN відділу в `submit_purchase`, червоний `app`, PR #20), https://github.com/mvorobets-blip/school-purchasing/actions/runs/40349297804 (AC-APR-05, AC-FRM-13 — прибрано перевірку власної заявки в `decide_purchase`, червоний `app`, PR #22)
- ADR (D): https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/decisions/0002-privileged-writes-via-db-functions.md, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/decisions/0003-server-auth-via-get-claims.md
- Архітектурне правило, крім `check:design` (D): job «Авторизація лише через getClaims()» у `.github/workflows/architecture.yml` (`scripts/check-no-get-session.mjs`); червоний прогін на коміті `mutation:` з `getSession()` — https://github.com/mvorobets-blip/school-purchasing/actions/runs/40314050147, потім revert (PR https://github.com/mvorobets-blip/school-purchasing/pull/18)
- Акаунти для PM (E): pm-requester@example.test (requester), pm-approver@example.test (approver — схвалювач відділу «Primary School»; роль у профілі — approver), pm-admin@example.test (admin). Паролі — PM особистим повідомленням
- Скріни за ролями (E): https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-requester-home.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-requester-approvals-forbidden.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-approver-home.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-approver-settings-forbidden.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-admin-home.png, https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/img/ws7-role-admin-approvals-forbidden.png
- AC зрізу 2 (E): AC-FRM-01 … AC-FRM-15 (реалізовано), AC-APR-01 … AC-APR-10 (реалізовано), AC-LANG-01 … AC-LANG-06 і AC-LANG-08 (реалізовано) — https://github.com/mvorobets-blip/school-purchasing/blob/4e4db1c47ac11dd04703e8d04fbc9c292a75b066/docs/conformance.md
- Відхилення від PM (E): не надходило — issues «Відхилення від вимог» у репо немає (дві власні розбіжності з вимогами PM знайдено й виправлено до merge: https://github.com/mvorobets-blip/school-purchasing/pull/23, https://github.com/mvorobets-blip/school-purchasing/pull/24 — див. «Бонус»)

## Бонус

Цикл візуальної перевірки в браузері агента — PR https://github.com/mvorobets-blip/school-purchasing/pull/24 (розділ «Бонус»: промпт, 12 знімків «до/після» у світлій і темній темі, що знайдено й виправлено, що пропущено).

Агент у Browser pane Claude Desktop знімав прод («до») і гілку на localhost проти бази проду («після») під акаунтами
PM і звіряв із DESIGN.md. Цикл знайшов те, чого не бачать ні тести, ні `check:design`: форма мовчки не надсилалась
(`required` у Select без повідомлення), після помилки губились введені рядки, а «Fill in all line fields» стояло під
формою поза екраном, `outline`-кнопка втратила межу (`buttonVariants` без `cn()`), відмова в доступі була сірим рядком,
а не нейтральною карткою з DESIGN.md. Незалежна перевірка вимог (агент без мого контексту) знайшла дві мої розбіжності з
вимогами PM ще до merge: формат дати «26 Oct» замість формату першого зрізу (вимога #49 формати не змінює) і власне повідомлення про межі
чисел (межі — наступний зріз). Пропущено: рамка фокусу логотипа в бічній панелі — типова браузерна, а не `ring-ring`;
мобільну ширину перевірено очима без знімків.

Висновок: агентний браузер корисний як другий рецензент вигляду, але знайдене треба звіряти з вимогами PM — частина
«покращень» (формат дати, власний текст повідомлення) сама виявилась відхиленням від вимог; окрема незалежна перевірка
вимог після дизайн-правок окупилась.
