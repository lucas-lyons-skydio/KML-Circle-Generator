# KML Circle Generator

A simple, browser-based tool to create KML files with radius circles from street addresses. No installation required – works on any device with a modern web browser.

## 🚀 Live Tool

**[Launch KML Circle Generator]([https://YOUR-USERNAME.github.io/kml-circle-generator/](https://lucas-lyons-skydio.github.io/KML-Circle-Generator/))**

## ✨ Features

- **Cross-platform** – Works on Windows, Mac, Linux, iOS, Android
- **No installation** – Runs entirely in your browser
- **Address geocoding** – Converts street addresses to coordinates automatically
- **Customizable radius** – Set any radius in miles
- **Up to 10 locations** – Add multiple locations in one KML file
- **Free** – Uses OpenStreetMap's free geocoding service

## 📖 How to Use

### Step 1: Open the Tool
Click the link above or open `index.html` in any web browser.

### Step 2: Set Your Radius
Enter your desired circle radius in miles (e.g., `2.5` for 2.5-mile circles).

### Step 3: Add Locations
For each location, enter:
- **Name** – A label for the location (e.g., "Fire Station 1")
- **Address** – Full street address including city, state, and ZIP code

Click **"+ Add Location"** to add more (up to 10).

**Example addresses:**
```
123 Main Street, Bristol, CT 06010
456 Oak Avenue, Hartford, CT 06103
```

### Step 4: Geocode Addresses
Click **"Geocode Addresses"** to convert your addresses to latitude/longitude coordinates.

- ✓ Green checkmark = Address found successfully
- ✗ Red X = Address not found (try a more complete address)

*Note: Please wait for geocoding to complete before proceeding.*

### Step 5: Generate KML
Click **"Generate & Download KML"** to download your KML file.

### Step 6: View Your Circles
Open the downloaded KML file in:
- **Google Earth** (desktop or web)
- **Google My Maps** (import the KML file)
- Any other KML-compatible mapping software

## 💡 Tips for Best Results

- **Use complete addresses** – Include street number, street name, city, state, and ZIP code
- **Check spelling** – Typos can cause geocoding to fail
- **Be specific** – "123 Main St, Bristol, CT 06010" works better than "Main St, Bristol"
- **US addresses work best** – International addresses may have mixed results

## 🔧 Technical Details

- Geocoding powered by [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/)
- Rate limited to 1 request per second (per Nominatim usage policy)
- All processing happens in your browser – no data is sent to any server except for geocoding

## 📄 License

MIT License – Free to use and modify.

---

*Questions or issues? Open an issue on this repository.*
