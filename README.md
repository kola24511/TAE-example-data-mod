# Example Data Mod

A data mod example for **The Adventurer's Era**. Adds a blue crystal
that drops from the test mob: 1–3 items with a 25% drop chance.
No C# code, SDK, or build tools are required.

## Structure

```text
module.json           # Mod metadata and content file paths
Data/
  items.json          # Item definitions
  loot.json           # Drop rules
Icons/crystal.png     # Item and mod icon
assets/lang/
  en/items.json       # English translations
  ru/items.json       # Russian translations
```

## Installation

Copy this folder into `Mods` next to the game executable.
The manifest should be at `Mods/example.crystal/module.json`.
Restart the game and check the mod list. The mod uses the existing test mob;
it does not spawn mobs itself.

---

# Пример дата-мода

Пример дата-мода для **The Adventurer's Era**. Добавляет синий кристалл,
который выпадает с тестового моба: 1–3 штуки с шансом 25%.
C#-код, SDK и инструменты сборки не нужны.

## Структура

```text
module.json           # Метаданные мода и пути к файлам контента
Data/
  items.json          # Описания предметов
  loot.json           # Правила выпадения
Icons/crystal.png     # Иконка предмета и мода
assets/lang/
  en/items.json       # Английские переводы
  ru/items.json       # Русские переводы
```

## Установка

Скопируй эту папку в `Mods` рядом с исполняемым файлом игры.
Манифест должен находиться по пути `Mods/example.crystal/module.json`.
Перезапусти игру и проверь список модификаций. Мод использует существующего
тестового моба и не создаёт мобов самостоятельно.
