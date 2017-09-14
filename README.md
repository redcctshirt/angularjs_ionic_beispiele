## Beispiele für AngularJS und Ionic-Framework - hybride Apps mit Cordova erstellen

* native App - erstellt mit Android Studio (Java)
* hybride App - erstellt mit AngularJS, Ionic Framework (HTML, CSS, Javascript) und Cordova

## AngularJS - Javascript-Framework zur Erstellung von Single-Page Applications (SPA)

Scope - Gültigkeitsbereich - Verbindung zwischen Controller und Template
$rootScope - Wurzelscope - umfasst alle Kinder-Scopes (die gesamte Anwendung)
$scope - normaler Scope
$scope.$apply() - ruft Aktualisierungszyklus auf
$scope.$digest() - Aktualisierungszyklus

* [Die erste App](beispiele/ersteApp.html)
* [Die erste App mit Controller](beispiele/ersteApp_mit_controller.html)
* [Die erste App mit Template](beispiele/ersteApp_mit_template.html)
* [Die erste App mit Service Value](beispiele/ersteApp_mit_service_value.html)
* [Die erste App mit Service](beispiele/ersteApp_mit_service.html)
* [Die erste App mit Service Factory](beispiele/ersteApp_mit_service_factory.html)
* [Die erste App mit http get](beispiele/ersteApp_mit_http_get.html)
* [Die erste App mit Service Provider](beispiele/ersteApp_mit_service_provider.html)
* [Die erste App mit Service Constant](beispiele/ersteApp_mit_service_constant.html)

## Ionic Framework - Framework für hybride Apps

## Cordova - Zugang zu nativen Funktionen über Javascript, Erzeugen der apk

### Installation

* Voraussetzung: git, Java, Android SDK, nodejs

'''
sudo npm install -g cordova
'''

### Anwendung

'''
# Projekt erzeugen - cordova create Ordner AppID AppName
cordova create Hallo com.beispiel.hallo Hallo
'''

Projektordnerstruktur: hooks, platforms, plugins, res, www (App in HTML), config.xml (Projekteinstellungen)

'''
# Platform Android hinzufügen
cordova platform add android 

# Platform Android entfernen
cordova platform remove android

# im Netzwerk zur Verfügung stellen http://localhost:8000
cordova serve android

# Emulator starten
cordova emulate android

# Plugin suchen
cordova plugin search x

# Plugin hinzufügen
cordova plugin add x

# Plugin entfernen
cordova plugin remove x

# App erstellen
cordova build android
'''



## Lizenz

https://creativecommons.org/publicdomain/zero/1.0/deed.de
