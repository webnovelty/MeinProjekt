## Die Schritte, die du zum Einrichten des GitHub-Repositorys "MeinProjekt" durchgeführt hast.

### 1. Gehe zu GitHub (www.github.com) und melde dich mit deinem Benutzerkonto an. Falls du noch kein Konto hast, registriere dich kostenlos.

![a-1](./images/a-1.png)

### 2. Nach dem Login klicke auf "+ New" (oben rechts) und erstelle ein neues leeres Repository mit dem Namen "MeinProjekt".

![a-2](./images/a-2.png)

### 3. Notiere dir die URL des erstellten Repositories, sie wird später benötigt.

![a-3](./images/a-3.png)

## Die Schritte, die du zum Erstellen eines SSH-Schlüssels (falls du keinen bereits hattest) durchgeführt hast.

### 4. Öffne dein Terminal (Linux/Mac) oder Git Bash (Windows).

![b-4](./images/b-4.png)

### 5. Überprüfe, ob du bereits einen SSH-Schlüssel hast, indem du den folgenden Befehl ausführst: ls ~/.ssh/

![b-5](./images/b-5.png)

### 6. Falls die Ausgabe Dateien wie id_rsa und id_rsa.pub enthält, hast du bereits einen SSH-Schlüssel. In diesem Fall kannst du zu Teil 3 springen. Wenn die Dateien nicht existieren, erstelle einen neuen SSH-Schlüssel mit dem folgenden Befehl: bash ssh-keygen -t rsa -b 4096 -C "deine_email@beispiel.com" Beachte, dass "deine_email@beispiel.com" durch deine GitHub-E-Mail-Adresse ersetzt werden muss.

### 7. Der Befehl wird dich nach dem Speicherort des Schlüssels fragen und optional nach einem Passwort. Du kannst den Standard-Speicherort akzeptieren und ein Passwort festlegen oder es leer lassen (kein Passwort).

![b-6_b-7](./images/b-6_b-7.png)

### ---

![b-6-7](./images/b-6-7.png)

### ---

![b-6-7-](./images/b-6-7-.png)

## Die Schritte, die du zum lokalen Klonen des Repositorys, zum Konfigurieren von Git und zum Erstellen der initialen Commits durchgeführt hast.

### 8. Gehe in deinem Terminal zu dem Verzeichnis, in dem du dein lokales Git-Repository erstellen möchtest.

![c-8](./images/c-8.png)

### 9. Klone das GitHub-Repository "MeinProjekt" mit dem folgenden Befehl: bash git clone git@github.com:DeinBenutzername/MeinProjekt.git .Ersetze "DeinBenutzername" durch deinen GitHub-Benutzernamen. Der Befehl klont das Repository auf deinen lokalen Rechner.

![c-9](./images/c-9.png)

### 10. Navigiere in das geklonte Verzeichnis "MeinProjekt":

![c-10](./images/c-10.png)

### 11. Konfiguriere Git mit deinem Namen und E-Mail, die mit GitHub verknüpft sind:

![c-11](./images/c-11.png)

### 12. Füge eine neue Datei hinzu (z. B. "main.py") und erstelle einen Initial-Commit:

![c-12](./images/c-12.png)

## Die Schritte, die du zum Erstellen des "feature"-Branches, zum Hinzufügen einer neuen Datei zu diesem Branch und zum Committen der Änderungen durchgeführt hast.

### 13. Erstelle einen neuen Branch mit dem Namen "feature":

![c-13](./images/c-13.png)

### 14. Füge eine weitere Datei hinzu (z. B. "utils/database.py") und erstelle einen Commit auf dem "feature"-Branch:

![c-14](./images/c-14.png)

### 15. Bearbeite die Datei "main.py" und führe einen Commit auf dem "feature"-Branch durch:

![c-15-1](./images/c-15-1.png)

### ---

![c-15-2](./images/c-15-2.png)

## Die Schritte, die du zum Mergen des "feature"-Branches in den "master"-Branch und zum Beheben des dabei auftretenden Merge-Konflikts durchgeführt hast.

### 16. Wechsle zurück zum "master"-Branch:

![c-16](./images/c-16.png)

### 17. Bearbeite die Datei "main.py" und führe einen Commit auf dem "master"-Branch durch:

![c-17-1](./images/c-17-1.png)

### ---

![c-17-2](./images/c-17-2.png)

### 18. Versuche nun den "feature"-Branch in den "master"-Branch zu mergen:

![c-18](./images/c-18.png)

### ---

![c-18-1](./images/c-18-1.png)

### ---

![c-18-2](./images/c-18-2.png)

### ---

![c-18-3](./images/c-18-3.png)
