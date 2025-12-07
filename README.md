# Домашнее задание по CI/CD

**Выполнил:** Герминов Артем Александрович

## Задание

Форкнуть репозиторий преподавателя и настроить CI/CD пайплайн с автоматическим запуском тестов при каждом коммите.

## Что сделано

✅ **Форкнут репозиторий:** https://github.com/CanUFeelMyHeart/new_rep_test

✅ **Добавлена функция умножения** (`/multiply?a=2&b=3`) в Flask приложение

✅ **Настроен GitHub Actions CI/CD:**
- Автоматический запуск тестов при каждом push
- Установка Python 3.8
- Установка зависимостей (Flask, pytest, coverage)
- Запуск тестов с coverage
- Отчет о покрытии кода

✅ **Пайплайн успешно выполняется** при каждом коммите

## Workflow файл

Файл `.github/workflows/test_on_push.yaml` содержит конфигурацию CI/CD пайплайна:
- Триггер: push в любую ветку
- Среда: Ubuntu latest
- Python версия: 3.8
- Шаги: checkout → setup python → install deps → run tests → coverage report

## Скриншоты

Скриншоты выполнения задания находятся в папке `screenshots/`

## Технологии

- Python 3.8
- Flask
- pytest
- coverage
- GitHub Actions

## Репозиторий

https://github.com/roux-afk/urfu-ci-cd-homework
