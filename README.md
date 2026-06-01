# Simulation Mehrtanksystem (MATLAB/Simulink)

Dieses Projekt entstand im Rahmen des Labors für Regelungstechnik. Ziel war die Modellbildung, Simulation und Regelung eines Zwei-Behälter-Systems. 
Die komplette Umsetzung und der Reglerentwurf wurden in MATLAB und Simulink gemacht.

## Projektaufgaben
* **Modellbildung:** Aufstellen der physikalischen Gleichungen für die Füllstände der beiden Tanks.
* **Parameterbestimmung:** Linearisierung und Berechnung der Übertragungsfunktionen.
* **Simulation:** Aufbau des Systems in Simulink.
* **Regelung:** Auslegung und Implementierung eines PI-Reglers für den zweiten Behälter unter Berücksichtigung von Systemgrenzen (z. B. Pumpenspannung).

## Hochgeladene Dateien
* `ZweitankSystem_mit_regler.slx` – Das finale Simulink-Modell inklusive Regelschleife.
* `Tank.m` – MATLAB-Skript mit allen Systemparametern zur Initialisierung (Flächen, Fluidwiderstände etc.).
