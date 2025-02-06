# Data Science Template

Небольшой шаблон проекта под нужны машинного обучения и анализа данных

В шаблон включён используемый мной профиль VS Code

Включённые пакеты Python:

- matplotlib - для графиков
- numpy - для ускорения массивов
- pandas - для работы с таблицами данных
- nbconvert - чтобы конвертировать jupyter в HTML (Необходима среда с javascript) или PDF (Необходим TeX https://nbconvert.readthedocs.io/en/latest/install.html#installing-tex)
- pytorch - для глубокого обучения

(Все зависимости устанавливаются из файла requirements)

Дополнения VS Code:

- Python, Pylance - поддержка языка и линтер
- Docker - комфортная работы с контейнерами
- Jupyter - поддержка Jupyter Notebooks
- Live Server - веб-сервер для отображения HTML-файлов
- WSL - подсистема Linux для Windows 
- SSH - подключение к удалённому хосту

Шаблон устаналивается с помощью cookiecutter

```
pip install cookiecutter
```

```
cookiecutter https://github.com/Monoclocker/my-data-science-preset.git
```