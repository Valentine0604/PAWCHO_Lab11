# LEMP Stack z Docker Compose

Zadanie demonstrujące użycie Docker Compose do uruchomienia stosu LEMP (Linux, Nginx, MySQL, PHP) wraz z phpMyAdmin.

--------------------------------------------------------------------------------------------------------------------

<b>Struktura projektu:</b>
<ul>
	<li>docker-compose.yml - główny plik konfiguracyjny Docker Compose</li>
	<li>nginx/default.conf - plik konfiguracyjny dla Nginx</li>
	<li>www/index.php - przykładowy plik PHP</li>
</ul>

<b>Uruchomienie kontenerów:</b><br>
```
docker-compose up -d
```
Wynik:
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/c699f103-f66f-4e17-8dff-63ea4abdaab9)

<b>Sprawdzenie uruchomionych kontenerów:</b><br>
```
docker-compose ps
```
Wynik:
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/21f1dbed-5528-4508-a4f9-ea9825faba18)

<b>Zatrzymanie i usunięcie kontenerów:</b><br>

```
docker-compose down
```
Wynik:
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/fde35cfd-d484-449b-9986-d093d8a34205)

<b>Usunięcie wszystkich zasobów, w tym woluminów:</b><br>

```
docker-compose down -v
```
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/e1c62c4c-c44f-4751-a185-47d490406edd)

--------------------------------------------------------------------------------------------------------------------

<b>Testowanie stosu LEMP:</b>

<li>Wyświetlenie strony startowej PHP na porcie 4001:</li><br>

![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/7f21c63c-147e-4b48-b28e-4859e75a2c63)

<li>Wyświetlenie serwera phpMyAdmin na porcie 6001:</li><br>

![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/3f00f17a-ab22-4f45-8b13-6d1765476f3a)
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/1cf4e9ee-7204-4e9c-b89d-3c810057d999)

--------------------------------------------------------------------------------------------------------------------

<b>Inicjalizacja testowej bazy danych i utworzenie tabeli 'cats':</b>

![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/a279db72-290b-4956-ae1d-f3448afecc04)
--------------------------------------------------------------------------------------------------------------------
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/6a108196-a83d-4922-ac31-638c7e3f0dd0)
--------------------------------------------------------------------------------------------------------------------
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/c28d1fe3-86c0-4ca7-a349-c209a1e84107)
--------------------------------------------------------------------------------------------------------------------
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/4502f722-d94f-4cc1-80f3-acfe17ad7d3f)
--------------------------------------------------------------------------------------------------------------------
<b>Wstawianie przykładowych wartości do tabeli 'cats':</b>

![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/f5a87651-b2cd-4a1d-b194-2ef0d11b5952)
--------------------------------------------------------------------------------------------------------------------
![image](https://github.com/Valentine0604/PAWCHO_Lab11/assets/106283972/2bef6568-a787-4a2a-97e7-ede864c72d42)








