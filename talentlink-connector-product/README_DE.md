# TalentLink Connector

[TalentLink](https://developer.lumesse-talenthub.com/) ist eine cloudbasierte
Plattform für Personalbeschaffung und Talentakquise von Lumesse (jetzt Teil von
Cornerstone OnDemand). Sie optimiert den Einstellungsprozess, von der
Stellenausschreibung über das Bewerbermanagement bis hin zur Vorauswahl und
Berichterstellung. TalentLink hilft Unternehmen dabei, die Talentakquise
effizient zu verwalten und HR-Prozesse zu automatisieren.

Dieser Konnektor:

-   basiert auf REST- und SOAP-Webservice-Technologien.
-   Sie erhalten Zugriff auf Beispielfunktionen von TalentLink.

## Demo

Rufen Sie den Testprozess auf. Er gibt Ihnen die Testdaten im Protokoll zurück.

## Setup

Bevor Interaktionen zwischen der Axon Ivy Engine und den TalentLink-Diensten
ausgeführt werden können, müssen diese einander vorgestellt werden. Dies kann
wie folgt erfolgen:

1. Erstellen Sie ein TalentLink-Konto `host-name`, `user-name`, `password` und
   `api_key`, um es zu verwenden.

2. Überschreiben Sie die Variablen für `host-name`, `user-name`, `password` und
   `api_key` im Demo-Projekt wie im folgenden Beispiel gezeigt.

```
Variables:

  talentlink-connector:

    host: <myhost>

    username: <myuser>

    # [password]
    password: <mypass>

    apikey: <myapikey>
```


