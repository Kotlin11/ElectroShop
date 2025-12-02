# ElectroShop – Aplikacja webowa ASP.NET Core MVC  
Projekt inżynierski

ElectroShop to aplikacja internetowa stworzona w technologii **ASP.NET Core MVC**, przedstawiająca sklep online z elektroniką. Zawiera pełną strukturę aplikacji MVC: model danych, kontrolery obsługujące logikę biznesową, 
widoki Razor odpowiedzialne za prezentację oraz zasoby statyczne.

Projekt został przygotowany jako część pracy inżynierskiej i przedstawia kompletną, działającą aplikację prezentującą produkty, szczegóły, koszyk i informacje o sklepie.


1 Funkcjonalności

Aplikacja zawiera:

- Stronę główną  
- Listę produktów  
- Podstronę szczegółów produktu  
- Możliwość dodawania produktów do koszyka (po stronie klienta)  
- Podstronę "O nas"  
- Podstronę "Kontakt"  
- Layout i wspólne elementy UI  
- Integrację z Bootstrap i jQuery  

2 Technologie

Projekt został zbudowany w oparciu o:

- **ASP.NET Core MVC (NET 6.0)**
- **Razor Views**
- **Bootstrap 5**
- **jQuery**
- **jQuery Validation / Unobtrusive**
- **C#**
- **HTML5 + CSS3**


3 Modele danych

### `Product.cs`

Model reprezentujący pojedynczy produkt w sklepie:

- Id  
- Nazwa  
- Opis  
- Cena  
- URL do zdjęcia  

### `CartItem.cs`

Model pojedynczej pozycji koszyka.


4 Kontrolery

### **HomeController**
- Strona główna  
- Sekcje informacyjne: O nas, Kontakt  

### **ProductsController**
- Lista produktów  
- Szczegóły pojedynczego produktu  

### **CartController**
- Obsługa koszyka użytkownika (sesja / lokalne przechowywanie danych)

5 Widoki

Aplikacja korzysta z:

- **Layoutu `_Layout.cshtml`** – wspólna nawigacja, stopka, dołączenie CSS/JS
- Widoków Razor dla:
  - Home
  - Products
  - Cart
  - Stron informacyjnych


## 🏁 Jak uruchomić projekt?

### 1. Pobierz repozytorium

### 2. Otwórz projekt w Visual Studio  
Kliknij `ElectroShop.sln`.

### 3. Przywróć pakiety NuGet  
Visual Studio zrobi to automatycznie, ale możesz też:


### 4. Uruchom aplikację

przyciskiem **IIS Express** / **Run** w Visual Studio.

### 5. Wejdź w przeglądarce:
http://localhost:5000

6 Cel projektu

Celem projektu było stworzenie w pełni działającej aplikacji sklepu internetowego z elektroniką opartej o wzorzec **Model–View–Controller**, z wykorzystaniem technologii ASP.NET Core.

Aplikacja:

- prezentuje produkty,
- umożliwia ich przeglądanie,
- posiada koszyk,
- demonstruje wiedzę z zakresu programowania webowego,
- stosuje poprawną architekturę aplikacji zgodnie z dobrymi praktykami .NET.


