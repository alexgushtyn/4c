# Парсер вакансий с платформ HeadHunter.ru и SuperJob.ru
Парсер создан для сбора информации с сайтов HeadHunter и SuperJob. Представляет собой пример MVP - минимально жизнеспособного продукта, который удовлетворяет базовым поставленным задачам.
## Требования
Для корректной работы потребуется установка API-ключа от SuperJob в переменную среды. В таком случае доступ к нему будет осуществлен с помощью библиотеки os через метод os.environ.get('API_KEY_SJ'), где API_KEY_SJ - пользовательское название переменной.
## Установка
Рекомендуется использовать виртуальное окружение проекта (в данном проекта использовался venv).
Для корректной работы рекомендуется Python 3.11.3 версии.
Необходимо установить модули
> pip install -r requirements.txt
## Запуск
Находясь в папке проекта, необходимо ввести в консоли
> python main.py


Код написан в образовательных целях для курсовой работы на курсе  Python-разработчиков от [sky.pro](https://sky.pro/)