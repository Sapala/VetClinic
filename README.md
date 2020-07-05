# VetClinic
Aby uruchomić projekt lokalnie należy:
1) Utworzyć pustą bazę danych  o nazwie VetClinic na swoim lokalnym serwerze
2) Uruchomić skrypt SQL który znajduje się w projekcie VetClinic.Data w katalogu Helpers
    Dzięki temu skryptowi baza danych uzyska właściwą strukturę i zostanie zapełniona danymi testowymi 
3) W projekcie VetClinic.Intranet i w projekcie VetClinic.PortalWWW w pliku appsettings.json należy zmienić connection string (zmienić nazwę serwera).
4) Poprzez konsole menadzera pakietów zaaktualizować baze danych poleceniem update-database
