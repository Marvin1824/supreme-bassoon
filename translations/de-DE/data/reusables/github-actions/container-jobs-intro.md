Das Konfigurieren von Aufträgen für die Ausführung in einem Container vereinfacht die Netzwerkkonfigurationen zwischen dem Auftrag und den Dienstcontainern. Docker-Container im gleichen benutzerdefinierten Bridge-Netzwerk exponieren gegenseitig alle Ports, sodass Du keinen der Servicecontainer-Ports dem Docker-Host zuordnen musst. Mit der im Workflow konfigurierten Kennzeichnung kannst Du vom Auftrags-Container her auf den Dienst-Container zugreifen.