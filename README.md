# DOWIS
Donnjer Weather and Information System

Das DOWIS besteht aus drei Kernkomponenten:

- Der Sensor Client
- Der REST-API Server
- Der Display Client

##Sensor Client

Der Sensor Client erfasst Wetterdaten und liefert diese an den REST-API Server

##REST-API Dienst

Der REST-API Server empfängt Daten des Sensorclients und speichert diese in eine Datenbank.
Er ist die zentrale Anlaufstelle für alle Display-Clients.

##Display Client

Der Displayclient bezieht relevante Daten vom REST-API Server und stellt diese Grafisch dar.
