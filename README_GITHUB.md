# Minecraft Java Launcher — GitHub build

Этот вариант настроен так, чтобы APK собирался в GitHub Actions без ПК.

## Как собрать APK с Android

1. Открой GitHub в браузере и создай новый **публичный** репозиторий.
2. Распакуй этот архив и загрузи **содержимое папки** `MinecraftJavaLauncher_GitHub` в репозиторий. Важно: папка `.github/workflows` тоже должна попасть в репозиторий.
3. Сделай commit в ветку `main`.
4. Открой вкладку **Actions** → workflow **Build Android APK**.
5. Если workflow ещё не запустился после commit, нажми **Run workflow**.
6. Дождись зелёной галочки.
7. Открой завершённый запуск workflow → раздел **Artifacts** → скачай `MinecraftJavaLauncher-debug-apk`.
8. Распакуй скачанный ZIP и установи `app-debug.apk` на Android.

## Что собирается

Сейчас это версия 0.2: интерфейс лаунчера, выбор версии, профиля FPS, renderer/backend, Java Runtime, RAM, render scale и оптимизаций. Кнопка запуска пока не запускает настоящий Minecraft Java.

Следующий этап — подключить настоящий Minecraft Java runtime, файлы версии/библиотеки/assets, локальный профиль и реальный запуск процесса. Авторизацию Microsoft и обход официальной авторизации этот проект не реализует.
