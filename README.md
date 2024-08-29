# Address Book Cleaner

This script takes a CSV file containing a list of contacts and processes it to clean and unify the data. The main features are:

1. Formatting phone numbers to the standard format +7(999)999-99-99 ext.9999.
2. Merging first name, last name, and middle name into a single full name field.
3. Identifying and merging duplicate contacts based on similar names.
4. Saving the processed data to a new CSV file.

## Usage

1. Place the phonebook_raw.csv file containing the raw contact data in the same directory as the script.
2. Run the script using Python.
3. The processed data will be saved to a new file named phonebook.csv.

## Requirements

- Python 3.x
- Standard Python libraries: csv, re, pprint, difflib

## License

This project is licensed under the [MIT License](LICENSE).

README.md (Russian)

# Очиститель адресной книги

Этот скрипт обрабатывает CSV-файл, содержащий список контактов, для очистки и унификации данных. Основные возможности:

1. Форматирование номеров телефонов в стандартный формат +7(999)999-99-99 доб.9999.
2. Объединение имени, фамилии и отчества в одно поле полного имени.
3. Определение и объединение дублирующихся контактов на основе сходства имен.
4. Сохранение обработанных данных в новый CSV-файл.

## Использование

1. Разместите файл phonebook_raw.csv с исходными контактными данными в той же директории, что и скрипт.
2. Запустите скрипт с помощью Python.
3. Обработанные данные будут сохранены в новый файл с названием phonebook.csv.

## Требования

- Python 3.x
- Стандартные библиотеки Python: csv, re, pprint, difflib

## Лицензия

Этот проект распространяется под [Лицензией MIT](LICENSE).
