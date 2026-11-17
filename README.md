# Krishi Setu

Krishi Setu is a responsive agri-tech marketplace prototype that connects farmers and FPOs with buyers and logistics partners.

## Features

- Farmer and FPO crop listings
- Buyer marketplace and offer system
- Live mandi price display
- Logistics job booking and status tracking
- Wallet, transaction history, and payment interfaces
- Farmer, buyer, and logistics profiles
- Crop photo previews and profile ratings
- Live weather information based on location
- English and Hindi language support
- Official administration portal
- Excel export support
- Responsive mobile and desktop layouts

## Project File

The complete application is contained in:

```text
56_abv_1.html
```

## How to Run

No build step or installation is required.

1. Open `56_abv_1.html` in a modern web browser.
2. Sign in or register through the application interface.
3. Select the role you want to use: Farmer/FPO, Buyer, or Logistics.

From PowerShell, the file can also be opened with:

```powershell
Start-Process ".\56_abv_1.html"
```

## Technologies

- HTML5
- CSS3
- JavaScript
- Browser `localStorage`
- SheetJS / XLSX
- OpenWeather data when location access and API configuration are available

## Data Storage

The prototype stores user, listing, offer, transaction, and wallet data in the browser's `localStorage`. Clearing browser site data resets the application data.

## Notes

- Authentication and payment screens are demonstrations and should not be treated as production payment or identity services.
- Demo OTP and official portal flows may display generated OTP values as notifications.
- An internet connection is recommended for fonts, the XLSX library, maps or geocoding services, and live weather data.
