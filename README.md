
# ODL APP

An electronic version of the paper equivalent of the Personal Flight Log (ODL), which spits out a ready-made monthly (daily) and annual summary for us.

The application is designed for UAV pilots and sensor operators.

## Features
TBD
- System: Win (.exe) & Android (biblioteka do określenia)
- PYTHON + TBD: PYTHON + KIVY/FLET/JAVA
- GUI: TBD


## Roadmap PL
- Zapisywanie do bazy danych 
- Zapisywanie dla kilku użytkowników? => Wybór użytkownika
- Podsumowanie dzienne
- Podsumowanie roczne?
- Wprowadzenie aktualnego nalotu (budowanie profilu użytkownika)
- Wprowadzenie dopuszczeni i DAT WAŻNOŚCI => Przypomnienia

    - Dopuszczenia
    -	Badania
    -	Egzaminy
    -	Wiedza stosowana
    -	Klasy pilota
    -	...?
   

- Przypomnienia
    -	 widget / background services
    -	Po otwarciu aplikacji na ekranie głównym

- Oddzielne okno dla „przeglądu użytkownika” tj. zbliżające się egzaminy, wychodzące dopuszczenia, aktualizowane na podstawie wprowadzanych lotów
- Zakładka / guzik „WPROWADŹ (DODAJ) LOT” – odsyłacz do funkcji / innego widoku
- Dostosowywanie do rozdzielczości ekranu [okna] – przypięcie widgetów Density independed pixel
- Przełączanie trybu jasny/ciemny
- Tryb pełnoekranowy
- Różne platformy



## Input PL

- Data (preferowany widget z kalendarzem / suwaki (zegary) dla dnia; miesiąca; roku)
Typ statku powietrznego (ustawienie domyślne[ostatnio wprowadzany] + rozwijana lista z predefiniowanymi typami)
- Funkcja (rozwijana lista lub przełącznik P/PA; W ustawieniach aplikacji wybrana opcja PILOT lub SENSOR OPERATOR = mniej opcji podczas korzystania)
- NR ćwiczenia (opisy tekstowe ćwiczeń? Wybór z listy + wybór wielokrotny, ograniczenia na podstawie wybranej funkcji)
- Warunki atmosferyczne (opisowo z komórkami do wprowadzenia danych liczbowych lub tekstowych [cavoc] (najpewniej z „palca”)
- Pora dnia (uwzględnienie godziny wschodu zachodu słońca do obliczeń?)
- Liczba lotów (zegarek z guzikami +/- lub z palca
- Czas + wybór [VLOS; BVLOS; etc.]
- Lot z uzbrojeniem (collapsed – po zaznaczeniu pokaże się pole do wypełniania) 

## Output PL
- „Wyplucie” tabeli – wzór ODL
    o	   Wszystkie dane wejściowe
  
- Podsumowanie tekstowe
    o	Nalot miesięczny całkowity + ilość lotów
  
    o	Dzień
  
    o	Noc
  
    o	PIC
  
    o	Instruktor?
  

## Sketch

![App Screenshot](/SKETCH.png)


## Authors

- [@Whigru](https://github.com/Whigru)
- [@BenQis](https://github.com/BenQis)

