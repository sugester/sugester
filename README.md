# Bilbioteki Sugestera
Opis API i bibliotek do [Sugester](http://sugester.pl)


## API

Sugester posiada API JSON, które umożliwia zarządzanie wszystkimi danymi (np. zadaniami, klientami, dealiami, projektami, e-mailami itp). 
Tu znajduje się opis [API Sugestera](https://github.com/sugester/API)

## Zbieranie danych o działaniach klientów

Sugester umożliwia zbieranie danych o działaniach Twoich klientów na Twoich stronach www, aplikacjach i systemach. 
Wystarczy, że zainstalujesz odpowiednia bibliotekę na Twojej stronie www (kod Javascript) lub wewnąrz Twojej aplikacji (aktualnie dostępne są biblioteki do języków PHP i Ruby). Na karcie klienta w Sugesterze zaczną pojawiać się wszystkie akcje, które wykonał dany klient. Na podstawie wykonanych akcji możesz wtedy definiować automatyczne działania, automatycznie nadawać scoring klientowi itp.

* Tu znajduje się opis [biblioteki PHP Sugestera](https://github.com/sugester/sugester_php)
* Tu znajduje się opis [biblioteki Ruby Sugestera](https://github.com/sugester/sugester_ruby)
* Tu znajduje się opis [biblioteki Javascript Sugestera](https://github.com/sugester/sugester_javascript)

UWAGA: dane o kientach można zbierać także przez API, jednak wymienione wyżej biblioteki są zoptymalizowane do przyjmowania setek tysięcy danych dziennie i są zalecane przy bardzo dużej ilości zbieranych danych przysyłanych do Sugestera z zewnętrznych źródeł.

## Szablony

Sugester umożliwoa definiowanie własnych szablonów stron, templatów e-maili i własnych wydruków. 
Tu znajduje się opis [szablonów Sugestera](https://github.com/sugester/szablony)

Więcej informacji znajduje się na [stronie pomocy Sugestera](http://pomoc.sugester.pl)
