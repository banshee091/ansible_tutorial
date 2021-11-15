# Steps to do

1. Erstelle ein Ansible-Konformes Filesystem
2. Mache einen Plan über den Ablauf deines Playbooks, auf einem einzelnen Host!
    Welche Variablen werden benötigt um alles möglichst Modular zu halten? 
    Welche Rolle wird wann ausgeführt? 
    Benötige ich unterschidliche Hosts? 
    Was muss in mein Inventory?
    ...
3. Unterteile dein Playbook wenn nötig. Sammle die Variablen in den zugehörigen Stellen zusammen.
4. Mach dir gedanken über die Credentials die du benötigst. Passe ggf. einzelne Rollen an um diese mit erhöhten Privilegien auszuführen.
5. Starte das Playbook mit -check. Schau was die einzelnen Rollen zurückliefern
6. Überlege wie du dein einzelnes Playbook für eine Gruppe optimierst.


# Ziele die Erreicht werden sollen

- Update das System auf die aktuellste release Version.
- Installiere Apache Webserver
- Schreibe einen Text in deine index.html