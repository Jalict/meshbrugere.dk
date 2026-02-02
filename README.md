# Danske Meshtastic Brugere Hjemmeside
Dette er kildekolde for Danske Meshtastic Brugere's hjemmeside.

Alle kan foreslå ændringer herinde, men hvis man ikke er til dét så hop på vores [Discord server](/discord) hvis du har forslag eller vil hjæpe til :)

## setup
Kort guide til hvordan du bygger siden lokalt, så du kan tjekke dine ændringerne før du laver pull request med dem.

**Linux**
```bash
# installer virtualenv
pip install virtualenv

# setup virtual miljø
python -m venv .venv

# aktiver virtuelt miljø
source .venv/bin/activate

# installer mkdocs + tema
pip install mkdocs
pip install mkdocs-cinder

# byg hjemmesiden
mkdocs build
```

Du kan nu åbne `<meshbrugere.dk>/site/index.html` i din browser