# Домашнее задание к занятию «Введение в микросервисы»

## Задача

Руководство крупного интернет-магазина, у которого постоянно растёт пользовательская база и количество заказов, рассматривает возможность переделки своей внутренней   ИТ-системы на основе микросервисов. 

Вас пригласили в качестве консультанта для оценки целесообразности перехода на микросервисную архитектуру. 

Опишите, какие выгоды может получить компания от перехода на микросервисную архитектуру и какие проблемы нужно решить в первую очередь.

## Решение
**Плюсы:**
- Возможность использовать разные технологии - при необходимости можно совмещать разные технологии и подходы - в рамках существующих договоренностей
- Устойчивость к ошибкам - при правильном подходе можно организовать устойчивую к ошибкам систему или в случае выхода одного или нескольких компонентов система будет продолжать работать
- Масштабируемость - в зависимости от нагрузки или потребностей проще реализовать горизонтальное масштабирование нужных компонентов по отдельности
- Простота развёртывания - можно проще и быстрее внедрять нововведения только для отдельных сервисов или откатываться к рабочей версии этих сервисов в случае возникновения проблем
- Простота замены - возможность при необходимости заменить устаревший сервис используя новые или более подходящие технологии
- Отражение структуры организации - можно создать более продуктивную систему при разделении команд для разных сервисов с разными задачами и целями

**Итог:** при правильном подходе можем сократить затраты, повысить выпуск более надежных обновлений и получить надежную, отказоустойчивую систему

**Минусы:**
- Проблемы разработки
  - Совместимость API - нужно больше уделять внимания прямой и обратной совместимости сервисов
  - Версионирование артефактов - нужно знать какие версии и библиотеки искользуются
  - Автоматизация сборки и тестирования - нужно больше времени уделять автоматизации и тестированию
  - Документация - необходимо иметь актуальную документацию
  - Инфраструктура разработки - нужна база для быстрого создания сервисов
- Проблемы эксплуатации
  - Мониторинг - необходима дополнительная система мониторинга за всеми сервисами
  - Сбор логов - необходима дополнительная система для сбора и анализа логов
  - Управление настройками - требуетя дополнительное внимание к настройкам для взаимосвязи между сервисами
  - Управление инфраструктурой - нужно допольнительно расчитвать где, что и с чем будет эффективнее работать
 
  **Итог:** для микросервисной архитектуры нужно будет выделять больше времени на ее обслуживание и станут необходимы квалифицированные специалисты, которые смогут быстрее решать задачи и осуществлять подготовку необходимых компонентов, что в свою очередь влияет на общую стоимость проекта

