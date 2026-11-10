# JobBox — публичные документы

Страницы для App Store и Google Play: https://anatret.github.io/jobbox-legal/

- `privacy/index.html` — политика конфиденциальности;
- `delete-account/index.html` — как удалить аккаунт (для Google Play).

Не правьте их вручную. Тексты ведутся в репозитории `jobboxv3`
(`assets/agreements/policy.txt` и `docs/legal/delete_account.txt`),
страницы собираются из них:

    dart run tool/build_legal_pages.dart ../jobbox-legal
