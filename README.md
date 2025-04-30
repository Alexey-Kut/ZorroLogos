🎨 ZorroLogos — AI Logo Generator with Flask + YandexArt

ZorroLogos — это веб-приложение, которое позволяет сгенерировать логотип по описанию, форме и стилю. Генерация изображений происходит с помощью YandexArt — нейросети от Яндекса (YandexGPT API).

Пример сгенерированного логотипа

<img src="static/image.jpeg" alt="Логотип ZorroLogos" width="300">

Возможности

- Ввод формы, стиля и описания логотипа
- Генерация через API YandexArt
- Отображение результата прямо на сайте
- Обработка ошибок (если API недоступен или не отвечает)

🛠️ Используемые технологии

- Python 3.x
- Flask
- HTML + Jinja2
- YandexGPT API (YandexArt)
- Bootstrap (по желанию для стилей)

 Как запустить

1. Установить зависимости (если нужно):
```bash
pip install flask
