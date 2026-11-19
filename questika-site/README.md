# Questika: hero-блок лендинга

Статичная страница: `index.html` + `assets/hero.glb` (3D-персонаж) + `assets/bg.jpg` (фон).

## Запуск локально
Браузер не даёт грузить GLB с file://, поэтому нужен простой сервер:

    python3 -m http.server 8000

и открыть http://localhost:8000

## GitHub Pages
Загрузите содержимое папки в репозиторий и включите Settings -> Pages.

## Заменить персонажа
Положите новый .glb в `assets/hero.glb` (одна сетка с текстурой, до 5-6 МБ).
