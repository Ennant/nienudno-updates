# Nienudno — aktualna wersja i naprawa instalacji

Stały link https://da.gd/nnd948 udostępnia program `Napraw-aktualizacje.exe`. Program pobiera najnowsze podpisane wydanie; nie jest przypisany do numeru jednej wersji.

Naprawa zachowuje światy i obce pliki pulpitu. Stare skróty należące do launchera są archiwizowane, a właściwy skrót wskazuje stały program uruchamiający aktualne wydanie. Zapewniony zostaje także „Zmień tapetę”.

Pierwsze przygotowanie lokalnej sieci wymaga zgody administratora Windows. Chroniony pomocnik odświeża potem ograniczone reguły lokalnej podsieci dla podpisanych wydań; zapora pozostaje włączona.

Od Complete.17 pierwsza konfiguracja nie uruchamia jako administrator pliku z katalogu użytkownika: chroniony host Windows niezależnie sprawdza zatwierdzone bajty po podwyższeniu uprawnień. Poprawnie skonfigurowane wcześniej chronione zadania pozostają obsługiwane; nie jest wymagana ponowna zgoda przy każdym wydaniu.

Od Complete.16 panel dowódcy ma zwarte przyciski misji, grup, pomocy i aktualizacji. „Zastosuj pobraną aktualizację” zapisuje obsługiwaną grę, zamyka ją bez force stop i uruchamia launcher ponownie. Zdalne zastosowanie wymaga tej funkcji na odbiorcy; starsze wydania potrzebują jednego początkowego restartu po aktualizacji. Laptopy muszą być włączone i osiągalne w tej samej sieci.

Complete.17 dodaje „Wydaj aktualizację wszystkim w sieci”: jedna podpisana paczka, równoległe przesłanie przez LAN, bezpieczne zlecenie zastosowania na zgodnych odbiorcach i potwierdzenie zgłoszonej wersji po restarcie. „Wysłano polecenie” nie jest potwierdzeniem wdrożenia. Offline i starsze odbiorniki wymagające początkowego ręcznego restartu są jawnie oznaczone. Laptop instruktora pozostaje otwarty na czas nadzoru wyników.

Ta aktualizacja wymaga istniejącej pełnej instalacji gry. Oryginalny instalator zachowano jako `Napraw-aktualizacje-legacy-r10.exe`. Nie deklarujemy zgodności różnych protokołów Minecraft we wspólnym świecie.

Od complete.24 (updates6) naprawa zostawia na laptopie jedną, najnowszą wersję launchera. Po zainstalowaniu i sprawdzeniu nowej wersji usuwa wyłącznie pliki programów starszych instalacji Nienudno (druga instalacja launchera, launcher z pendrive'a w C:\NienudnyMinecraft, stary „Nienudny Launcher” przez jego własny deinstalator). Zapisane i rozegrane światy ze starszych wersji trafiają do „Zapisanych światów”, pozostałe dane zostają w dotychczasowych folderach. Instalacja, która akurat działa, zostaje i jest porządkowana przy następnej naprawie.

Od complete.25 okno naprawy od razu pokazuje najnowszą opublikowaną wersję, wersję zainstalowaną na tym laptopie i listę nowości (z pliku latest.json w tym repozytorium; o tym, co zostanie zainstalowane, decyduje wyłącznie podpisany kanał stable.json).
