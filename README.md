Dies ist das Repository für die Edge Computing Software, welche in der wt-online Ausgabe 7/8 im Jahre 2023 mit den Schwerpunkten „Werkzeugmaschinen – Produktionsanlagen, Smart Services, Verfügbarkeit, Produktivitätssteigerung als Service“ erschienen ist.
# Edge Computing Software für den Zerspanungsprozess
## Ermöglichung datenintensiver Innovationen in der Industrie durch Open Data und Open Source

### Abstract
In aktuellen Forschungsprojekten entwickeln Forscher des Instituts für Werkzeugmaschinen und Fabrikbetrieb (IWF) Open-Source Software für Edge Devices. Für die Auslegung der Fertigungs-prozesse werden dabei neben den ingenieurwissenschaftlichen Themen auch die Auslegung der Auswerteelektronik inklusive der Softwareentwicklung adressiert. Der interdisziplinäre Ansatz, einschließlich der Softwarebereitstellung, wird exemplarisch an einem DFG-Projekt zur Prozess-überwachung bei der Drehbearbeitung diskutiert.

Englische Version:

In current research projects, researchers at the Institute for Machine Tools and Factory Management (IWF) are developing open-source software for edge devices. For the design of the manufacturing processes, the design of the evaluation electronics including the software development is addressed in addition to the engineering topics. The interdisciplinary approach, including the provision of software, is discussed using a DFG-project on process monitoring in turning processes as an example.

### Informationen zum Repository

1. In *Aduino_code.ino* ist der Code für den Arduino, sodass dieser mit Python kommunizieren kann.
2. In *Temperaturmessungen* ist eine *Temperaturmessung.exe* Datei zu finden. 
Über diese Datei kann die Software auch ohne eine Python-Installation ausgeführt werden.
Allerdings muss hierfür die *Temperaturmessung.exe* Datei im Verzeichnis *Temperaturmessung* bleiben.
3. In *code* ist der Open Source Code für die Nachnutzung der Software zu finden. Über die *requirements.txt* kann ein zugehöriges Anaconda Enviroment aktiviert werden.

Für einen Einstieg in die erweiterbare Softwareentwicklung für Hardwarekommunikation mit Python empfiehlt sich das Buch [Python for the lab](https://www.pythonforthelab.com/books/).
