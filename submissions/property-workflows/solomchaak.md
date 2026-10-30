# Здача WS7

## Дані

- Роль: pm
- Команда: property-workflows
- GitHub-логін: solomchaak
- Ваше репо: https://github.com/solomchaak/property-workflows-spec
- SHA: 4f886d8a9bf788b84fd58ff3d2c8b3b804585cd9
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: —

## PM

- Сховище вимог: issues
- Зріз 2: an administrator edits a template (changes are kept automatically) and saves it as a numbered version; a run keeps the version it was launched from; managers never see unpublished changes; all pages share one design system
- Продукт — матриця прав і roadmap (A): https://github.com/solomchaak/property-workflows-spec/issues/1 і коментарі «Зміна: …» https://github.com/solomchaak/property-workflows-spec/issues/1#issuecomment-6398138384, https://github.com/solomchaak/property-workflows-spec/issues/1#issuecomment-6439078821
- Вимоги зрізу 2 (B): https://github.com/solomchaak/property-workflows-spec/issues/19, https://github.com/solomchaak/property-workflows-spec/issues/20
- Відмовні AC і AC про стан інтерфейсу (B): вимога https://github.com/solomchaak/property-workflows-spec/issues/19 — AC-DSYS-02 (заборонена роль), AC-DSYS-03 (не увійшов); стан — AC-DSYS-04; вимога https://github.com/solomchaak/property-workflows-spec/issues/20 — AC-EDITOR-07 (заборонена роль), AC-EDITOR-09 (не увійшов); стан — AC-EDITOR-04 (помилка), AC-EDITOR-17 (порожній стан)
- Самоперевірка за чеклістом (B): https://github.com/solomchaak/property-workflows-spec/issues/19#issuecomment-6398180196, https://github.com/solomchaak/property-workflows-spec/issues/20#issuecomment-6398186435
- Питання, на які ви відповіли (C): https://github.com/solomchaak/property-workflows-spec/issues/21, https://github.com/solomchaak/property-workflows-spec/issues/22, https://github.com/solomchaak/property-workflows-spec/issues/23, https://github.com/solomchaak/property-workflows-spec/issues/24, https://github.com/solomchaak/property-workflows-spec/issues/25, https://github.com/solomchaak/property-workflows-spec/issues/26, https://github.com/solomchaak/property-workflows-spec/issues/27, https://github.com/solomchaak/property-workflows-spec/issues/28, https://github.com/solomchaak/property-workflows-spec/issues/29, https://github.com/solomchaak/property-workflows-spec/issues/30, https://github.com/solomchaak/property-workflows-spec/issues/31, https://github.com/solomchaak/property-workflows-spec/issues/32, https://github.com/solomchaak/property-workflows-spec/issues/33, https://github.com/solomchaak/property-workflows-spec/issues/34, https://github.com/solomchaak/property-workflows-spec/issues/35, https://github.com/solomchaak/property-workflows-spec/issues/36, https://github.com/solomchaak/property-workflows-spec/issues/37, https://github.com/solomchaak/property-workflows-spec/issues/38
- Зміни вимог із журналом змін (C): https://github.com/solomchaak/property-workflows-spec/issues/20#issuecomment-6439080473, https://github.com/solomchaak/property-workflows-spec/issues/19#issuecomment-6439079516, https://github.com/solomchaak/property-workflows-spec/issues/1#issuecomment-6439078821

### Приймання на проді (трек D)

