## Sounding_Time
###### Zyblyuk Roman


# Запуск Проекта 
Создайте виртуальную среду Python и установите зависимости:
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

После установки зависимостей запишите голос запустив скрипт create_audio_files.py: 

```
python create_audio_files.py
```

Затем нужно очистить звук от лишней тишины скриптом clear_empty.py: 
```
python clear_empty.py
```

Приготовления закончены, теперь можно узнать время запустив main.py
```
python main.py
```
