# Домашнее задание к занятию 16 «Платформа мониторинга Sentry»

## Задание 1

Скриншот меню Projects в sentry.io

![image](https://github.com/user-attachments/assets/d9006e33-79be-4164-b93c-0f82dbd40002)


## Задание 2

Не нашел в интерфейсе кнопки `Generate sample event`, похоже ее убрали в новой версии. 
Поэтому импортировал sentry_sdk на ВМ в облаке и сгенерировал из тестового скрипта ошибку типа деления на ноль:

```
def test():
    return 1 / 0  # Вызов ZeroDivisionError
test()
```

<img width="1352" height="485" alt="image" src="https://github.com/user-attachments/assets/54f87943-2ca1-44cd-94cc-6aeb3c292d7f" />



`Stack trace`


<img width="1354" height="687" alt="image" src="https://github.com/user-attachments/assets/46034d08-5acc-41ff-a994-c4ff3bc98527" />


<img width="1348" height="682" alt="image" src="https://github.com/user-attachments/assets/9a0da110-35aa-41e5-8cf8-479bd08bbab0" />


Список событий проекта

<img width="1335" height="679" alt="image" src="https://github.com/user-attachments/assets/6f4c8be0-a4e4-400b-a4bd-0827e051e9ef" />


## Задание 3

Настроил правило алёртинга и сгенерировал тестовую ошибку.
Скрин сообщения по почте:


<img width="1038" height="653" alt="image" src="https://github.com/user-attachments/assets/c126b764-9935-4c8f-91f7-af145a483bd6" />




