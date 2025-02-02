up:: [[Разработка ПО]]
tags:: 
source:: 
created:: 2022-10-30 19:07
accociations:: [[машинное обучение]]

- [[Beginners Python Cheat Sheet.pdf]]
- - [GitHub - gto76/python-cheatsheet: Comprehensive Python Cheatsheet](https://github.com/gto76/python-cheatsheet)
	- копия: [[Comprehensive Python Cheatsheet]]

Один из самых популярных фреймворков для автоматизации тестирования [[PyTest]] написан на Python. На этом языке написаны и многие популярные тестовые инструменты, например, [[Robot Framework - Python Open Source automation framework]] (описание сценариев тестирования).

Популярные фреймворки для автоматизации управления инфраструктурой [[SaltStack]] и [[Ansible]] также написаны на Python. Он является идеальным инструментом для автоматизации рутинных задач в системном администрировании.
# Типы данных

## Список
```python
strings = ['Hello', 'world']
numbers = [1, 5, 3, 6, 4]
compound = strings + numbers
compound.append(8)
compound.sort()
first = strings[0]
s = sum(numbers)
```
## Словарь
```python
dictionary = {'cat': 'кошка', 'dog': 'собака'}
print(dictionary['cat'])
countries = {}
countries['Европа'] = ['Австрия', 'Германия', 'Италия']
print(len(countries['Европа']))
countries[0] = 'Hello'
```
# Ввод
```python
name = input('Введите имя: ')
print('Привет', name) # элементы print разделяются пробелом
```

# Links
- [[учебники по Python]]
- [[стартер приложения на Python]]
- [[визуализация данных на Python]]
- [[библиотеки Telegram для Python]]
- [[Numpy]]
### Онлайн-редакторы
- Google Colab
- Kaggle
- Нетология: При написании кода мы используем онлайн-редакторы [replit.com](https://replit.com/) и [pythonanywhere.com](https://pythonanywhere.com/), они запускаются прямо из браузера, устанавливать какой-либо дополнительный софт не потребуется.
## Заметки, где упоминается Python

```dataview
TABLE file.mday as Изменен
FROM [[Python]]
SORT file.mday desc
```
## См. также
- [[Фреймворк для автоматизации тестирования PyTest]]
- [[Robot Framework - Python Open Source automation framework]]
- [[Самые популярные библиотеки Python]]

## Что сделать
- [ ] Изучить pep8 https://pep8.org/ ⏫ 📅 2022-10-26