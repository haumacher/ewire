# E-Wire

English version below.

[E-Wire](https://github.com/haumacher/ewire) ist ein Tool zur Planung und Dokumentation von Elektro-Installationen in Gebäuden.
Die Dokumentation und Planungsfunktion ist insbesondere bei smart-home Installationen mit KNX interessant, 
weil bei dieser Installationsart eine große Menge an Leitungen für die einzelnen Schaltfunktionen verlegt 
werden müssen. 

## Entwicklungsversion

Die Anwendung ist als Konfiguration der modellbasierten no-code Platform [TopLogic](https://github.com/top-logic/tl-engine) 
realisiert. Ein lokaler Start als Entwickungs- und Konfigurationsumgebung benötigt eine installiertes Java 17 und Apache Maven. 
Mit diesen Voraussetzungen ist ein Start mit den folgenden Schritten möglich:

```
git clone https://github.com/haumacher/ewire.git
cd ewire
mvn
```

Danach sollte sich ein Browser-Fenster öffnen und zum Login auffordern. Der Administrator hat die Kennung `root` und 
das Passwort wird beim Start-Vorgang auf der Konsole ausgegeben.

# English Version

Tool for planning and documenting electrical installations in buildings. 
The documentation and planning function is particularly interesting for smart home installations with KNX, 
because this type of installation requires a large number of cables to be laid for the individual switching functions.

## Development version

The application is implemented as a configuration of the model-based no-code platform [TopLogic](https://github.com/top-logic/tl-engine). 
A local start as development and configuration environment requires an installed Java 17 and Apache Maven. 
With these prerequisites, a start with the following steps is possible:

```
git clone https://github.com/haumacher/ewire.git
cd ewire
mvn
```

A browser window should then open and prompt you to log in. The administrator has the ID ‘root’ and 
the password is displayed on the console during the start process.
