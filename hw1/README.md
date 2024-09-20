# Структура репозитория 
itmo-python-backend/
│
├── hw1/
│   ├── __init__.py
│   ├── myapp.py
│   └── src/
│       ├── __init__.py
│       ├── factorial.py
│       ├── fibonacci.py
│       ├── mean.py
│       └── utils.py
└── venv/



# Запуск проекта

1. ``` git clone https://github.com/Stepan5024/itmo-python-backend.git ```
2. ``` cd ``` 
3. ``` python3.10 -m venv venv ```
3.1 Если есть ошибки установки python 3.10 brew install python@3.10
4. masOs: ```source venv/bin/activate``` windows ```venv\Scripts\activate```
5. ```pip install -r requirements.txt```
6. ```uvicorn hw1.myapp:app --reload```
