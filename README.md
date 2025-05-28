# ppy12c-devops

## Screenshot z uruchomionej aplikacji
[![1.png](https://i.postimg.cc/dtS8F4VS/1.png)](https://postimg.cc/CzkZHCDj)

## Screenshot z przejścia testu GitHub Actions
[![2.png](https://i.postimg.cc/SR1zyxkz/2.png)](https://postimg.cc/CnDK7YZF)

## Krótki opis

W ramach mini-projektu DevOps wykonałem pełny przepływ pracy DevOpsa na bazie prostej aplikacji webowej.

1. Przygotowałem prostą aplikację z użyciem Flask.
2. Utworzyłem plik ```Dockerfile```, która umożliwia budowanie kontenerów Docker.
3. Dokonałem lokalnego deploymentu za pomocą Dockera.
4. Dodałem endpoint ```/health```, który umożliwia sprawdzenia, czy aplikacja działa poprawnie.
5. Skonfigurowałem GitHub Actions, które testują aplikację automatycznie po każdym ```pushu``` do gałęzi ```main```. 
