# face-livness-web

![Пример GIF](https://github.com/Fanfar1c/face-liveness-web/blob/main/src/test.gif?raw=true)

Протестировать можно по ссылке: [Сайт](https://fanfar1c.github.io/face-liveness-web/)


## Проверка фото на живость

Данный проект призван определять, является ли предоставленная фотография реальной или фейковой с использованием техник обработки изображений. Реализация выполнена на языке C++ с использованием библиотеки OpenCV для обработки изображений и NCNN для инференса нейронной сети. Кроме того, модель конвертирована в формат WebAssembly (WASM) с помощью Emscripten для простого развертывания и интеграции в веб-приложения.

### Возможности
Определение Реальности vs. Подделки: Система различает реальные и фейковые фотографии, анализируя различные характеристики изображений.


### Запуск через Live Server (VSCode Extension)

- Установите расширение Live Server в VSCode.
- Откройте ваш HTML файл в VSCode.
- Нажмите правой кнопкой мыши по файлу и выберите "Open with Live Server".

### Запуск через Python

- Откройте терминал.
- Перейдите в папку, содержащую ваш файл, используя команду `cd путь_к_папке`.
- Запустите локальный сервер Python с помощью команды:

```bash
python -m http.server

```
- После запуска сервера, вы можете открыть свой браузер и перейти по адресу [http://localhost:8000/](http://localhost:8000/) для просмотра вашего проекта.


### Запуск через Node.js

- Убедитесь, что у вас установлен Node.js на вашем компьютере.

- Откройте терминал.

- Перейдите в папку, содержащую ваш файл, используя команду `cd путь_к_папке`.

- Запустите локальный сервер Node.js с помощью команды:

```bash
npx http-server

```

- После запуска сервера, вы также можете открыть свой браузер и перейти по адресу http://localhost:8080/ для просмотра вашего проекта.



### Модель определение лица и определение liveness вшиты в файл Emscrippeng_test.data

### Есть вопросы пишите  [Telegram](https://t.me/dastan4row/)