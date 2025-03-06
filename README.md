# Quiz Muzyczny

## Opis projektu
Projekt zrealizowany na studia na przedmiot programowanie niskopoziomowe. Gra muzyczna napisana w języku C z użyciem biblioteki CSFML. Zawiera ona różne funkcje, takie jak tabela wyników, inicjalizacja gry, nawigacja w menu oraz obsługa pytań.

## Cel projektu
Celem projektu jest stworzenie gry muzycznej, która pozwala na interakcję użytkownika z różnymi elementami gry, takimi jak pytania muzyczne, tabela wyników oraz zapisywanie stanu gry.

## Jak uruchomić aplikację
1. Otwórz Visual Studio i załaduj plik `Music.vcxproj`.
2. Zbuduj rozwiązanie, wybierając odpowiednią konfigurację (Debug lub Release).
3. Uruchom plik wykonywalny wygenerowany w katalogu `x64/Debug` lub `x64/Release`.

## Wymagania systemowe
- System operacyjny: Windows
- Visual Studio z zainstalowanym kompilatorem C++
- Terminal lub konsola

## Struktura Projektu

- **gameLogic.c/h**: Zawiera główną logikę gry.
- **initialization.c/h**: Odpowiada za inicjalizację komponentów gry.
- **menu.c/h**: Zarządza menu gry.
- **questions.c/h**: Obsługuje pytania używane w grze.
- **showLeaderboard.c/h**: Wyświetla tabelę wyników.
- **structs.h**: Definiuje struktury używane w całej grze.
- **fonts/**: Zawiera pliki czcionek używane w grze.
- **x64/**: Zawiera skompilowane pliki DLL i obiekty dla debugowania i wydania.

## Dodatkowe Pliki

- **background.jpeg, background2.jpeg**: Obrazy tła używane w grze.
- **leaderboard.txt**: Przechowuje dane tabeli wyników.
- **questions.txt**: Zawiera pytania używane w grze.
- **saved_game.txt**: Przechowuje stan zapisanej gry.

## License

This project is under the MIT License - see the [LICENSE](./LICENSE) file for details.