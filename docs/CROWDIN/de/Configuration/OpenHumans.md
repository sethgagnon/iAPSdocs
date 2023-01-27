# Open Humans Uploader

## Spende deine Daten an die Wissenschaft

Du kannst die Community unterstützen, indem Du Deine Daten für Forschungsprojekte zur Verfügung stellst. Dies hilft Wissenschaftlern, die Dinge voranzutreiben, neue wissenschaftliche Ideen zu entwickeln und die Offenheit gegenüber Open Source Closed Loop Systemen zu fördern. AndroidAPS is ready to synchronize your data with [Open Humans](https://www.openhumans.org), a platform allowing you to upload, connect, and store your personal data – such as genetics, activity and health data.

Du behältst die volle Kontrolle darüber, was mit Deinen Daten geschieht und welche Projekte Du unterstützen möchtest, indem Du ihnen den Zugriff auf Deine Daten ermöglichst. Abhängig vom Projekt, dem Du beitrittst, werden Daten ausgewertet und vom Projekt auf unterschiedliche Art und Weise und in unterschiedlichem Umfang genutzt.

Die folgenden Daten werden zu Deinem Open-Humans-Konto hochgeladen:

- Glucose values
- Careportal events (except notes)
- Extended boluses
- Profile switches
- Total daily doses
- Temporary basals
- Temp targets
- Einstellungen
- Application version
- Device model
- Screen dimensions

Vertrauliche oder private Informationen wie z. B. Deine Nightscout-URL oder das API-Secret werden nicht hochgeladen.

## Einrichtung

1. Create your account on [Open Humans](https://www.openhumans.org) if not already done. Zur Anmeldung kannst Du auch Dein Google- oder Facebook-Konto verwenden, wenn Du dies möchtest.
2. Enable the “Open Humans” plugin in [Config Builder](../Configuration/Config-Builder.md).
3. Öffne dessen Einstellungen durch einen Klick auf das Zahnradsymbol. Du kannst das Hochladen auf die Zeiten beschränken, in denen Du Dich im WLAN befindest und/oder zu denen das Smartphone geladen wird.
4. Öffne das Open-Humans-Plugin (entweder über den OH Tab oder Hamburger-Menü) und klicke auf 'LOGIN'.

```{image} ../images/OHUploader1.png
:alt: Open Humans Konfigurations-Generator
```

5. Lies die angezeigten Informationen über den Open Humans Uploader und die Nutzungsbedingungen sorgfältig.
6. Bestätige, indem Du das Kästchen markierst und auf 'LOGIN' klickst.
7. Die Open Humans Webseite wird geöffnet. Melde Dich mit Deinen Zugangsdaten an.
8. Entscheide, ob Du Deine AndroidAPS Uploader-Mitgliedschaft in Deinem öffentlichen Open Humans Profil ausblenden möchtest.
9. Klicke auf die Schaltfläche 'Authorize project'.

```{image} ../images/OHUploader2.png
:alt: Open Humans Nutzungsbedingungen + Login
```

10. Danach kehrst Du zu AAPS zurück. Dort wird der erfolgreiche Login bestätigt.
11. Das Smartphone muss eingeschaltet und das Open Humans Plugin geöffnet bleiben, um die Einrichtung abschließen zu können.
12. Nach dem Klicken auf 'Schließen' wird Deine Mitglieds-ID angezeigt. Queue sizes > 0 shows that there is still data to be uploaded.
13. Klicke auf 'LOGOUT', wenn Du das Hochladen von Daten zu Open Humans stoppen möchtest.
14. Der laufende Upload wird in den Android-Benachrichtigungen angezeigt.

```{image} ../images/OHUploader3.png
:alt: Open Humans Einrichtung beenden
```

15. You can manage your data by logging in to the [Open Humans website](https://www.openhumans.org).

```{image} ../images/OHWeb.png
:alt: Open Humans Datenverwaltung
```

## Möglichkeiten zum Teilen Deiner Daten

### [The 'OPEN' project](https://www.open-diabetes.eu/)

Das “OPEN” Projekt besteht aus einem internationalen und bereichsübergreifenden Konsortium, das Patienten-Innovatoren, Kliniker, Sozialwissenschaftler, Informatiker und Patientenorganisationen zusammenführt, um eine Evidenzbasis rund um die Auswirkungen von Do-it-yourself Artificial Pancreas Systemen (DIY APS) auf Menschen mit Diabetes und verschiedene Gesundheitssysteme zu schaffen. For more details see their [website](https://www.open-diabetes.eu/).

September 2020 the 'OPEN' project launched a [survey](https://survey.open-diabetes.eu/) including the option to donate data you uploaded to Open Humans. A [tutorial](https://open-diabetes.eu/en/open-survey/survey-tutorials/) how to donate your data to the 'OPEN' project is available on their site and within the survey itself.

### [OpenAPS Data Commons](https://www.openhumans.org/activity/openaps-data-commons/)

Die OpenAPS Data Commons wurden erstellt, um einen einfachen Weg zu schaffen, Daten aus der DIYAPS-Community mit Forschern zu teilen. Die Daten werden sowohl mit traditionellen Forschern, die traditionelle Forschungsstudien erstellen, als auch mit Gruppen oder Einzelpersonen aus der Community, die Daten im Rahmen ihrer eigenen Forschungsprojekte überprüfen wollen, gemeinsam genutzt. OpenAPS Data Commons verwendet die 'Open Humans' -Plattform, um es den Menschen zu ermöglichen, ihre Daten von DIYAPS einschließlich AndroidAPS, Loop und OpenAPS einfach hochzuladen und gemeinsam zu nutzen.

Du kannst Deine Daten über einen der folgenden drei Wege zu Open Humans hochladen:

1. Nutze den oben beschriebenen Open Humans Uploader in AndroidAPS.
2. Verwende Nightscout Data Transfer, um die Daten zu übermitteln.
3. Lade Daten manuell zu Open Humans hoch.

Sobald Du ein Konto eingerichtet hast und Deine Daten hochgeladen werden, solltest Du diese mit den OpenAPS Data Commons verbinden, wenn Du Deine Daten für Forschungszwecke spenden willst.

## Nutzungsbedingungen

This is an open source tool that will copy your data to [Open Humans](https://www.openhumans.org). Wir behalten uns keine Rechte vor, Deine Daten ohne Deine ausdrückliche Genehmigung an Dritte weiterzugeben. Die Daten, die das Projekt und die Anwendung erhalten, werden über eine zufällige Benutzer-ID identifiziert und nur nach Deiner Zustimmung sicher auf ein Open Humans-Konto übertragen. You can stop uploading and delete your upload data at any time via [www.openhumans.org](https://www.openhumans.org). Sei Dir bewusst, dass es Projekte auf Open Humans geben kann, die das Löschen bereits gespendeter Daten nicht ermöglichen.

Also see [Open Humans Terms of Use](https://www.openhumans.org/terms/).

## Datenschutz

Open Humans schützt Deine Privatsphäre, indem Dir für jedes Projekt eine nummerische ID zugewiesen wird. Dadurch kann Dich das Projekt wiedererkennen aber nicht identifizieren. Die von AAPS hochgeladene Anwendungs-ID funktioniert gleich und hilft nur bei der Datenverwaltung. Weitere Informationen findest Du hier:

- [Open Humans Data Use Policy](https://www.openhumans.org/data-use/)
- [Open Humans GDPR](https://www.openhumans.org/gdpr/)