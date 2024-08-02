# Hallo

## Dit is een probeersel
Dit is een probeersel omdat ik RTD wil testen in combinatie met de meer info truuk.
<details> <summary>Meer informatie </summary> En dit dan zowel buiten een tabel als daarbinnen. Want je weet ommers maar nooit.  </details>

### Authenticatie

| Variabele                                | Uitleg                                                    |
| ---------------------------------------- | --------------------------------------------------------- |
| `oidcAuthority`                          | URL van de OpenID Connect Identity Provider                 |
| `oidcClientId`                           | Voor toegang tot de OpenID Connect Identity Provider      |
| `oidcClientSecret`                       | Secret voor de OpenID Connect Identity Provider           |
| `OIDC_MEDEWERKER_IDENTIFICATIE_CLAIM`    | Identificatie van de medewerker in regsiters <br/> (default waarde is `email`) <details> <summary>Meer informatie </summary> Bij het wegschrijven van gegevens naar bv. Open Klant of Open Zaak is een `medewerkerIdentificatie.identificatie` verplicht. Verschillende gemeenten gebruiken hier verschillende waardes voor. Bij een koppeling met bv. de e-Suite is het van belang dat hier de e-Suite gebruikersnaam in staat van de ingelogde KCM. </details>|
| `OIDC_MEDEWERKER_IDENTIFICATIE_TRUNCATE` | Optioneel afkappen van de claim <br/> (bijv. `24`) <details> <summary>Meer informatie </summary> Binnen ZGW mag een `medewerkerIdentificatie.identificatie` niet langer zijn dan 24 karakters. Met deze variabele kun je ervoor zorgen dat de uiteindelijk waarde wordt afgekapt na 24 tekens. </details>       |
|  |  |
