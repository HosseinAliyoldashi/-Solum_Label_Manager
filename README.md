# Label_Manager
 Benutzerfreundliche Software zur Verwaltung von LED-Etiketten. Vorschau, Neustart und Versand von Bildern per API möglich. Alle Aktionen werden automatisch protokolliert. Keine Vor-Ort-Prüfung nötig – alles zentral steuerbar.
# Beschreibung der Variablen
VALID_USERS
Eine Liste von Benutzernamen, die berechtigt sind, die Software zu verwenden. Nur Benutzer in dieser Liste haben Zugang zur Anwendung.

PAIR_ID_MAPPING
Ein Dictionary, das die ID der Labels mit einer benutzerdefinierten Kennung oder einem Namen verknüpft. Dies erleichtert die Auswahl und Verwaltung von Labels.

API_URL_TEMPLATE
Eine URL-Vorlage für die Kommunikation mit der API der Labels. Sie enthält Platzhalter für Variablen wie IP oder ID, die ersetzt werden können.

API_UPDATE_URL
Die URL der API, die speziell für das Aktualisieren der Label-Bilder verwendet wird. Diese URL wird verwendet, um neue Bilddaten an das Label zu senden.

api-key
Ein API-Schlüssel, der für die Authentifizierung bei der Kommunikation mit den Geräten der Labels erforderlich ist. Ohne diesen Schlüssel werden die Anfragen abgelehnt.

app.title
Der Haupttitel der Anwendung, der im Fenster der Software angezeigt wird.

title_label
Der Titel, der in der Benutzeroberfläche oben angezeigt wird, häufig als Logo oder der Name der Software.

