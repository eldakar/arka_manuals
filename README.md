# arka_manuals

## Instalacja i Profil

![image](https://github.com/user-attachments/assets/0e8eeab1-a114-4381-b88e-577df5b5a225)

![image](https://github.com/user-attachments/assets/aeba1710-d0e4-4bd6-abd6-1d9bdd14c18e)

Logujemy do postaci i wpisujemy `map update`

![image](https://github.com/user-attachments/assets/8acfb2d2-b6b1-4fdd-b790-e3def6b56e4a)

I teraz robimy kroki wg dzordzyka, ktore znajduja sie tutaj - ale streszcze `https://github.com/tjurczyk/arkadia/blob/master/README.md`

### Komenda `lua installPackage("https://github.com/tjurczyk/arkadia/releases/latest/download/ArkadiaScriptsInstaller.xml")`

![image](https://github.com/user-attachments/assets/c33f31f8-740e-4eca-8adf-8d35b5dfaf03)

Klikamy na 'pobierz mape'

![image](https://github.com/user-attachments/assets/738a50ae-f811-45a8-ae8a-83a141234617)

### Komenda `/aktualizuj_skrypty`

![image](https://github.com/user-attachments/assets/bfafe480-aabf-4ed0-9ddf-b42bc4ffdc66)

### Restart + Logowanie

Pojawi sie to okno, klikamy na `utworz konfiguracje`

![image](https://github.com/user-attachments/assets/1efabfa4-2c9f-42a7-8555-b69cadac85b3)

W taki oto sposob utworzony zostal plik Eldakar.json

![image](https://github.com/user-attachments/assets/82e74cf2-99ae-4557-b229-d22d3292c1fa)

### Komenda `/konfiguracja`

![image](https://github.com/user-attachments/assets/7aa7b299-d6bb-4c8b-81a9-ca72c9c3c576)

Klikamy na `/pobierz baze tutaj`, Zainstaluj numeryczna + zainstaluj cltr+alt chodzenie

### Restart + Logowanie 

Na tym etapie nalezy sprawdzic czy wszystko jest ok. Powinna dzialac klawiatura numeryczna - powinna sie mapka przesuwac przy poruszaniu.

### Komenday `/kondycje` 

wyswietli okno kondycji - naprawdopodobniej pod mapa po prawej stronie okna - ktore trzeba rozsunac

![image](https://github.com/user-attachments/assets/3e4a6fd4-b824-4c47-bd20-8390e689c686)

## MCpaczka

Sciagamy plik

![image](https://github.com/user-attachments/assets/85dfb1ac-5b7e-4dff-801e-4f54a86d8759)

Nastepnie wpisz `/lua getMudletHomeDir()` i znajdz ten katalog w explorerze.

Wylacz mudlet

Przejdz do podkatalogu /plugins i rozpakuj tam paczke - tak aby pliki lua byly bezposrednio w katalogu arkadia-mc

![image](https://github.com/user-attachments/assets/dfa88f78-6d54-4773-b434-e4433179c60d)

### Zaloguj na arke

Zobaczysz komunikaty o zmianach w konfiguracji

![image](https://github.com/user-attachments/assets/343dd29d-14cc-48a3-b7fe-c9f40a7510db)

## SPRAWDZ CZY KOMENDA `/mc` odda Ci liste opcji - jesli tak to instalacja jest poprawnie ukonczona

## Mozesz teraz skopiowac swoj stary Eldakar.json do pliku na wylaczonym mudlecie


### Jak naprawic sciagniecie bazy

### Komenda `/lua db:close("people")`
### Komenda `/pobierz_baze`

![image](https://github.com/user-attachments/assets/0aaaeedc-44ea-4574-b7de-dad0a69f5ab6)



