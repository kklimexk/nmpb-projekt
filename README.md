nmpb-projekt
============
Projekt na zajecia z narzedzi modelowania procesow biznesowych:

WYMAGANIA (dla wersji z JBoss AS 7):

Nalezy zainstalowac koniecznie JDK 7.
UWAGA: JDK 8 moze nie zadzialac.

KONFIGURACJA:

1. Sciagnac camunde ze strony: http://camunda.org/release/camunda-bpm/jboss/7.1/camunda-bpm-jboss-7.1.0-Final.tar.gz
2. Sciagnac plugin do modelowania dla eclipsa (Kepler): http://camunda.org/release/camunda-modeler/update-sites/kepler/latest/site/
3. git clone https://github.com/kkrzys/nmpb-projekt
4. Zaimportowac projekt do eclipsa (Kepler) - gdy chcemy korzystac z terminala
5. Wchodzimy do katalogu nmpb-projekt
6. mvn clean install (mozna takze w eclipsie klikajac prawym na pom.xml -> Run as -> Maven Install)
7. Kopiujemy plik /target/loan-approval-0.1.0-SNAPSHOT.war do /camunda-bpm-jboss-7.1.0-Final/server/jboss-as-7.2.0.Final/standalone/deployments/
8. Wchodzimy do katalogu /camunda-bpm-jboss-7.1.0-Final/ i uruchamiamy skrypt start-camunda.sh (start-camunda.bat)
