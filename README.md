# face-livness-web

![Пример GIF](https://ссылка_на_ваш_файл_в_gif_формате.gif)

Проверка фото на живость

Данный проект призван определять, является ли предоставленная фотография реальной или фейковой с использованием техник обработки изображений. Реализация выполнена на языке C++ с использованием библиотеки OpenCV для обработки изображений и NCNN для инференса нейронной сети. Кроме того, модель конвертирована в формат WebAssembly (WASM) с помощью Emscripten для простого развертывания и интеграции в веб-приложения.

Возможности
Определение Реальности vs. Подделки: Система различает реальные и фейковые фотографии, анализируя различные характеристики изображений.