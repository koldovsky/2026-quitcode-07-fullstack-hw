# Здача WS7

## Дані

- Роль: dev
- Команда: school-purchasing
- GitHub-логін: YarynaPankivv
- Ваше репо: https://github.com/YarynaPankivv/school-purchasing
- SHA: d9bf88270d028d1d25f9467d05c034bbefa84d6a
- Репо вимог PM: https://github.com/ValiaBihun/2026-quitcode-dream-team
- Прод-URL: https://school-purchasing.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/ValiaBihun/2026-quitcode-dream-team · джерело: issues · знімок 2026-10-26
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/YarynaPankivv/school-purchasing/pull/23 (знімок 2026-10-23)
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/YarynaPankivv/school-purchasing/pull/30 (знімок 2026-10-26; перший — https://github.com/YarynaPankivv/school-purchasing/pull/25)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/50, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/52, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/53
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/YarynaPankivv/school-purchasing/pull/24 (`add-frm-apr`; уточнення — https://github.com/YarynaPankivv/school-purchasing/pull/26 і https://github.com/YarynaPankivv/school-purchasing/pull/31)
- Дизайн-система — PR (B): https://github.com/YarynaPankivv/school-purchasing/pull/27
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/DESIGN.md · джерело: AI-чат — Claude Code зі скілом Impeccable
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/YarynaPankivv/school-purchasing/actions/runs/40379310988
- Знімки «до/після» (B): https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-before-login-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-login-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-before-requests-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-requests-light.png (темні — ті самі імена з `-dark`)
- Зміна `impl-<зріз2>` (C): https://github.com/YarynaPankivv/school-purchasing/tree/d9bf88270d028d1d25f9467d05c034bbefa84d6a/openspec/changes/archive/2026-10-26-impl-frm-apr (заархівовано; план — https://github.com/YarynaPankivv/school-purchasing/pull/32)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/YarynaPankivv/school-purchasing/pull/33, https://github.com/YarynaPankivv/school-purchasing/pull/29, https://github.com/YarynaPankivv/school-purchasing/pull/20
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/YarynaPankivv/school-purchasing/actions/runs/40374897628 (AC-APR-05, AC-FRM-13), https://github.com/YarynaPankivv/school-purchasing/actions/runs/40375539133 (AC-FRM-02); таблиця «AC → що прибрали → який тест упав» — в описі https://github.com/YarynaPankivv/school-purchasing/pull/33
- ADR (D): https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/decisions/0003-permissions-in-database.md
- Архітектурне правило, крім `check:design` (D): job «Server Actions: перевірка користувача» в `architecture.yml` (`check:actions`); доказ — червоний прогін https://github.com/YarynaPankivv/school-purchasing/actions/runs/40376008062 у https://github.com/YarynaPankivv/school-purchasing/pull/34
- Акаунти для PM (E): pm-requester@example.test (requester), pm-approver@example.test (approver), pm-admin@example.test (admin). Зашифрований архів https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/accounts.zip
- Скріни за ролями (E): https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-member1-requests-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-member1-forbidden-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-approver-requests-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-approver-forbidden-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-requests-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-users-light.png; акаунти для PM (pm-*): https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-requester-home-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-requester-forbidden-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-approver-home-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-approver-forbidden-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-admin-home-light.png, https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/docs/img/design-after-pm-admin-requests-light.png
- AC зрізу 2 (E): AC-FRM-01…15 і AC-APR-01…10 — усі «реалізовано» в `docs/conformance.md`; AC-LANG-01…06, 08 — «реалізовано»
- Відхилення від PM (E): не надходило

## Бонус

Цикл візуальної перевірки в браузері агента (Browser pane в Claude Desktop, скіл Impeccable): `/impeccable critique` по всіх сторінках застосунку (збережені звіти — вхід 26/40 і головна 28/40), виправлення в PR дизайн-системи, далі прохід усіма сторінками під ролями requester, approver, admin і два виправлення за ним. Промпт, знімки до/після, що знайдено й виправлено й що пропущено — в описі https://github.com/YarynaPankivv/school-purchasing/pull/41. Статичний critique не побачив відмову за чужою заявкою (404 замість «Not enough permissions») і порядок шарів меню на телефоні, їх знайшов лише прохід у браузері; рядок «ask them to check your account» на вході лишився без адресата допомоги.
