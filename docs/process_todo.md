<h3>Zastosowane i proponowane testy</h3>

Zaprojektowane testy jednostkowe odpalane sa automatycznie za pomoca TravisCI.

Dodatkowo mozna napisac testy UI za pomoca Selenium. Przy ich wiekszej ilosci, ze wzgledu na czas ich wykonania, warto zaplanowac ich uruchomienie w nocy.

Opcjonalne jest dodanie testow wydajnosci, kiedy aplikacja jest juz wdrozona na serwerze klienta. Mozna je wykonac za pomoca JMeter, konfigurujac przykladowo ilosc zapytan w okreslonym czasie.

Korzystne moga byc takze smoke testy, po wdrozeniu aplikacji na heroku.
