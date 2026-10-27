# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: OleksandrMartynov
- Ваше репо: https://github.com/OleksandrMartynov/property-workflows
- SHA: 4c8ad478e533a6b6f45c721fde0ef6ad5d755550
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows-rho.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/OleksandrMartynov/property-workflows/pull/20 — знімок від 25.10
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/OleksandrMartynov/property-workflows/pull/30 — знімок від 27.10 (нові AC-EDITOR-10…29, AC-DSYS-05…08, змінені AC-EDITOR-02, 03)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/23, https://github.com/solomchaak/property-workflows-spec/issues/24 — обидва власні, PM відповів 27.10 і додав AC-EDITOR-13, 14, 15
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/OleksandrMartynov/property-workflows/pull/21 (уточнення після відповідей PM — https://github.com/OleksandrMartynov/property-workflows/pull/32; журнал питань — https://github.com/OleksandrMartynov/property-workflows/pull/38)
- Дизайн-система — PR (B): https://github.com/OleksandrMartynov/property-workflows/pull/18
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/DESIGN.md · джерело: артефакт Claude Design https://claude.ai/artifact/BamW4LNTPFw37TFKkzJU9Z
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/OleksandrMartynov/property-workflows/actions/runs/40530932897
- Знімки «до/після» (B): https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-before-login-light.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-after-login-light.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-before-login-dark.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-after-login-dark.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-before-run-light.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-after-run-light.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-before-run-dark.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-after-run-dark.png (усі в `docs/img/` на SHA)
- Зміна `impl-<зріз2>` (C): https://github.com/OleksandrMartynov/property-workflows/tree/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/openspec/changes/archive/2026-10-25-impl-template-editor (уточнення — https://github.com/OleksandrMartynov/property-workflows/tree/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/openspec/changes/archive/2026-10-27-impl-clarify-template-editor)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/OleksandrMartynov/property-workflows/pull/24, https://github.com/OleksandrMartynov/property-workflows/pull/25, https://github.com/OleksandrMartynov/property-workflows/pull/34, https://github.com/OleksandrMartynov/property-workflows/pull/35, https://github.com/OleksandrMartynov/property-workflows/pull/36, https://github.com/OleksandrMartynov/property-workflows/pull/37, https://github.com/OleksandrMartynov/property-workflows/pull/40 (тест пастки «update own row + колонка role» у `profiles`)
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/OleksandrMartynov/property-workflows/actions/runs/40208375030 (AC-EDITOR-08), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40208601080 (AC-EDITOR-07), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40208792411 (AC-EDITOR-02), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40209615124 (AC-EDITOR-08, дія), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40513381977 (AC-EDITOR-23), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40514147592 (AC-EDITOR-20), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40521931783 (AC-DSYS-08), https://github.com/OleksandrMartynov/property-workflows/actions/runs/40554699277 (`grant update (role)` на `profiles` — тест пастки ролі, PR #40)
- ADR (D): https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/decisions/0006-template-drafts-and-immutable-versions.md (ще 0004 — дизайн-система)
- Архітектурне правило, крім `check:design` (D): job «Кожна Server Action перевіряє вхід» (`scripts/check-actions-auth.mjs`) і «Секретний ключ лише на сервері» в `architecture.yml`; доказ, що ловить порушення, — червоний прогін на коміті `violation: Server Action resetDraft() без перевірки входу` (PR #25): https://github.com/OleksandrMartynov/property-workflows/actions/runs/40209826755
- Акаунти для PM (E): pm-manager@example.test (manager), pm-admin@example.test (admin)
- Скріни за ролями (E): https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-visitor-login.png (відвідувач — вхід), https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-manager-templates.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-manager-template.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-manager-denied.png (менеджер — головна зрізу й відмова «Not enough rights»), https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-admin-templates.png, https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/docs/img/ws7-role-admin-editor.png (адміністратор); у описі PR https://github.com/OleksandrMartynov/property-workflows/pull/37
- AC зрізу 2 (E): за `docs/conformance.md` на SHA усі 67 AC (зокрема AC-EDITOR-01…29 і AC-DSYS-01…08) — реалізовано; відкладених немає
- Відхилення від PM (E): не надходило (issues «Відхилення від вимог» у репо немає)

## Бонус

Цикл візуальної перевірки в браузері агента (Browser pane у Claude Desktop): PR https://github.com/OleksandrMartynov/property-workflows/pull/18 (промпт, знімки до/після, що агент знайшов і виправив, що пропустив), далі PR https://github.com/OleksandrMartynov/property-workflows/pull/27 і https://github.com/OleksandrMartynov/property-workflows/pull/31 (галерея й редактор шаблонів, модальні вікна: знімки світлої й темної теми, виправлення обрізаного тексту, відступів і поведінки на телефоні). Агент пройшов `/login`, `/`, `/runs`, сторінку запуску й шаблони в обох темах, склав список відхилень, виправив їх і переперевірив; не перевірено hover і pressed (знімки статичні), про що сказано в описі PR #18.
