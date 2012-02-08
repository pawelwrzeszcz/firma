Skrypty wstawiają przelewy do ZUS i US w interfejsie bankowości elektronicznej WBK https://www.centrum24.pl/centrum24-web/home.

# Wymagania

Selenium IDE + Firefox

# Instrukcje
 # Na podstawie szablonu user-extensions.js.template stwórz plik user-extensions.js z odpowiednimi wartościami.
 # Dodaj go jako rozszerzenie w Selenium IDE (patrz http://saucelabs.com/blog/index.php/2010/03/selenium-tip-of-the-week-parametrizing-selenese-tests/)
 # Zaloguj się do WBK i uruchom skrypty.

# Ważne:
 * Skrypty uruchom z prędkością bliższą 'slow' niż 'fast', inaczej pojawią się błędy walidacji przy wstawianiu przelewów.
 * Skrypty mają wpisane na sztywno rachunek, z którego mają być pobrane środki oraz nazwy urzędów skarbowych. Musisz je podmienić - pull request parametryzujący te zmienne mile widziany ;)
