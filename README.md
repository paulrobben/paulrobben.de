# Webseite von Paul Robben

Code der Webseite [paulrobben.de](https://paulrobben.de).

Basiert auf dem [Hugo](https://gohugo.io/) Theme [Adritian](https://github.com/zetxek/adritian-free-hugo-theme).

# Build & Deploy
Lokal betreiben/verändern der Webseite per Hugo mit dem Befehl `hugo server`. Per Befehl `hugo` wird unter /public das HTML generiert, das dann per beliebigen Webserver (z.B. Apache) bereitgestellt werden kann.

Deployment aktuell per Github Actions nach Uberspace.


# Einpflegen von Fotos
Zunächst muss die Datei unter /assets/photos abgelegt werden. Anschließend kann sie unter /data/photos.yml eingepflegt werden, dazu einfach den Dateinamen, Ort und Datum (im Format 2020-01-31 für den 31. Januar 2020) sowie optional den Titel (wird auch als Alt-Text verwendet) eintragen.
