# Конфигурация SONOFF-TX-Ultimate для ESPHome и Home Assistant

Этот проект предоставляет конфигурацию для устройства **SONOFF-TX-Ultimate** с использованием **ESPHome**.  
Основан на репозитории: [SmartHome-yourself/sonoff-tx-ultimate-for-esphome](https://github.com/SmartHome-yourself/sonoff-tx-ultimate-for-esphome).

## Особенности работы

### 1. Индикация состояния реле
- При включении реле загорается светодиод, сигнализирующий о его активности

### 2. Ночная подсветка
- Если ночная подсветка включена, индикация состояния реле **отключается** (приоритет ночной подсветки выше)
- Автоматически активируется после заката

### 3. Основная подсветка
- **Режимы работы**:
  - Статичный свет
  - Радуга
  - Пульсация
- Имеет приоритет над ночной подсветкой, **кроме случаев**:
  - Когда ночная подсветка включена автоматически (после заката)

## Установка и настройка
Подробные инструкции по прошивке и настройке доступны в оригинальном репозитории (смотри раздел Local use in ESPHome):  
[SmartHome-yourself/sonoff-tx-ultimate-for-esphome](https://github.com/SmartHome-yourself/sonoff-tx-ultimate-for-esphome)
