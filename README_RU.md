# NEON DRIFT 3D — Android APK через GitHub Actions

## Как собрать с телефона
1. Создай новый репозиторий на GitHub, например `neon-drift-3d`.
2. Загрузи **содержимое** этой папки в корень репозитория (папки `.github` и `app` должны быть видны в корне рядом с `build.gradle` и `settings.gradle`).
3. Открой вкладку **Actions**. Если GitHub попросит разрешить workflows, нажми разрешение.
4. Выбери **Build NEON DRIFT 3D APK** → **Run workflow** → **Run workflow**.
5. Дождись зелёной галочки. Открой завершённый запуск и скачай artifact `NEON-DRIFT-3D-APK`.
6. Распакуй скачанный artifact ZIP и установи `app-debug.apk`. Если Android спросит, разреши установку из этого источника.

## Примечания
- Для первого запуска игре нужен интернет: текущая HTML-версия загружает Three.js с CDN.
- Это debug APK для тестирования; для публикации в Google Play понадобится подписанный release build.
