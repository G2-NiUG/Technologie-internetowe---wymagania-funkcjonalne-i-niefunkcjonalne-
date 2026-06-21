# Technologie-internetowe-wymagania-funkcjonalne-i-niefunkcjonalne

Opis projektu:
Celem rozwiązania jest stworzenie profesjonalnego rozwiązania do obróbki komercyjnych materiałów wideo z pomocą rozwiązań Microsoft Fabric. 

Interesariusze:
Administrator systemu
Klient i osoby przydzielone przez niego do projektu

Wymagania funkcjonalne:
WF-01	System umożliwia import materiałów wideo, obrazów oraz audio.
WF-02	System umożliwia edycję materiału na osi czasu z wykorzystaniem wielu ścieżek.
WF-03	System umożliwia dodawanie efektów wizualnych, przejść i napisów.
WF-04	System umożliwia korekcję kolorystyczną oraz edycję dźwięku.
WF-05	System pozwala na korzystanie z przygotowanych szablonów.
WF-06	System zapisuje historię zmian i umożliwia przywrócenie wcześniejszej wersji projektu.
WF-07	System umożliwia eksport projektu do wybranego formatu i rozdzielczości.
WF-08	System umożliwia pracę wielu osobom jednocześnie nad projektem. 
WF-09	System automatycznie zapisuje postęp pracy oraz wykonuje kopie zapasowe.

Wymagania niefunkcjonalne:
WN-01	System powinien uruchamiać się w czasie nie dłuższym niż 10 sekund.
WN-02	System powinien automatycznie zapisywać projekt co maksymalnie 5 minut.
WN-03	System powinien obsługiwać jednoczesną pracę minimum 10 użytkowników na jednym projektem.
WN-04	System powinien automatycznie wykrywać plagiat oraz treści nieodpowiednie i zgłaszać je do kontroli.
WN-05 Wszystkie przesyłane dane powinny być szyfrowane. 
WN-06	Interfejs powinien umożliwiać użytkownikom obsługę za pomocą skrótów klawiszowych.
WN-07	System powinien działać na zarówno systemach Windows i macOS.

Możliwe technologie:
FFmpeg - obróbka wideo 
Python - backend aplikacji
React - frontend aplikacji
Microsoft SQL Server - baza danych
Azure AI Services - funkcje sztucznej inteligencji w aplikacji


Przykładowe komponenty Microsoft Fabric: 
OneLake - przechowywanie danych o projektach, klientach, logi i inne statystyki
Data Factory - automatyczne importowanie logów z aplikacji, synchronizowanie danych z magazynem plików, 
Power BI - tworzenie dashboardów z projektami, danymi technicznymi, danymi finansowymi
Copilot in Fabric - wsparcie sztucznej inteligencji w projekcie, tworzenie 


