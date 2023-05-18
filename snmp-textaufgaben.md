# TEXTAUFGABEN

---

## Was versteht man unter Network Management?

Netzwerkmanagement bezieht sich auf die Prozesse, Methoden und Tools, die zur Überwachung, Verwaltung und Wartung eines Computer- oder Telekommunikationsnetzwerks verwendet werden. Es umfasst eine Reihe von Aufgaben, darunter die Konfiguration und Installation von Netzwerkgeräten, die Überwachung des Netzwerkverkehrs, die Fehlerbehebung bei Problemen, die Sicherstellung der Netzwerksicherheit und die Optimierung der Netzwerkleistung. Network Management sorgt für einen reibungslosen Betrieb und hilft, Ausfallzeiten zu minimieren.

---

## Welche Rolle spielen der SNMP-Manager und der SNMP-Agent?

Im Kontext des Simple Network Management Protocol (SNMP) ist der SNMP-Manager ein System, das verwendet wird, um Netzwerkgeräte zu überwachen und zu steuern. Der SNMP-Agent hingegen ist eine Softwarekomponente, die auf dem Netzwerkgerät selbst läuft. Der Agent sammelt Informationen über den Status und die Leistung des Geräts und sendet diese Informationen an den SNMP-Manager. Der Manager kann auch Befehle an den Agenten senden, um Konfigurationsänderungen vorzunehmen oder andere Managementaufgaben auszuführen.

---

## Was ist SNMP? Gehe genauer auf die Neuerungen in Version 3 ein!

SNMP ist ein Internet-Standardprotokoll, das zur Verwaltung von Geräten in IP-Netzwerken verwendet wird. Es bietet eine einfache Möglichkeit, Informationen über Netzwerkgeräte zu sammeln und Konfigurationsänderungen vorzunehmen. SNMP Version 3 führte eine Reihe wichtiger Verbesserungen gegenüber den vorherigen Versionen ein. Insbesondere wurden Verbesserungen in den Bereichen Sicherheit und Authentifizierung vorgenommen. SNMPv3 bietet Verschlüsselungsfunktionen zur Gewährleistung der Datenvertraulichkeit und bietet verbesserte Authentifizierungsmechanismen zur Überprüfung der Identität von Netzwerkgeräten. Darüber hinaus führte SNMPv3 auch verbesserte Möglichkeiten zur Kontrolle des Zugriffs auf Netzwerkgeräte ein.

---
## Was ist eine MIB, und wie ist der Namespace aufgebaut?

Eine MIB ist eine Struktur zur Organisation von Informationen über Netzwerkgeräte. Sie ist in einer hierarchischen Form organisiert, ähnlich einem Baum, mit verschiedenen "Zweigen" oder "Objekten", die verschiedene Aspekte der Geräteleistung und -konfiguration darstellen. Jeder Eintrag in einer MIB hat einen eindeutigen Identifikator, der als Object Identifier (OID) bezeichnet wird. Die MIB ist so aufgebaut, dass sie verschiedene Arten von Geräten und Netzwerkkonfigurationen abbilden kann, und ist daher sehr flexibel.

---

## Wie werden Einträge in der MIB identifiziert? Wie findet man z.B. die Kategorie "IBM"?

Einträge in der MIB werden durch eine Reihe von Zahlen identifiziert, die als Object Identifier (OID) bezeichnet werden. Jede Zahl in der OID repräsentiert einen Knoten in der hierarchischen Struktur der MIB, beginnend von der Wurzel des Baums. So könnte die OID 1.3.6.1.4.1.2 beispielsweise auf einen Eintrag in der IBM-Kategorie der MIB hinweisen, wobei 1.3.6.1.4.1 der generische Pfad für alle Hersteller-spezifischen MIBs ist (bekannt als "private enterprises") und 2 der spezifische Identifikator für IBM ist. Es ist wichtig zu beachten, dass die genaue Struktur und Organisation der MIB von den spezifischen Geräten und Softwareversionen abhängen kann, die in einem bestimmten Netzwerk verwendet werden.