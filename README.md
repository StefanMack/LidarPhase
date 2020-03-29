# LidarPhase

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/StefanMack/LidarPhase/master)

## Lidar ToF-Abstandsmessung indirekt über die Phase

Eine preiswerte und sehr genaue Messtechnik für die Lichtlaufzeitmessung ist die Phasenmessung. Dabei wird als Sender ein Dauerstrichlaser (CW-Laser) verwendet, dessen Licht intensitätsmoduliert ist. Das "Lichtecho" ist dann ebenfalls mit der gleichen Frequenz intensitätsmoduliert. Je nach Abstand (=Reichweite), d.h. Lichtlaufzeit hat das Echolicht bezüglich seiner Intensitätsmodulation einen Phasenversatz im Vergleich zum gerade emitierten Sendelicht.

**Hierbei ist es wichtig, dass es nicht um einen Phasenversatz der elektromagnetischen Welle sondern um einen Phasenversatz der Intensitätsmodulation handelt.** Im Gegensatz zu Radar ist Lidar üblicherweise eine inkokärente Messtechnik: Die Welleneigenschaft des Lichts spielt keine Rolle. Eine Photodiode misst anders als eine Antenne nur die Intenität, nicht die Feldstärke! Es gibt namhafte Sensorhersteller, die an diesem Grundverständnis bei der Messkernentwicklung schon gescheitert sind ;-)

Im nachfolgendem Text wird dargestellt, wie durch Mischen des Intensitätssignals des Sendelichts mit dem des Echolichts der Phasenversatz, damit die Lichtlaufzeit und schlussendlich der Messabstand bestimmt wird. Weiter wird gezeigt, wie man mit zwei unterschiedlichen Modulationsfrequenzen den Eindeutigkeitsbereich wesentlich vergrößern kann.

> Hinweis: Wenn Sie oben im File Explorer auf eine der beiden Jupyter Notebooks (Endung ".ipnyb") klicken, dann wird lediglich ein Viewer geöffnet, in dem Sie das Notebook nur anschauen können. Dieser Viewer liefert jedoch öfters beim Start eine Fehlermeldung und kann Animationen nur unzureichend wiedergeben.  
**Zum Anschauen verwenden Sie daher bitte den speziellen Viewer für Jupyter-Notebooks "nbviewer" [über diesen Link](https://nbviewer.jupyter.org/github/StefanMack/LidarPhase/blob/master/LidarPhaseMess.ipynb).**
Möchten Sie die Codebeispiele darin einzeln ausführen und ändern, dann klicken Sie bitte auf das Icon "launch|binder". **Das Starten des Webservice binder kann bis zu einer Minute dauern.**


License
-----
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.
