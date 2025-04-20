# Strömungsmaschinen Pumpenanalyse

## Projektbeschreibung

Dieses Repository enthält das Projekt für die **Strömungsmaschinen-Vorlesung – Pumpenanalyse** an der **DHBW Karlsruhe**. Ziel des Projekts ist es, das Betriebsverhalten einer Wasserpumpe basierend auf realen Messdaten und Herstellerangaben zu analysieren. Es werden Berechnungen zur Schätzung des Energieverbrauchs, der Pumpen-Effizienz und der Umwandlung von hydraulischer Energie durchgeführt.

## Projektkontext

Das Projekt analysiert eine Wasserpumpe in einer industriellen Umgebung. Die Leistungsdaten, insbesondere der Volumenstrom, sind in der Datei `volume_flow_data.csv` enthalten. Die Pumpe hat einen Impellerdurchmesser von **264 mm**.

## Anforderungen

- **Python 3.x**
- **Jupyter Notebook**
- **pandas, numpy, scipy**: Zur Datenverarbeitung und Berechnung

## Aufgaben

1. **Berechnung des Energieverbrauchs**: Schätzung der gesamten verbrauchten Energie basierend auf dem Volumenstrom.
2. **Bestimmung der Pumpen-Effizienz**: Berechnung der durchschnittlichen Effizienz der Pumpe.
3. **Berechnung der ungenutzten Energie**: Bestimmung der Energie, die nicht in hydraulische Arbeit umgewandelt wurde.

## Methodik

1. **Datenverarbeitung**: Umrechnung des Volumenstroms von m³/h in m³/s, Berechnung der Zeitdifferenz und Interpolation des Pumpenkopfs.
2. **Energieberechnungen**: Berechnung der hydraulischen und Eingangsleistung sowie des Energieverbrauchs.
3. **Effizienzberechnung**: Berechnung der Pumpen-Effizienz als Verhältnis von hydraulischer Energie zu Eingangsenergie.

## Code-Erklärung

- **Daten Laden**: Die CSV-Datei mit Zeitstempel und Volumenstrom wird eingelesen.
- **Umrechnung und Berechnungen**: Volumenstrom wird umgerechnet, Pumpenkopf interpoliert und die Energie berechnet.
- **Effizienz**: Berechnung der durchschnittlichen Effizienz.
