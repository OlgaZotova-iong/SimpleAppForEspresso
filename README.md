# Espresso-Android-Automation

Учебный проект по автоматизации тестирования Android-приложения с использованием фреймворка **Espresso**. Проект демонстрирует навыки написания UI-тестов для проверки корректности отображения элементов интерфейса.

## 🛠 Технологический стек
- **Язык:** Java.
- **Инструменты:** Android SDK, Espresso.
- **Архитектура:** Navigation Component, DrawerLayout.

## 🧪 Область тестирования (Scope of Testing)
Тестирование сосредоточено на проверке ключевых UI-компонентов:
- **Smoke-тестирование:** Проверка корректности отображения главного экрана (`HomeFragment`).
- **Валидация контента:** Проверка соответствия текста в элементах интерфейса (`withText`).
- **Навигация:** Тестирование базовых элементов управления (Navigation Drawer, Toolbar, Floating Action Button).

## 📊 Результаты тестирования
Проект успешно прошел этап автоматизированного тестирования.
- **Статус сборки:** Успешно (Build Passed).
- **Результат тестов:** Все сценарии в `EspressoTest` выполнены успешно.
- **Отчет:** См. [Issue #1](https://github.com/OlgaZotova-iong/SimpleAppForEspresso/issues/1) в репозитории.

## 🚀 Как запустить тесты
1. Клонируйте репозиторий:
   `git clone https://github.com/OlgaZotova-iong/SimpleAppForEspresso.git
2. Откройте проект в **Android Studio**.
3. Запустите тесты через терминал проекта:
   `./gradlew connectedAndroidTest`

## 📈 Навыки
- Написание UI-автотестов на **Espresso**.
- Работа с `ViewMatchers` и `ViewAssertions`.
- Управление жизненным циклом Activity в тестах (`ActivityScenarioRule`).
- Анализ результатов тестирования и работа с отчетами.