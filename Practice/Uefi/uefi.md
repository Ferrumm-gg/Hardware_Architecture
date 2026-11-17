# Задача 1. Навигация по основным разделам

![alt text](images/image.png)

* Версия UEFI BIOS: `N46ET09W` (дата: `2024-01-22`)
* Серийный номер (System-unit serial number): `PF12345`
* Тип CPU: `Intel(R) Core(TM) CPU` (`1.X00GHz`)
* Установленная память: `8192MB`
* Статус UEFI Secure Boot: `On`

> Точный путь: `Main`

# Задача 2. Смена порядка загрузки

![alt text](images/image-1.png)

USB HDD перенесен на первое место, NVMe0 на второе

> Точный путь: `Startup -> Boot -> Boot Priority Order`

# Задача 3. Включение/выключение Secure Boot

![alt text](images/image-2.png)

Требуется перезагрузка

> Точный путь: `Security -> Secure Boot -> Secure Boot`

# Задача 4. Установка пароля супервизора

![alt text](images/image-3.png)

> Точный путь: `Security -> Password -> Supervisor Password`

# Задача 5. Сброс на заводские настройки

![alt text](images/image-4.png)

> Точный путь: `Restart -> Load Factory Defaults`

Сбросился порядок загрузки к исходному

![alt text](images/image-5.png)

# Задача 6. Управление встроенными устройствами

![alt text](images/image-6.png)

> Точный путь: `Config -> USB -> Always On USB`

# Задача 7. Режим работы SATA/NVMe

![alt text](images/image-7.png)

В эмуляторе ThinkPad T14s Gen 5 нет настройки режима работы накопителей

# Задача 8. Временное меню загрузки (эмуляция F12)

![alt text](images/image-8.png)

> Точный путь: `Startup -> Boot Device List F12 Option`

# Задача 9. Просмотр системных логов

![alt text](images/image-9.png)

(Simulator not support)

> Точный путь: `Main -> BIOS Event log`

# Задача 10. Полный сценарий: подготовка к переустановке ОС

### 1. Сбросить настройки на Factory Defaults

![alt text](images/image-10.png)

### 2. Включить Secure Boot

![alt text](images/image-11.png)

### 3. Установить Supervisor Password 

![alt text](images/image-12.png)
![alt text](images/image-13.png)

### 4. Поставить USB первым в порядке загрузки

![alt text](images/image-14.png)

### 5. Сохранить и выйти

![alt text](images/image-15.png)

### 6. Снова войти, проверить настройки, сбросить пароль и вернуть порядок загрузки

![alt text](images/image-16.png)

>Изменения сохранились

### Возврат настроек:

![alt text](images/image-17.png)
![alt text](images/image-18.png)