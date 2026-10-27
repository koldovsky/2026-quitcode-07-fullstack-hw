# Здача WS7

## Дані

- Роль: dev
- Команда: therapy-scheduling
- GitHub-логін: pavmys
- Ваше репо: https://github.com/pavmys/therapy-scheduling
- SHA: 013c743fc5cdad463bc016bf70e094e7ec376f81
- Репо вимог PM: https://github.com/Sofiia-pm/therapy-scheduling-spec
- Прод-URL: https://therapy-scheduling-three.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/Sofiia-pm/therapy-scheduling-spec · джерело: issues · знімок 2026-10-26
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/pavmys/therapy-scheduling/pull/17 (знімок 2026-10-24)
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/pavmys/therapy-scheduling/pull/26 (знімок 2026-10-26)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/30, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/31, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/25#issuecomment-6424238090
- PR «Специфікація» з `add-client-cards` (A): https://github.com/pavmys/therapy-scheduling/pull/19
- Дизайн-система — PR (B): https://github.com/pavmys/therapy-scheduling/pull/18
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/DESIGN.md · джерело: артефакт Claude Design https://claude.ai/artifact/JBQckDn5cGek5sVnZMLh79?sk=D6nXTktI17M3luAs_M9g7A
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/pavmys/therapy-scheduling/actions/runs/40452637073
- Знімки «до/після» (B): https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-before-holds-dark.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-after-holds-dark.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-before-slots-dark.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-after-slots-dark.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-after-slots-light.png
- Зміна `impl-client-cards` (C): https://github.com/pavmys/therapy-scheduling/tree/013c743fc5cdad463bc016bf70e094e7ec376f81/openspec/changes/archive/2026-10-26-impl-client-cards
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/pavmys/therapy-scheduling/pull/21, https://github.com/pavmys/therapy-scheduling/pull/22, https://github.com/pavmys/therapy-scheduling/pull/24, https://github.com/pavmys/therapy-scheduling/pull/28, https://github.com/pavmys/therapy-scheduling/pull/29, https://github.com/pavmys/therapy-scheduling/pull/30, https://github.com/pavmys/therapy-scheduling/pull/31
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/pavmys/therapy-scheduling/actions/runs/40388557936 (AC-CARD-11), https://github.com/pavmys/therapy-scheduling/actions/runs/40402163226 (AC-CARD-05, AC-CARD-08)
- ADR (D): https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/decisions/0004-db-access-tests-pglite.md, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/decisions/0005-own-clients-rls.md
- Архітектурне правило, крім `check:design` (D): job «Секретний ключ лише на сервері» (`scripts/check-server-boundary.mjs`) у `.github/workflows/architecture.yml`; червоний прогін на навмисному порушенні (`process.env.SUPABASE_SECRET_KEY` у коді сторінки) — https://github.com/pavmys/therapy-scheduling/actions/runs/40449994017, PR з виводом і revert — https://github.com/pavmys/therapy-scheduling/pull/30
- Акаунти для PM (E): pm-scheduler@example.test (scheduler), pm-therapist@example.test (therapist), pm-admin@example.test (admin). Паролі — PM у чаті.
- Скріни за ролями (E): https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-scheduler-clients.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-scheduler-card-child.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-my-clients.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-foreign-card-denied.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-new-card-denied.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-schedule.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-admin-clients.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-admin-search-guardian.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-anon-card-link-login.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-holds-denied.png, https://github.com/pavmys/therapy-scheduling/blob/013c743fc5cdad463bc016bf70e094e7ec376f81/docs/img/ws7-role-therapist-slots-denied.png
- AC зрізу 2 (E): AC-CARD-01 (реалізовано), AC-CARD-02 (реалізовано), AC-CARD-03 (реалізовано), AC-CARD-04 (реалізовано), AC-CARD-05 (реалізовано), AC-CARD-06 (реалізовано), AC-CARD-07 (реалізовано), AC-CARD-08 (реалізовано), AC-CARD-09 (реалізовано), AC-CARD-10 (реалізовано), AC-CARD-11 (реалізовано), AC-CARD-12 (реалізовано), AC-CARD-13 (реалізовано), AC-CARD-14 (реалізовано), AC-CARD-15 (реалізовано), AC-CARD-16 (реалізовано); уточнення зрізу 1 після відповідей PM — AC-HOLD-42, AC-HOLD-43, AC-HOLD-44 (реалізовано)
- Відхилення від PM (E): не надходило

## Бонус

Цикл візуальної перевірки в браузері агента, два проходи. Промпт і знімки «до/після» першого проходу — коментар https://github.com/pavmys/therapy-scheduling/pull/25#issuecomment-6433985520; другий прохід — PR https://github.com/pavmys/therapy-scheduling/pull/31 (промпт, три знімки, виправлення). Людина входить під акаунтом PM, агент (Claude Code) відкриває сторінки й знімає, людина виходить; паролів агент не бачить.

- Прохід 1 (прод, PR #25): на `/clients/new` під `pm-therapist` — лише відмова без шапки, терапевт не міг піти зі сторінки чи вийти. Додано шапку терапевта, закріплено тестом AC-CARD-06.
- Прохід 2 (локально, PR #31): та сама сторінка показувала відмову червоною помилкою, а `/slots` і `/holds` — нейтральним `Alert` з `Lock`; DESIGN.md вимагає для відмови `Alert` з `Lock`, червоний — лише для помилок. Сторінку переведено на спільний `staffOnlyPage`, тест AC-CARD-06 тепер перевіряє й вигляд.

Висновок: тести перевіряли текст відмови, але не те, чи може людина піти зі сторінки і чи відмова виглядає як на інших сторінках. Знімок під реальною роллю ловить прогалини, яких AC не описують, а друге знайдене відхилення — від власної дизайн-системи, яку жоден AC не цитує.
