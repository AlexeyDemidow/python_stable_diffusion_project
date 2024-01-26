## Скрипт для взаимодействия с нейросетью Stable Diffusion в режиме img2 img inpainting

Для работы скрипта нужна локальная версия SD от AUTOMATIC1111

Инструкция по установке по [ссылке](https://www.itshneg.com/kak-ustanovit-stable-diffusion-poshagovaya-instrukciya/?utm_referrer=https%3A%2F%2Fyandex.by%2F)

### Принцип работы

- Запуск SD
- Создание директорий под маску, исходное фото и результат
- Поместить фото в папку _source_
- Скрипт создаст на ее основе маску
- Формируется запрос к API с использованием исходного фото и маски
- Сохраняется результат