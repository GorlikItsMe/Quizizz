# Quizizz Odpowiedzi
## Jak Używać

1. Dołącz do quizu, poczekaj na pierwsze pytanie.
2. Otwórz konsolę, wklej następujący kod:
```ts
fetch("https://raw.githubusercontent.com/Skygoplay/Quizizz/master/skrypt.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
3. Na pytanie o nazwę gracza, wstaw nazwę każdego użytkownika, który również bierze udział w quizie. Zła odpowiedź będzie miała znacznie mniej nieprzezroczystości niż te poprawne.
4. Powtórz kroki 2 i 3 dla każdego pytania.


Jak widać na tym zrzucie ekranu, odpowiedź "" jest prawidłowa
![screenshot](/docs/screenshot_1.png)
