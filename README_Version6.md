```markdown
# test-parsers — тестовые метаданные для парсеров

В репозитории находятся 3 тестовых JSON-файла метаданных (формат ERC‑721 / OpenSea‑friendly).  
Используйте их для локального тестирования парсеров или для деплоя на GitHub Pages / raw.githubusercontent.

Файлы:
- metadata/1.json
- metadata/2.json
- metadata/3.json
- assets/1.png, assets/2.png, assets/3.png (опционально — изображения)

Как получить рабочие ссылки
1) Raw GitHub (работает сразу после пуша в ветку main):
   https://raw.githubusercontent.com/<USERNAME>/<REPO>/main/metadata/1.json
   https://raw.githubusercontent.com/<USERNAME>/<REPO>/main/metadata/2.json
   https://raw.githubusercontent.com/<USERNAME>/<REPO>/main/metadata/3.json

2) GitHub Pages (если включите Pages с источником: main / docs или gh-pages):
   - Если вы поместите metadata/ и assets/ в папку docs/ и запушите на main:
     https://<USERNAME>.github.io/<REPO>/metadata/1.json
     https://<USERNAME>.github.io/<REPO>/metadata/2.json
     https://<USERNAME>.github.io/<REPO>/metadata/3.json

Быстрая инструкция (команды)
# создайте локальную папку, положите туда файлы (metadata/, assets/, README.md)
git init
git add .
git commit -m "Initial: test metadata for parsers"
git branch -M main
# создайте репо на GitHub (через сайт) и вставьте URL вместо <URL>
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git push -u origin main

Советы:
- Для простого теста можно использовать raw.githubusercontent ссылки (не требует Pages).
- Для более «красивого» URL — переместите metadata/ и assets/ в docs/ и включите Pages (Settings → Pages → Source: main / docs).
```