# Wp-Install
### Um WordPress zu installieren, wird ein Webspace benötigt, der die folgenden Mindestvoraussetzungen erfüllt:<br>
* PHP-Version 5.2.4 oder höher
* MySQL-Version 5.0 oder höher
* Apache Server

## Folgende Schritte beachten!
### Apache und Datenbak
* Bitte XAMPP unterladen und installieren https://www.apachefriends.org/de/download.html<br>
<strong>Datenbank erforderlich!</strong><br>
* Webbrowser Öffnen und die Seite localhost/phpmyadmin aufrufen und sich einloggen<br>
<strong>Neue Datenbank anlegen</strong><br>
* Auf C://xampp/htdocs einen Ordner erstellen mit einem gewünschten Name (ZB. myWebsite)<br>

### Wordpress Paket
* Wordpress unterladen https://de.wordpress.org/
* Öffne die Datei wp-config-sample.php mit einem Texteditor zB. Notepad++ unterladen https://notepad-plus-plus.org/download/v7.5.1.html
* Füge die erforderlichen Datenbankdaten und die Sicherheitsschlüssel (kleine, große Buchstaben beachten!!!) ein.
  * define('DB_NAME', 'DATENBANKNAME'); // Der Name der Datenbank, die du benutzt.
  * define('DB_USER', 'BENUTZERNAME'); // Dein MySQL Datenbank Benutzernamen
  * define('DB_PASSWORD', 'PASSWORT'); // Dein MySQL Passwort
  * define('DB_HOST', 'localhost');
* Das ganze Paket in deinem Ordner (ZB. C://xamp/htdocs/myWebseite) kopieren.
* Einen Webbrowser Öffnen und die Seite localhost/myWebseite/install.php aufrufen.
* Automatisierte Installation durchführen.

