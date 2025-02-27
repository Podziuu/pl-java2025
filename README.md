# PŁ: Zaawansowane Zagadnienia Programowania w Javie - Edycja 2025

## Zaliczenie - zarys 2025

- Projekt grupowy: od 3 do 6 osób (brak odstępstw)
- Tematyka realizowanego projektu: dowolna
- Elementy, które powinny znaleźć się końcowym projekcie i podlegają ocenie:
    - Współpraca z repozytorium Git (dowolnie wybrany darmowy hosting według upodobań, na przykład: Github, Gitlab lub Bitbucket)
    -   Aktywność w realizacji projektu: 
	    - *pull requesty* wraz z *code review* wewnątrz zespołu 
	    - *githubowy pulse* lub inne narzędzie pokazujące ciągłość pracy podczas semestru
	    - podział zadań przy implementacji funkcjonalności projektu poprzez *board projektowy* (Jira, Trello,...)
	  
    - Praktyczna implementacja i wdrożenie rozwiązań, tematów, narzędzi prezentowanych podczas zajęć (nie muszą być wszystkie, ok. 60% jest ok?)
		 - [ ] Aplikacja oparta o **Spring (Boot) Framework** 
		 - [ ] Integracja z zewnętrznym zasobem po **REST** z wykorzystaniem publicznego API (np.: https://github.com/public-apis/public-apis) wraz z wykorzystaniem (przetworzeniem) otrzymanych danych 
		 - [ ] Zaprojektowanie własnego API z wykorzystaniem biblioteki **OpenAPI** wraz z drugą aplikacją, która konsumuje udostępnione API. Klient będzie wykonywał zapytania HTTP do serwisu i analizował otrzymane dane.
		 - [ ] Architektura mikroserwisowa z wykorzystaniem **Spring Cloud Eureka**, umożliwiająca rejestrację i wykrywanie usług. Aplikacja będzie składała się z minimum dwóch mikroserwisów, które będą się wzajemnie komunikowały przy użyciu Spring Eureka jako serwera rejestracji usług.
		 - [ ] Wykorzystanie **Spring Cloud Config Server**, który centralizuje zarządzanie konfiguracją dla wielu mikroserwisów. Dzięki temu, wszystkie serwisy w systemie mogą korzystać z jednej wspólnej konfiguracji, przechowywanej w centralnym miejscu (np. w plikach YAML na oddzielnym repozytorium Git), a zmiany w konfiguracji są natychmiastowo propagowane do aplikacji.
		 - [ ] Wykorzystanie **Keycloak** lub **Spring Authorization Server** (lub inny nieprezentowany podczas zajęć)  jako systemu zarządzającego autoryzacją i autentykacją użytkowników oraz/i serwisów.
		 - [ ] Aplikacja powinna być zaprojektowana w taki sposób, aby jej komponenty zostały odpowiednio przetestowane przy użyciu różnych typów testów, np. **jednostkowych (unit tests)**, **integracyjnych (integration tests)** oraz **testów BDD (Behavior Driven Development)**. Celem jest zapewnienie wysokiej jakości kodu, wykrywanie błędów na wczesnym etapie oraz zapewnienie, że aplikacja działa zgodnie z oczekiwaniami użytkowników końcowych.
		 - [ ] Aplikacja wykorzystująca ostatnie nowości w **JDK** (np. Local-Variable Type Inference, Text Blocks, Sealed Classes, Pattern Matching dla instanceof, Virtual Threads, Records, Structured Concurrency)
		 - [ ] ...
		 - [ ] ...
		 - [ ] ...
		 - [ ] ...
    - UI oraz UX nie mają znaczenia, podczas prezentacji można użyć narzędzi typu Swagger albo Postman  
    - Unikanie typowych aplikacji Create-Read-Update-Delete (CRUD)


## Propozycje tematów 2025
- IntelliJ
- JDK Updates (9~23)
- Refleksja w Javie
- Cucumber (BDD) + AssertJ
- Integracja z modelami AI przez http + biblioteki do AI w Javie
- Statyczna analizę kodu
- Współbieżność
- Interoperacyjność Javy np. z Pythonem
- Spring 101: Podstawowe zagadnienia, MVC, RestController, HttpClient, JPA
- Spring 102: Security
- Spring 103: Spring proxy-based AOP + AspectJ + Spring aspectj-based AOP
- Spring 104: Tranzakcje, mechanizm Retryable, OpenAPI
- Mikroserwisy 101: praktyczne podstawy budowy systemu z wykorzystaniem REST i Spring Cloud Eureka  
- Microserwisy 102: zaawansowane tematy związane z wykorzystaniem narzędzi do zarządznia autoryzacją i autentykacją użytkowników i serwisów (Keycloak vs Spring Authorization Server)
- Mutation testing (pitest)
- From Java to Go(lang)



## Ramowy plan zajęć
 Lp | Temat | Data       | Prowadzący | Uwagi                                                                                                  
----|---------------------|------------|------------|-------------
 1  | Wprowadzenie + IntelliJ | 03.03 | MD |
 2  | JDK Updates (od wersji 9 do wersji 23/24) | 10.03 | ZN |
 3  || 17.03 ||                                        
 4  | Przedstawienie pomysłu na projekt | 24.03 ||                                             
 5  || 31.03 ||
 6  || 07.04 ||
 7  || 28.04 ||
 8  || 05.05 ||
 9  || 12.05 ||
 10 || 19.05 ||
 11 | Sprawdzanie postępu realizacji projektu | 26.05 ||                                              
 12 || 02.06 ||
 13 || 09.06 ||
 14 || 16.06 ||
 15 | Finalne przedstawienie zrealizowanego projektu | 23.06 ||
