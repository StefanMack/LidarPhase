# LidarPhase
Illustration of the phase measurement method in LIDAR technology


## Lidar ToF-Abstandsmessung indirekt über die Phase

Version 6.2.2019, S. Mack

Eine preiswerte und sehr genaue Messtechnik für die Lichtlaufzeitmessung ist die Phasenmessung. Dabei wird als Sender ein Dauerstrichlaser (CW-Laser) verwendet, dessen Licht intensitätsmoduliert ist. Das "Lichtecho" ist dann ebenfalls mit der gleichen Frequenz intensitätsmoduliert. Je nach Abstand (=Reichweite), d.h. Lichtlaufzeit hat das Echolicht bezüglich seiner Intensitätsmodulation einen Phasenversatz im Vergleich zum gerade emitierten Sendelicht.

**Hierbei ist es wichtig, dass es nicht um einen Phasenversatz der elektromagnetischen Welle sondern um einen Phasenversatz der Intensitätsmodulation handelt.** Im Gegensatz zu Radar ist Lidar üblicherweise eine inkokärente Messtechnik: Die Welleneigenschaft des Lichts spielt keine Rolle. Eine Photodiode misst anders als eine Antenne nur die Intenität, nicht die Feldstärke! Es gibt namhafte Sensorhersteller, die an diesem Grundverständnis bei der Messkernentwicklung schon gescheitert sind ;-)

Im nachfolgendem Text wird dargestellt, wie durch Mischen des Intensitätssignals des Sendelichts mit dem des Echolichts der Phasenversatz, damit die Lichtlaufzeit und schlussendlich der Messabstand bestimmt wird. Weiter wird gezeigt, wie man mit zwei unterschiedlichen Modulationsfrequenzen den Eindeutigkeitsbereich wesentlich vergrößern kann.
