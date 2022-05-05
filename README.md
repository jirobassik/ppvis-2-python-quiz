# Сборник тестов по языку Python
Сборник тестов в виде фрагментов кода, для которых надо указать, что будет выведено на экран и объяснить почему. 

## Требования к тестам
- Тест представляется атомарный фрагмент, не зависящий от других фрагментов
- Тест должен выводить на экран информацию, которая и является целью проверки. Желательно одну строку
- Кроме вопроса "что будет выведено на экран?", тестируемому может задаваться вопрос "почему?" для проверки его знаний
- Тест должен проверять один элемент знаний
- Тест должен быть направлен на базовые возможности языка Python
- Каждый тестовый фрагмент должен сопровождаться:
    - правильным ответом
    - набором тэгов - классификация теста, первый тэг является основным

## Формирование тэгов
- идентификатор тэга пишется на английском
- терминологию нужно сверять с официальной документацией, с глоссарием https://docs.python.org/3/glossary.html
- тэги могут быть вложенными
- тэги обозначают какие области знаний затрагиваются в тестовом фрагменте
- порядок записи тэгов: по значимости
- [список тэгов](TAGS.md), он может пополняться

## Формат записи теста
В фигурных скобках {} подставляемые фрагменты.

<code>
```python

{code_fragment}

\```

Output: `{output}`

Tag: {tag_list}

\---
</code>
