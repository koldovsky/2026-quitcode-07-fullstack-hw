# Здача WS7

## Дані

- Роль: dev
- Команда: leave-portal
- GitHub-логін: lukian-tomochko
- Ваше репо: https://github.com/lukian-tomochko/leave-portal
- SHA: 1cbedd66043fa57858cff6adc0772fca8705399a
- Репо вимог PM: https://github.com/mkozlovskyi-ops/course-staff-management-spec
- Прод-URL: https://leave-portal-blush.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/mkozlovskyi-ops/course-staff-management-spec · джерело: docs · знімок 2026-10-24
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/lukian-tomochko/leave-portal/pull/15
- PR «Оновлення вимог» після уточнень PM (A): /requirements-sync 2026-10-27: Вимоги актуальні
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/16, https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/17, https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/18
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/lukian-tomochko/leave-portal/pull/3 (`add-leave-management`; PM не публікував окремого зрізу 2 для WS7, тому за зріз 2 взято вимогу 02 «рішення менеджера», план — https://github.com/lukian-tomochko/leave-portal/pull/17)
- Дизайн-система — PR (B): https://github.com/lukian-tomochko/leave-portal/pull/14
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/DESIGN.md · джерело: AI-чат: Claude Code (Claude Sonnet 5.5)
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/lukian-tomochko/leave-portal/actions/runs/40457548975
- Знімки «до/після» (B): https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-before-login-light.png, https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-after-login-light.png, https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-before-leave-dark.png, https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-after-leave-dark.png
- Зміна `impl-<зріз2>` (C): https://github.com/lukian-tomochko/leave-portal/tree/1cbedd66043fa57858cff6adc0772fca8705399a/openspec/changes/archive/2026-10-27-impl-leave-decision (після злиття https://github.com/lukian-tomochko/leave-portal/pull/25)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/lukian-tomochko/leave-portal/pull/18, https://github.com/lukian-tomochko/leave-portal/pull/19, https://github.com/lukian-tomochko/leave-portal/pull/20; після ревʼю WS6 ще https://github.com/lukian-tomochko/leave-portal/pull/26 (insert лише через функцію бази, складений ключ), https://github.com/lukian-tomochko/leave-portal/pull/29 (імʼя змінює лише адміністратор), https://github.com/lukian-tomochko/leave-portal/pull/28 (AC-LEAVE-10 у формі), https://github.com/lukian-tomochko/leave-portal/pull/30 (перейменування міграції для порядку db-deploy)
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/lukian-tomochko/leave-portal/actions/runs/40163893130 (AC-DECIDE-08), https://github.com/lukian-tomochko/leave-portal/actions/runs/40164087425 (AC-DECIDE-18)
- ADR (D): https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/decisions/0004-decision-functions.md · другий ADR: https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/decisions/0006-leave-request-via-private-function.md (подання заявки лише функцією бази; тести `tests/db/leave-request.test.ts`)
- Архітектурне правило, крім `check:design` (D): job «Секретний ключ лише на сервері» (`check:boundary`) у `architecture.yml`; доказ, що ловить порушення, — вивід «5 порушень» в описі https://github.com/lukian-tomochko/leave-portal/pull/16
- Акаунти для PM (E): teacher1@example.test (employee), manager1@example.test і manager2@example.test (manager), admin@example.test (admin); адреси є в `supabase/demo-users.json`, входом на проді перевірено. Паролі — PM у чаті
- Скріни за ролями (E): PR https://github.com/lukian-tomochko/leave-portal/pull/27; файли в `docs/img/`: employee — https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-employee-leave.png (головна) і https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-employee-denied-decisions.png (відмова: `/decisions`); manager — https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-manager-decisions.png (головна) і https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-manager-denied-record.png (відмова: чужий запис, manager2); admin — https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-admin-decisions.png (головна) і https://github.com/lukian-tomochko/leave-portal/blob/1cbedd66043fa57858cff6adc0772fca8705399a/docs/img/ws7-role-visitor-login.png (відмова: відвідувач без входу; для адміністратора окремої заборони в зрізі немає, AC-DECIDE-10)
- AC зрізу 2 (E): як у `docs/conformance.md` на SHA, усі «реалізовано»: AC-DECIDE-01 … AC-DECIDE-24 і AC-BALANCE-01 … AC-BALANCE-22 (46 AC зрізу 2 і вимоги 03; разом у матриці 67 AC, усі «реалізовано», `npm run ac:coverage` — OK)
- Відхилення від PM (E): не надходило станом на 2026-10-27 (issues «Відхилення від вимог» у репо немає)

## Бонус

—
