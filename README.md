# observability-task-06
## Домашнее задание
Установка и настройка TICK стека

#### Цель:
Установить и настроить Telegraf, Influxdb, Chronograf, Kapacitor.
Результатом выполнения данного ДЗ будет являться публичный репозиторий, в системе контроля версий (Github, Gitlab, etc.), в котором будет находиться Readme с описанием выполненных действий. Файлы конфигурации Telegraf, Influxdb, Chronograf, Kapacitor должны находиться в директории TICK-1.


#### Описание/Пошаговая инструкция выполнения домашнего задания:
1. На виртуальной машине установите любую open source CMS, которая включает в себя следующие компоненты: nginx, php-fpm, database (MySQL or Postgresql);
2. На этой же виртуальной машине установите Telegraf для сбора метрик со всех компонентов системы (начиная с VM и заканчивая DB);
3. На этой же или дополнительной виртуальной машине установите Influxdb, Chronograf, Kapacitor
4. Настройте отправку метрик в InfluxDB.
5. Создайте сводный дашборд с самыми на ваш взгляд важными графиками, которые позволяют оценить работоспостобность вашей CMS;
6. Настройте правила алертинга для черезмерного потребления ресурсов, падения компонентов CMS и 500х ошибок;

#### Критерии оценки:
0 баллов - задание не выполнено согласно инструкции
1 балл - задание выполнено успешно согласно инструкции


#### Компетенции:
Системы мониторинга
- Установка и настройка мониторинга сервиса, используя компоненты TICK стека
