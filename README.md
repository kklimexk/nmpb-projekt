nmpb-projekt
============
Projekt na zajecia z narzedzi modelowania procesow biznesowych:

WYMAGANIA (dla wersji z JBoss AS 7):

Nalezy zainstalowac koniecznie JDK 7.
UWAGA: JDK 8 moze nie zadzialac.

KONFIGURACJA:

1. git clone https://github.com/kkrzys/nmpb-projekt
2. Wchodzimy do katalogu nmpb-projekt
3. mvn clean install
4. Kopiujemy plik /target/loan-approval-0.1.0-SNAPSHOT.war do /camunda-bpm-jboss-7.1.0-Final/server/jboss-as-7.2.0.Final/standalone/deployments/
5. Wchodzimy do katalogu /camunda-bpm-jboss-7.1.0-Final/ i uruchamiamy skrypt start-camunda.sh (start-camunda.bat)
