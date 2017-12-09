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
* [Die erste App mit Direktive](beispiele/ersteApp_mit_directive.html)
* [Die erste App mit Direktive](beispiele/ersteApp_mit_Routen.html)
* [Die erste App mit ngclick](beispiele/ersteApp_mit_ngclick.html)
* [Die erste App mit ngif](beispiele/ersteApp_mit_ngif.html)
* [Die erste App mit ngshow und nghide](beispiele/ersteApp_mit_ngshow_nghide.html)
* [Die erste App mit ngclass](beispiele/ersteApp_mit_ngclass.html)
* [Die erste App mit ngstyle](beispiele/ersteApp_mit_ngstyle.html)
* [Die erste App mit ngsrc](beispiele/ersteApp_mit_ngsrc.html)
* [Die erste App mit ngrepeat](beispiele/ersteApp_mit_ngrepeat.html)
* [Die erste App mit ngrepeat 2](beispiele/ersteApp_mit_ngrepeat2.html)
* [Die erste App mit ngrepeat 3](beispiele/ersteApp_mit_ngrepeat3.html)
* [Die erste App mit ngrepeat 4](beispiele/ersteApp_mit_ngrepeat4.html)
* [Die erste App mit ngrepeat 5](beispiele/ersteApp_mit_ngrepeat5.html)
* [Die erste App mit nginit](beispiele/ersteApp_mit_nginit.html)
* [Die erste App mit ngsubmit](beispiele/ersteApp_mit_ngsubmit.html)
* [Die erste App mit ngmodel](beispiele/ersteApp_mit_ngmodel.html)
* [Die erste App mit ngchange](beispiele/ersteApp_mit_ngchange.html)
* [Die erste App mit ngfocus, ngblur](beispiele/ersteApp_mit_ngfocus_ngblur.html)
* [Die erste App mit ngdisabled](beispiele/ersteApp_mit_ngdisabled.html)
* [Die erste App mit Formular](beispiele/ersteApp_mit_formular.html)
* [Die erste App mit Formular 2](beispiele/ersteApp_mit_formular2.html)
* [Die erste App mit Formular 2](beispiele/ersteApp_mit_events.html)
* [Die erste App mit Formular 2](beispiele/ersteApp_mit_timeout.html)
* [Die erste App mit Formular 2](beispiele/ersteApp_mit_interval.html)

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
