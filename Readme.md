**Projekt sieci wykonał Paweł Janowski i Dawid Dereszkiewicz**  

**Przeznaczenie:** 

Sieć jest przeznaczona dla kancelarii prawnej. Użytkownikami sieci są pracownicy kancelarii  

**Lokalizacja i Topologia Fizyczna:** 

Firma zlokalizowana jest w centrum Gdańska. 

Firma znajduje się w jednym budynku i obejmuje parter oraz piętra: 1,2,3 Parter: 

Na parterze znajduje się serwerownia 

I piętro: 

Na I pierwsze swoje biuro ma zastępca prezesa. Znajduje się tam również dział księgowości. 

II piętro: 

Na drugim piętrze znajduje się biuro prezesa. 

III piętro: 

Na III piętrze znajduje się główna sala biurowa oraz dział firmy „Human resources” **Sieć składa się z** 

-4 routerów  

-6 switchy 

-1 bezprzewodowego punktu dostępu 

-16 komputerów 

-1 serwera DNS/FTP/HTTP 

-4 drukarek 

-2 laptopów 

-3 smartphonów  

**Usługi Sieciowe:** 

DNS- Tłumaczy adres lab.ug na adres IP serwera świadczącego usługi FTP i HTTP (192.168.7.2) 

FTP- Przechowywanie plików na serwerze FTP pod adresem lab.ug, można się do niego zalogować za pomocą loginu cisco i hasła cisco  

http- Wyświetlanie strony internetowej pod adresem lab.ug 

Połączenia wewnątrz sieci- każdy host w dowolnej podsieci ma możliwość połączenia się z innym hostem z dowolnej podsieci. 

Bezprzewodowy punkt dostępu wi-fi (niestety przez ograniczenia PT kiedy ustawimy telefonom stałe ip po ponownym uruchomieniu symulacji ich adres jest zapominany) 

**Adresacja IP:** 

Każde urządzenie posiada ręcznie skonfigurowane statyczny adres IP 



|Urządzenie |IP |Brama Domyślna |Maska |
| - | - | - | - |
|PC Prezes |192.168.1.2 |192.168.1.1 |255.255.255.0 |
|PC1 |192.168.1.3 |||
|Drukarka Prezesa |192.168.1.4 |||
|Laptop 1 |192.168.1.5 |||
|PC2 |192.168.2.2 |192.168.2.1 ||
|PC3 |192.168.2.3 |||
|Drukarka  |192.168.2.4 |||
|Laptop 2 |192.168.2.5 |||
|SB4 |192.168.3.2 |192.168.3.1 ||
|SB3 |192.168.3.3 |||
|SB2 |192.168.3.4 |||
|SB1 |192.168.3.5 |||
|Drukarka SB |192.168.3.6 |||
|HR1 |192.168.4.2 |192.168.4.1 ||
|HR2 |192.168.4.3 |||
|HR3 |192.168.4.4 |||
|HR4 |192.168.4.5 |||
|Drukarka HR |192.168.4.6 |||
|K1 |192.168.5.2 |192.168.5.1 ||
|K2 |192.168.5.3 |||
|K3 |192.168.5.4 |||
|Smartphone 1 |192.168.6.2 |192.168.6.1 ||
|Smartphone 2 |192.168.6.3 |||
|Smartphone 3 |192.168.6.4 |||
|UG |192.168.7.2 |192.168.7.2 ||
|Administrator |192.168.7.3 |||
**Routing:** 

Routing jest statyczny, skonfigurowany zostały ręcznie **Zabezpieczenia:** 

Każdy router i przełącznik ma ustawione MOTD, hasło do trybu  użytkownika (ang. User Exec Mode) oraz trybu uprzywilejowany (ang. Privileged Exec Mode) , hasła  są zaszyfrowane, bezprzewodowy punkt dostępu posiada hasło WPA2 (password) 
