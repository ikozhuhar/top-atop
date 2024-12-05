# Мониторинг процессов ps top atop

https://www.8host.com/blog/osnovnye-komandy-linux-kak-rabotaet-atop/


## Как управлять процессами в Linux с помощью ps и top 

Управление процессами — одна из ключевых задач любого системного администратора. Linux предоставляет мощные инструменты для мониторинга и контроля, такие как ps и top. Давай разберём, как их использовать эффективно. 

## Мониторинг процессов с помощью ps  

`ps` — это базовая команда для просмотра списка процессов.

**Примеры использования:**

**1. Посмотреть все процессы текущего пользователя:**
```
ps -u
```
**2. Вывести все процессы в системе:**
```
ps -e
```
**3. Получить детализированную информацию о процессах:**
```
ps aux
```

Здесь:  
   - `a` — показывает процессы всех пользователей, работающих в терминале.  
   - `u` — выводит информацию о владельце процесса.  
   - `x` — включает процессы, не привязанные к терминалу


## Мониторинг процессов с помощью `top` 

`top` — интерактивный инструмент для мониторинга процессов в реальном времени.  

Основные команды внутри `top`: 

1. Сортировка по загрузке CPU: Нажми `P`.  
2. Сортировка по использованию памяти: Нажми `M`.  
3. Убить процесс прямо из top: Нажми `k`, введи `PID` и подтверди.  
4. Фильтрация процессов по пользователю: Нажми `u` и введи имя пользователя.  

Чтобы сделать вывод более удобным, попробуй заменить `top` на `htop`, который предоставляет цветной интерфейс и больше возможностей для управления процессами.
