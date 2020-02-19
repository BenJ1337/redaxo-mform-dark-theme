## Dark Theme für REDAXO Addon MForm 

### Template einrichten
Das Template kann nach zwei Verfahren im Addon MForm registriert werden:

1. Vor Installation von MForm:
    1) Den Ordner template mit Inhalt in das MForm Addon Verzeichnis kopieren
        
            /redaxo/src/addons/mform/data/
        
    2) MForm wie gewohnt über das Addon-Menü installieren
    3) Das Dark Theme in den MForm Einstellungen auswählen und übernehmen


2. Nach Installation von MForm bzw. ohne Deinstallation von MForm
    1) Den Ordner dark_theme jeweils in folgende Verzeichnisse kopieren    
    
            /redaxo/data/addons/mform/templates/ (nur .init Dateien relevant)
            /assets/addons/mform/templates/ (nur theme.css relevant)
           
    aus `/redaxo/data/...` werden die .ini Dateien für den Aufbau des HTML des Inputformulars im REDAXO-Backend geladen. 
    
    aus `/assets/addons/...` wird die theme.css im REDAXO Backend eingebunden