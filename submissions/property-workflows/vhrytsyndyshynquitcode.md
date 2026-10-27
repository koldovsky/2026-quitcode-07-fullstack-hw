# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: vhrytsyndyshynquitcode
- Ваше репо: https://github.com/vhrytsyndyshynquitcode/property-workflows
- SHA: fcc006d395c0b7887b348fac3498ff5340f52956
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows-one.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-27
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/12
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/26 (знімок 2026-10-27: 24 нові AC, 2 змінені) → PR «Специфікація» з ADDED / MODIFIED https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/27; /requirements-sync 2026-10-26: Вимоги актуальні (до уточнень)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/32, https://github.com/solomchaak/property-workflows-spec/issues/33 — обидва власні; PM відповів змінами вимог 27.10 (AC-EDITOR-26, AC-EDITOR-27)
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/14
- Дизайн-система — PR (B): https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/13
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/DESIGN.md · джерело: AI-чат: Claude Code (Claude Opus 5.5)
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/vhrytsyndyshynquitcode/property-workflows/actions/runs/40496957075
- Знімки «до/після» (B): https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-before-runs-light.png, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-after-runs-light.png (також `login` і `home`, світла й темна теми: `docs/img/ws7-before-*`, `docs/img/ws7-after-*`)
- Зміна `impl-<зріз2>` (C): https://github.com/vhrytsyndyshynquitcode/property-workflows/tree/fcc006d395c0b7887b348fac3498ff5340f52956/openspec/changes/archive/2026-10-26-impl-template-versions
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/16, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/17, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/18, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/19, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/21, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/29, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/30 — рев'ю CodeRabbit до merge з відповіддю на кожен коментар мають https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/19, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/21, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/29, https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/30; на #16–#18 CodeRabbit не встиг до merge, їхній код перевірено й виправлено в #19
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/vhrytsyndyshynquitcode/property-workflows/actions/runs/40295115497 (AC-EDITOR-08: `save_template_version` без перевірки ролі), https://github.com/vhrytsyndyshynquitcode/property-workflows/actions/runs/40295378603 (AC-EDITOR-02: політика робочої копії `using (true)`); зелений після revert — https://github.com/vhrytsyndyshynquitcode/property-workflows/actions/runs/40295702568
- ADR (D): https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0001-template-versions-draft-and-immutable-versions.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0002-design-system-shadcn-tokens.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0003-next-16-4-3-security-patch.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0004-mochi-mascot.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0005-sidebar-aurora-click-effects.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0006-calm-work-pages-per-pm-tone.md, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/decisions/0007-theme-choice-on-device.md
- Архітектурне правило, крім `check:design` (D): job «Секретний ключ лише на сервері» (`scripts/check-server-boundary.mjs`) у `.github/workflows/architecture.yml` — червоний прогін на коміті-порушенні (Supabase-клієнт із `SUPABASE_SECRET_KEY` поза `admin.ts`): https://github.com/vhrytsyndyshynquitcode/property-workflows/actions/runs/40299502181, PR https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/17
- Акаунти для PM (E): pm-admin@example.test (admin), pm-manager@example.test (manager)
- Скріни за ролями (E): https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-role-admin-edit.png, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-role-admin-versions.png, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-role-manager-template.png, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-role-manager-edit-denied.png, https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-role-manager-versions-denied.png (повний набір — PR https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/18)
- AC зрізу 2 (E): AC-DSYS-01 (реалізовано), AC-DSYS-02 (реалізовано), AC-DSYS-03 (реалізовано), AC-DSYS-04 (реалізовано), AC-DSYS-05 (реалізовано), AC-DSYS-06 (реалізовано), AC-DSYS-07 (реалізовано), AC-DSYS-08 (реалізовано), AC-EDITOR-01 (реалізовано), AC-EDITOR-02 (реалізовано), AC-EDITOR-03 (реалізовано), AC-EDITOR-04 (реалізовано), AC-EDITOR-05 (реалізовано), AC-EDITOR-06 (реалізовано), AC-EDITOR-07 (реалізовано), AC-EDITOR-08 (реалізовано), AC-EDITOR-09 (реалізовано), AC-EDITOR-10 (реалізовано), AC-EDITOR-11 (реалізовано), AC-EDITOR-12 (реалізовано), AC-EDITOR-13 (реалізовано), AC-EDITOR-14 (реалізовано), AC-EDITOR-15 (реалізовано), AC-EDITOR-16 (реалізовано), AC-EDITOR-17 (реалізовано), AC-EDITOR-18 (реалізовано), AC-EDITOR-19 (реалізовано), AC-EDITOR-20 (реалізовано), AC-EDITOR-21 (відкладено (назва шаблону має зберігатися у версії — потрібні колонка template_versions.name, міграція й перейменування шаблону в редакторі; наступний PR)), AC-EDITOR-22 (відкладено (залежить від AC-EDITOR-21: назва шаблону запуску — з версії)), AC-EDITOR-23 (реалізовано), AC-EDITOR-24 (відкладено (перейменування шаблону в редакторі — разом з AC-EDITOR-21)), AC-EDITOR-25 (відкладено (стан «All changes kept» і повідомлення про втрачене з'єднання потребують клієнтського редактора замість форм без JS)), AC-EDITOR-26 (реалізовано), AC-EDITOR-27 (реалізовано), AC-EDITOR-28 (реалізовано), AC-EDITOR-29 (реалізовано)
- Відхилення від PM (E): не надходило

## Бонус

Цикл візуальної перевірки в браузері агента (Claude in Chrome): PR https://github.com/vhrytsyndyshynquitcode/property-workflows/pull/21 — промпт, знімки до й після, що агент
знайшов, виправив і пропустив. Під час приймання на проді обома ролями агент порівнював сторінки за знімками й обчисленими
стилями, а не лише за текстом: на `/runs/new` у темній темі невибраний шаблон (`outline` з рамкою) виглядав помітнішим за
вибраний (`secondary` без рамки), тож вибір читався навпаки; відмова редактора була без заголовка, на відміну від інших
відмов. Виправлено токенами (`border-primary`, `text-primary`, `bg-secondary`; контраст 6.35:1 / 5.83:1), перевірено на
Vercel Preview разом зі станом наведення (зауваження CodeRabbit). Знімки:
https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-visual-before-runs-new-dark.png,
https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/docs/img/ws7-visual-after-runs-new-dark.png. Висновок: тести логіки й текстові перевірки цю ваду не
ловили — її видно лише в браузері в одній з тем; Tab-навігацію й вузький екран агент не перевіряв.
