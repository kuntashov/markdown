**Готовая реализация markdown от EvilBeaver https://github.com/oscript-library/markdown**

# Парсер Markdown на языке 1С

Является 1С-реализацией популярного php-парсера [Parsedown](https://github.com/erusev/parsedown) (https://github.com/erusev/parsedown).

### Пример

```bsl
	Маркдаун = Новый Markdown;
	ТекстХтмл = Маркдаун.Преобразовать("*Привет, Мир!*");
	Сообщить(ТекстHTML);
	// <p><em>Привет, Мир!</em></p>
```


## Текущий статус

В настоящий момент работа над парсером только начата и исходный код доступен только в devel-ветке.
