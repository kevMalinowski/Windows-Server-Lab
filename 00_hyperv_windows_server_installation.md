
# Schritt 0: Windows Server 2022 Installation in Hyper-V

Bevor Rollen wie Active-Directory eingerichtet werden können, muss ein Basis-Betriebssystem in einer Virtuellen Umgebung aufgesetzt werden. 

## Schritt 1: Erstellung der VM (Spezifikationen) 

Beim erstellen der VM ist der Name frei wählbar, bevorzugter Weise sollte ein Name gewählt werden, der zum installierten System passt, für eine leichtere Übersicht!

Beispiel: Windows Server 2022 / Domain-Controller

1) **Generation** : Generation 2 (Wichtig für UEFI und Sicherheitsfeatures wie Secure Boot) 
2) **Speicher zuweisen** : 4096 MB (Dynamischen Arbeitsspeicher sollte eingestellt werden!)
3) **Netzwerk konfiguration** : Default Switch wenn eine Internetverbindung benötigt wird, anonsten reicht der Private Switch für die Kommunikation innerhalb des Netzwerks.
