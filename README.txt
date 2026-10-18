ПРИЛОЖЕНИЕ «ЦЕНЫ» — ПРОЕКТ ДЛЯ СБОРКИ APK

Способ 1 (без установки программ, через сайт GitHub):
 1. Зарегистрируйся на github.com (бесплатно).
 2. Нажми «+» → New repository → назови prices → Create repository.
 3. Нажми «uploading an existing file» и перетащи сюда ВСЕ файлы и папки из этой папки
    (включая скрытую папку .github). Нажми Commit changes.
 4. Открой вкладку Actions → Build APK → дождись зелёной галочки (3–6 минут).
 5. Внутри запуска внизу в разделе Artifacts скачай prices-apk (zip) и распакуй:
    там файл app-debug.apk.
 6. Перешли apk на телефон, открой его. Если спросит, разреши установку из этого источника.

Способ 2: открой папку в Android Studio (File → Open) и нажми Build → Build APK(s).

Как обновлять цены: заменить файл app/src/main/assets/index.html на новый и собрать заново.
