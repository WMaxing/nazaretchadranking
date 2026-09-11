# Nazaret Chad Ranking

Gotowa statyczna strona pod GitHub Pages z Firebase.

## 1. Firebase

Projekt korzysta z istniejącej konfiguracji Firebase zapisanej w `index.html` i `admin.html`.

W Firebase Authentication włącz **Email/Password** i upewnij się, że konto administratora:

`kplatek.2020@gmail.com`

istnieje.

Następnie w Realtime Database wklej zawartość `database.rules.json` jako Rules.

> Ważne: API key Firebase Web SDK może być widoczny w frontendzie. Bezpieczeństwo zapewniają reguły Firebase. Nie wkładaj haseł administratora do repozytorium.

## 2. Pierwszy start

1. Otwórz `index.html` lokalnie albo po publikacji.
2. Wejdź w `admin.html`.
3. Zaloguj się kontem administratora.
4. Kliknij **Importuj startowych 15**.
5. Od tej chwili Chadzi są pobierani z `/chads` w Firebase.

## 3. Dodawanie Chada

W panelu admina uzupełnij nazwę, tytuł, opis, Aura Score i URL zdjęcia, a następnie **Zapisz**.

Nowy Chad pojawi się na stronie głównej.

## 4. GitHub Pages

Wrzuć wszystkie pliki z tego folderu do repozytorium GitHub. W ustawieniach repozytorium wybierz:

**Settings → Pages → Deploy from a branch → main → /(root)**

Po chwili GitHub Pages opublikuje `index.html`.

## 5. Zdjęcia

Panel używa URL zdjęcia, np. linku do obrazka z hostingu. Dzięki temu nie trzeba zapisywać zdjęć bezpośrednio w repozytorium.

## Uwaga

`database.rules.json` to przykładowe reguły dla tego projektu. Przed publicznym uruchomieniem sprawdź je w Firebase Rules Simulator i nie używaj ich w innym projekcie bez dostosowania.
