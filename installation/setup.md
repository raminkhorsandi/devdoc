---
title: Konfiguration
weight: 30
---

# OPUS 4 Konfigurieren

<p class="note">Dieser Teil der Anleitung ist noch nicht fertig und wird bis zum Release weiter ergänzt. Die alte
Anleitung zum manuellen Einrichten einer OPUS 4 Instanz ist im Prinzip weiterhin gültig.</p>

Das Setup Skript führt die notwendigen Schritt aus, um eine OPUS 4 Instanz einzurichten.

## Datenbank anlegen

Es wird MySQL verwendet. Für das Anlegen der Datenbank fragt das Skript nach folgenden Informationen:

* Name der Datenbank
* Name des OPUS 4 Admin Nutzers
* Password
* Name des OPUS 4 Applikation Nutzers
* Host für MySQL
* Port für MySQL
* Name des MySQL Root Nutzers

## Apache Webserver konfigurieren

## Apache Solr einrichten

Solr wird auf dem selben System in einem separten Nutzer Account installiert. Soll Solr auf einem anderen System laufen
können Sie dort das Solr Setup Skript verwenden.

## Testdaten hinzufügen

**TODO** Testdaten sollten ein optionales Paket sein
