# The Sims 4 - Change Language / Смена Языка

[![GitHub stars](https://img.shields.io/github/stars/AristarhUcolov/The-Sims-4-Change-Language?style=flat-square)](https://github.com/AristarhUcolov/The-Sims-4-Change-Language/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/AristarhUcolov/The-Sims-4-Change-Language?style=flat-square)](https://github.com/AristarhUcolov/The-Sims-4-Change-Language/issues)

Simple tool to change The Sims 4 game language using Windows Registry files.

Простой инструмент для смены языка игры The Sims 4 с помощью файлов реестра Windows.

---

## 🇬🇧 English

### 📋 Description

This repository contains Windows Registry files (.reg) that allow you to quickly change the language in The Sims 4 game. The language change is done by modifying the registry key that stores the game's locale setting.

### ⚠️ Important Warnings

- **Always create a backup** of your registry before making any changes
- **Close The Sims 4** completely before applying registry changes
- These files modify Windows Registry - use at your own risk
- Administrator privileges may be required to apply the changes

### 📦 Prerequisites

- Windows operating system
- The Sims 4 game installed
- Administrator rights on your computer

### 🚀 How to Use

1. **Download** the registry file for your desired language:
   - `Sims 4 - English.reg` - for English language
   - `Sims 4 - Russian.reg` - for Russian language

2. **Close The Sims 4** if it's currently running

3. **Double-click** on the downloaded `.reg` file

4. **Confirm** the action when Windows asks if you want to add the information to the registry
   - Click "Yes" or "Run" when prompted

5. **Restart** The Sims 4 game

6. The game should now start in the selected language

### 🔧 Manual Registry Editing (Alternative Method)

If you prefer to edit the registry manually:

1. Press `Win + R` and type `regedit`, then press Enter
2. Navigate to: `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Maxis\The Sims 4`
3. Find the `Locale` value
4. Double-click on `Locale` and change it to:
   - `en_EN` for English
   - `ru_RU` for Russian
5. Click OK and close Registry Editor
6. Restart The Sims 4

### 🌍 Supported Languages

Currently, this repository includes:
- English (`en_EN`)
- Russian (`ru_RU`)

You can create registry files for other languages by following the same pattern and using appropriate locale codes (e.g., `de_DE` for German, `fr_FR` for French, `es_ES` for Spanish, etc.)

### ❓ Troubleshooting

**The language didn't change:**
- Make sure you closed The Sims 4 completely before applying the registry file
- Verify that the registry changes were applied by checking Registry Editor
- Try restarting your computer
- Make sure your game version supports the selected language

**Registry file won't open:**
- Right-click on the file and select "Merge"
- Run it as Administrator
- Check that you have sufficient permissions

**Game crashes or won't start:**
- Revert the changes by applying the original language registry file
- Verify game files integrity through Origin/EA app
- Reinstall the game if necessary

### 📝 License

This project is provided as-is for educational and convenience purposes. Use at your own risk.

### 🤝 Contributing

Feel free to contribute by adding support for more languages! Simply create a new `.reg` file with the appropriate locale code.

---

## 🇷🇺 Русский

### 📋 Описание

Этот репозиторий содержит файлы реестра Windows (.reg), которые позволяют быстро изменить язык в игре The Sims 4. Изменение языка осуществляется путем модификации ключа реестра, в котором хранится настройка локали игры.

### ⚠️ Важные предупреждения

- **Всегда создавайте резервную копию** реестра перед внесением изменений
- **Закройте The Sims 4** полностью перед применением изменений реестра
- Эти файлы изменяют реестр Windows - используйте на свой риск
- Для применения изменений могут потребоваться права администратора

### 📦 Требования

- Операционная система Windows
- Установленная игра The Sims 4
- Права администратора на компьютере

### 🚀 Как использовать

1. **Скачайте** файл реестра для нужного языка:
   - `Sims 4 - English.reg` - для английского языка
   - `Sims 4 - Russian.reg` - для русского языка

2. **Закройте The Sims 4**, если игра запущена

3. **Дважды щелкните** по скачанному файлу `.reg`

4. **Подтвердите** действие, когда Windows спросит, хотите ли вы добавить информацию в реестр
   - Нажмите "Да" или "Запустить" при появлении запроса

5. **Перезапустите** игру The Sims 4

6. Игра должна запуститься на выбранном языке

### 🔧 Ручное редактирование реестра (альтернативный метод)

Если вы предпочитаете редактировать реестр вручную:

1. Нажмите `Win + R` и введите `regedit`, затем нажмите Enter
2. Перейдите по пути: `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Maxis\The Sims 4`
3. Найдите параметр `Locale`
4. Дважды щелкните по `Locale` и измените значение на:
   - `en_EN` для английского
   - `ru_RU` для русского
5. Нажмите OK и закройте редактор реестра
6. Перезапустите The Sims 4

### 🌍 Поддерживаемые языки

В настоящее время репозиторий включает:
- Английский (`en_EN`)
- Русский (`ru_RU`)

Вы можете создать файлы реестра для других языков, следуя той же схеме и используя соответствующие коды локали (например, `de_DE` для немецкого, `fr_FR` для французского, `es_ES` для испанского и т.д.)

### ❓ Решение проблем

**Язык не изменился:**
- Убедитесь, что вы полностью закрыли The Sims 4 перед применением файла реестра
- Проверьте, применились ли изменения реестра в редакторе реестра
- Попробуйте перезагрузить компьютер
- Убедитесь, что ваша версия игры поддерживает выбранный язык

**Файл реестра не открывается:**
- Щелкните правой кнопкой мыши по файлу и выберите "Слияние"
- Запустите от имени администратора
- Проверьте, что у вас есть необходимые разрешения

**Игра вылетает или не запускается:**
- Отмените изменения, применив файл реестра с исходным языком
- Проверьте целостность файлов игры через Origin/приложение EA
- При необходимости переустановите игру

### 📝 Лицензия

Этот проект предоставляется как есть в образовательных целях и для удобства. Используйте на свой риск.

### 🤝 Вклад в проект

Не стесняйтесь вносить свой вклад, добавляя поддержку других языков! Просто создайте новый файл `.reg` с соответствующим кодом локали.
