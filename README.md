# Shakerregistratie

Webpagina om per klant te registreren welke shakers er in de winkel staan: merk, type, bouwjaar, aantal cycli, algemene staat, staat van de klemplaat en foto's.

Deze repository bevat alleen de code. Alle gegevens (klantenlijst, machines en foto's) staan in de gedeelde SharePoint-map **Shakers en mengers klanten** (Diensten › Gedeelde documenten › General › MyMx).

## Zo gebruik je het

1. Open de map in SharePoint en klik op **Synchroniseren** of **Snelkoppeling toevoegen aan Mijn bestanden**.
2. Open de pagina in **Microsoft Edge** of **Google Chrome** op je pc.
3. Klik op **Map kiezen**, selecteer de gesynchroniseerde map en klik op **Wijzigingen toestaan**.

## Inhoud van de gedeelde map

| Pad | Inhoud |
|---|---|
| `klanten-*.csv` | Export van de klantenlijst (de recentste wordt gebruikt). Zet een nieuwe export in de map om de lijst bij te werken. |
| `machines/*.json` | Eén bestand per geregistreerde machine. |
| `fotos/*.jpg` | Foto's, verkleind tot maximaal 1600 px. |
