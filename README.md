# JobBox — публичные документы

Страницы для App Store и Google Play: https://anatret.github.io/jobbox-legal/

- `privacy/index.html` — политика конфиденциальности.

Не правьте `privacy/index.html` вручную. Текст ведётся в приложении
(`assets/agreements/policy.txt` в репозитории `jobboxv3`), страница
собирается из него:

    dart run tool/build_privacy_html.dart ../jobbox-legal/privacy/index.html
