
## Теория

- CS
	- [[Сортировки]] (Quicksort pseudocode)
	- [[{TODO} Дерево||Деревья]] TODO
	- [[{TODO} Хэширование||Хэширование]] TODO
- Web
	- Сетевые протоколы
- Java
	- Garbage Collectors
	- [[Многопоточка||Multithreading]]
		- [[Синхронизация потоков||Synchronised]]
		- [[Volatile||Volatile]]
		- [[{TODO} Атомики||Atomics]] TODO
		- [[Локи||Locks]] TODO
- Hibernate
- Spring
	- Bean Scopes
	- RestController / Controller / GetMapping
	- Spring Data
- DB
	- Индексы
		- Составные
		- Какие проблемы решают
		- Как лучше построить
	- Уровни изоляции
- Kafka
	- Сколько партиций может быть?
	- Обеспечение порядка чтения
	- Какие есть типы ASC?
	- Батч чтение
- System design
	- Logging System Design


## Задачки

- Написать библиотеку книги/юзеры, 
	- Потокобезопасность
	- Если книга на руках – встать в очередь
	- Вернуть книгу
- Как работать с пейментами если нельзы использовать Serealizable, но нужно поддерживать консистентность. 
	-  Ответ: использовать оптимистик локи
- Задачка про медленный запрос. Шаги