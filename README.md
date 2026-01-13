Lib:
```pip install paho-mqtt```

Start venv:
```.venv/Scripts/activate``` - Windows
```source venv/bin/activate``` - macOS/Linux

Stop venv:
```deactivate```

Start program:
```python mqtt_brute_forcer.py -H your.mqtt.broker.com -p 1883 -u username -w wordlist.txt```

Example:
Описание
В офисе DUCKERZ установили систему умного дома. Жалко, что это делали неумные люди (можно хотя бы было логин admin заменить, что ли).
Задание
```mqtt://tasks.duckerz.ru:30015```

Start:
```python main.py -H tasks.duckerz.ru -p 30015 -u admin -w wordlist1.txt```


Nota!
worldlist.txt - 38650-password-sktorrent.txt
worldlist1.txt - 1000000-password-seclists.txt - most common passwords from breach data

Resource:
https://github.com/duyet/bruteforce-database