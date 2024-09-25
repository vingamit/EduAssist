# EduAssist

Относительна простая реализация рага, пока что только есть возможность использовать YandexGPT.

Для запуска бота потребуется заполнить файл `.env` пример файла в `.env.example`

Команды для запуска.(Возможно понадобиться Python3.10.13, на других версиях не тестил)

1) Виртуальное окружение

```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
2) Загрузка данных с парсера (кажется с данными какая-то проблема :- )

```
python parser.py
```

3) Создание коллекции в Chroma и сохранения данных локально

```
python app/chroma_db_init.py
```

4) Запуск бота

```
python app/bot.py
```