# Здача WS7

## Дані

- Роль: pm
- Команда: school-purchasing
- GitHub-логін: ValiaBihun
- Ваше репо: https://github.com/ValiaBihun/2026-quitcode-dream-team
- SHA: 8f0fee554e7d6c50ba62e995aefda3eab7156eaa
- Репо вимог PM: https://github.com/ValiaBihun/2026-quitcode-dream-team
- Прод-URL: —

## PM

- Сховище вимог: issues
- Зріз 2: працівник подає закупівлю через форму лише у свої відділи й за своїми дозволами, а схвалювач вирішує лише по заявках свого відділу; чужі дані, заборонені дії й відвідувач без входу отримують чітку відмову; увесь інтерфейс показано англійською
- Продукт — матриця прав і roadmap (A): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/1 і коментар «Зміна: …» https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/1#issuecomment-6365597208
- Вимоги зрізу 2 (B): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/47, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/48
- Додаткова вимога зрізу 2 (поза B): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/49 — інтерфейс англійською; мовна вимога, відмову за правами для неї покрито вимогами https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/47 і https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/48 (AC-LANG-03 — текст відмови англійською)
- Відмовні AC і AC про стан інтерфейсу (B): вимога https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/47 — AC-FRM-08 (чужі дані), AC-FRM-03 і AC-FRM-04 (заборонена роль), AC-FRM-09 (не увійшов), AC-FRM-02 (межа відділу); стан — AC-FRM-05 (порожній стан), AC-FRM-06 (помилка). Вимога https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/48 — AC-APR-03 (чужі дані), AC-APR-04 (заборонена роль), AC-APR-05 (межа: власна заявка); стан — AC-APR-06 (помилка)
- Самоперевірка за чеклістом (B): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/47#issuecomment-6365768937, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/48#issuecomment-6365769338, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/49#issuecomment-6453458289
- Питання, на які ви відповіли (C): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/50, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/51, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/52, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/53, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/54, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/55, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/56, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/57, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/58, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/59, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/60, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/61, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/62
- Зміни вимог із журналом змін (C): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/47#issuecomment-6453442348, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/48#issuecomment-6453443124, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/49#issuecomment-6453443941, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/1#issuecomment-6453445055

### Приймання на проді (трек D)

| Розробник | Прод-URL | Роль (акаунт) | AC | Результат | Посилання |
|---|---|---|---|---|---|
| @YarynaPankivv | https://school-purchasing.vercel.app | не увійшов (вікно інкогніто) | AC-FRM-09 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | не увійшов (вікно інкогніто) | AC-LANG-02 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-01 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-03 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-06 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-07 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-10 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-11 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-15 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-APR-04 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-LANG-01 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-LANG-04 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-01 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-02 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-03 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-06 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-07 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-05 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-06 | ✅ | — |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-02 | ✅ (тест) | https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/tests/db/frm-apr.test.ts#L77 |
| @YarynaPankivv | https://school-purchasing.vercel.app | працівник (pm-requester@example.test) | AC-FRM-04 | ✅ (тест) | https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/tests/db/frm-apr.test.ts#L96 |
| @YarynaPankivv | https://school-purchasing.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-05 | ✅ (тест) | https://github.com/YarynaPankivv/school-purchasing/blob/d9bf88270d028d1d25f9467d05c034bbefa84d6a/tests/db/frm-apr.test.ts#L301 |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | не увійшов (вікно інкогніто) | AC-FRM-09 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | не увійшов (вікно інкогніто) | AC-LANG-02 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-01 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-03 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-06 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-07 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-10 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-11 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-15 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-APR-04 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-LANG-01 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-LANG-04 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-01 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-02 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-03 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-06 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-07 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-05 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-06 | ✅ | — |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-02 | ✅ (тест) | https://github.com/kdeineko-tech/school-purchasing/blob/f739e3e7a945a55e4de3860d6b20d839614b3fe7/tests/db/purchases.test.ts#L51 |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | працівник (pm-requester@example.test) | AC-FRM-04 | ✅ (тест) | https://github.com/kdeineko-tech/school-purchasing/blob/f739e3e7a945a55e4de3860d6b20d839614b3fe7/tests/db/purchases.test.ts#L73 |
| @kdeineko-tech | https://school-purchasing-lemon.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-05 | ✅ (тест) | https://github.com/kdeineko-tech/school-purchasing/blob/f739e3e7a945a55e4de3860d6b20d839614b3fe7/tests/db/decisions.test.ts#L105 |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | не увійшов (вікно інкогніто) | AC-FRM-09 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | не увійшов (вікно інкогніто) | AC-LANG-02 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-01 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-03 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-06 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-07 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-10 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-11 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-15 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-APR-04 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-LANG-01 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-LANG-04 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-01 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-02 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-03 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-06 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-07 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-05 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-LANG-06 | ✅ | — |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-02 | ✅ (тест) | https://github.com/mvorobets-blip/school-purchasing/blob/498ec2f7be53260e0dc7aab2bfc71755e215ed6a/tests/db/purchase.test.ts#L45 |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | працівник (pm-requester@example.test) | AC-FRM-04 | ✅ (тест) | https://github.com/mvorobets-blip/school-purchasing/blob/498ec2f7be53260e0dc7aab2bfc71755e215ed6a/tests/db/purchase.test.ts#L63 |
| @mvorobets-blip | https://therapy-scheduling-ten.vercel.app | схвалювач (pm-approver@example.test) | AC-APR-05 | ✅ (тест) | https://github.com/mvorobets-blip/school-purchasing/blob/498ec2f7be53260e0dc7aab2bfc71755e215ed6a/tests/db/approval.test.ts#L90 |

Примітка до прод-URL @mvorobets-blip: `https://therapy-scheduling-ten.vercel.app` — це домен Vercel-проєкту, який розробниця назвала інакше; за адресою працює її застосунок «School Purchasing» з репо https://github.com/mvorobets-blip/school-purchasing (адреса вказана в полі «Website» репо й у її рев'ю HW7), сторінка входу англійською.

## Розробник

—

## Бонус

Розділ «Вигляд і тон» у «Продукті»: https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/1 (розділ «### Вигляд і тон» наприкінці issue), коментар «Зміна: додано розділ «Вигляд і тон»» https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/1#issuecomment-6365597760. Опубліковано 23.10 разом із вимогами, тому розробники могли взяти його через /requirements-sync.
