# DatITMObot
  DatITMO - телеграм чат бот знакомств для подростков на Python
 
 Для реализации работы с telegram api используется библиотека aiogram, а из субд используется sqlite
 
 Из функционала :
  - создание анкеты
  - поиск по анкетам
  - редактирование анкеты
  - рейтинг анкет
  - админка
  - ранговая система
  - привязка инстаграмма
  - жалобы
  - откакт действий
 
 Архитектура проекта - Основная логика хранится в main.py, настройки в config.py. В database.py, в классе dbworker хранится работа с бд,а в custom_answer.py - массивы с кастомными ответами юзеров(нужно в будущем переписать на vedis)


# Примеры пользования
