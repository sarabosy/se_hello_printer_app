Praca nad kodem przebiega w lokalnym srodowisku deweloperskim. Kazda z modyfikacji lub nowych funkjonalnosci wprowadzona zostaje do ogolnego repozytorium znajdujacego sie na githubie. Nowy commit powoduje aktualizacje statusu projektu w TravisCI.

Za jego posrednictwem nastepuje automatyczne uruchomienie testow, lintera oraz, po udanym zbudowaniu aplikacji, wdrozenie jej na heroku.
Za pomoca serwera statuscake monitorujemy czy aplikacja postawiona za pomoca heroku jest nadal online i nie wystapily bledy.

Dodatkowo, TravisCI tworzy obraz dockera i umieszcza aplikacje na serwerze klienta.

Calosc procesu budowy oprogramowania przedstawiono na schemacie ponizej:

![Alt text](https://github.com/sarabosy/se_hello_printer_app/blob/master/docs/se_hello_printer.png "CD diagram")