| Розробник | Прод-URL | Роль (акаунт) | AC | Результат | Посилання |
|---|---|---|---|---|---|
| @dmudryk | https://property-workflows-bravo16.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/dmudryk/property-workflows/blob/12bd69d8344dd172af032ca83b720ecb14e46b16/tests/db/templates.test.ts#L201 |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/dmudryk/property-workflows/blob/12bd69d8344dd172af032ca83b720ecb14e46b16/tests/db/template-rules.test.ts#L87 |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/dmudryk/property-workflows/blob/12bd69d8344dd172af032ca83b720ecb14e46b16/tests/db/template-rules.test.ts#L134 |
| @dmudryk | https://property-workflows-bravo16.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/dmudryk/property-workflows/blob/12bd69d8344dd172af032ca83b720ecb14e46b16/tests/db/template-rules.test.ts#L281 |
| @dmudryk | https://property-workflows-bravo16.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/dmudryk/property-workflows/blob/12bd69d8344dd172af032ca83b720ecb14e46b16/tests/db/template-rules.test.ts#L326 |
| @vsmrnk | https://property-workflows.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/tests/db/template-versions-db.test.ts#L239 |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/tests/db/template-clarify-db.test.ts#L1 |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/tests/db/template-clarify-db.test.ts#L105 |
| @vsmrnk | https://property-workflows.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/tests/templates/editor.test.tsx#L108 |
| @vsmrnk | https://property-workflows.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/vsmrnk/property-workflows/blob/fe0a990ea2d384f204a22c3349a89ae8721ab899/tests/db/template-clarify-db.test.ts#L254 |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/tests/db/profiles-role.test.ts#L6 |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/tests/db/template-editor-oct27.test.ts#L75 |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/tests/templates/editor-oct27.test.ts#L22 |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/tests/db/template-editor-oct27.test.ts#L207 |
| @vhrytsyndyshynquitcode | https://property-workflows-one.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/vhrytsyndyshynquitcode/property-workflows/blob/fcc006d395c0b7887b348fac3498ff5340f52956/tests/db/template-editor-oct27.test.ts#L156 |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/tests/db/template-versions.test.ts#L206 |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/tests/db/template-editor-rules.test.ts#L71 |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/tests/db/template-editor-rules.test.ts#L84 |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/tests/db/template-editor-rules.test.ts#L104 |
| @ylehenkyi-qc | https://pmwp-ylehenkyi.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/ylehenkyi-qc/property-workflows/blob/289f53f192d5a190224b52eb9bcdd400fa2d5af6/tests/db/template-editor-rules.test.ts#L144 |
| @yuriivynar | https://property-workflows-eta.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/tests/db/template-versions.test.ts#L206 |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/tests/db/template-clarify.test.ts#L83 |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/tests/db/template-clarify.test.ts#L95 |
| @yuriivynar | https://property-workflows-eta.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/tests/db/template-clarify.test.ts#L151 |
| @yuriivynar | https://property-workflows-eta.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/yuriivynar/property-workflows/blob/5c4ef5bda555b91a524d2e2918bb687892262b5b/tests/db/template-name-versioned.test.ts#L111 |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-03 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-04 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | admin (pm-admin@example.test) | AC-EDITOR-05 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-DSYS-02 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-06 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-07 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-16 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-DSYS-04 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | не увійшов | AC-DSYS-03 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | не увійшов | AC-EDITOR-09 | ✅ | — |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-08 | ✅ (тест) | https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/tests/templates/editor-actions.test.ts#L2 |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-11 | ✅ (тест) | https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/tests/db/template-page-states-db.test.ts#L95 |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-12 | ✅ (тест) | https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/tests/db/template-page-states-db.test.ts#L117 |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | не увійшов | AC-EDITOR-26 | ✅ (тест) | https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/tests/templates/editor-actions-anon.test.ts#L1 |
| @OleksandrMartynov | https://property-workflows-rho.vercel.app | manager (pm-manager@example.test) | AC-EDITOR-29 | ✅ (тест) | https://github.com/OleksandrMartynov/property-workflows/blob/4c8ad478e533a6b6f45c721fde0ef6ad5d755550/tests/db/template-page-states-db.test.ts#L179 |

## Розробник

—

## Бонус

Розділ «Вигляд і тон»: https://github.com/solomchaak/property-workflows-spec/issues/1 (останній розділ issue «Продукт»; додано до теми, станом на коміт 4f886d8a9bf788b84fd58ff3d2c8b3b804585cd9).
