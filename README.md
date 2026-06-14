<p align="center">
	<img width="500" height="500" alt="tarot_logo" src="https://github.com/user-attachments/assets/4d6d06ee-4575-4b90-926a-a590469acc09" />
</p>

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Version-1.0(alpha)-blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/License-MIT-green">	
</p>

## О проекте

Данный проект создан с целью предоставления возможности всем желающим бесплатного ресура для изучения карт Таро с возможностью получения их расклада в ответ на заданный вопрос.

## Установка

Процесс установки:

1. В репозитории проекта в верхней части нажать перейти в раздел «<> Code» и выбрать «Download ZIP» и распокавать данный архив в любое удобное место;
2. В распакованном каталоге запустить файл «TarotSetup_no_llm.exe» и проследовать шагам установки, по умолчанию приложение устанавливается по пути «C:\Program Files (x86)\Tarot»;
3. В каталоге приложения вручную создать пустой каталог с названием «models»;
4. Перейти по [ссылке](https://huggingface.co/unsloth/Qwen2.5-VL-7B-Instruct-GGUF/blob/main/Qwen2.5-VL-7B-Instruct-Q4_K_M.gguf) на сайт Hugging Face в репозиторий нейросети unsloth/Qwen2.5-VL-7B-Instruct-GGUF и загрузить на устройство файл версии Qwen2.5-VL-7B-Instruct-Q4_K_M.gguf под названием «Qwen2.5-VL-7B-Instruct-Q4_K_M.gguf».
5. Загруженный файл нейросети «Qwen2.5-VL-7B-Instruct-Q4_K_M.gguf» переместить в созданный ранее каталог «models».
6. Запустить файл «start.vbs» который автоматически запустит сервер и откроет веб-страницу проекта по адреcу [localhost:8080](http://localhost:8080).

## Документация

Системные требования!



## Разработчики

- Маматова Эвелина — Frontend (разработка логики и сайта);
- Екшова Алина — Frontend (разработка логики и сайта);
- Гусев Михаил — Backend (разработка архитектуры работа с GitHub);
- Патрушев Врсений — Backend (разработка ядра и архитектуры);
- Трубицын Степан — Backend (работа с ИИ);

## Лицензия

Проект «Tarot_ai_explainer» распространается под лицензией MIT.
