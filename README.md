# Nairobi → Lake Naivasha → Masai Mara: 8-Day Safari Map
 
This is an interactive 3D map of an 8-day safari in Kenya. The trip starts in **Nairobi**, then descends into the Great Rift Valley to **Lake Naivasha**, where guests stay at Loldia House and take a walking safari on **Crescent Island**. From there it continues to the **Masai Mara**, covering Governors Camp, the **Mara Triangle** and the **Talek** region before returning to Nairobi.
 
🗺️ **See the full itinerary and the live map:**
[Jezioro Naivasha i Maasai Mara](https://safarikenia.com.pl/jezioro-naivasha-maasai-mara/) on **Safari Kenia**
 
---
 
## The route
 
| Day | Destination | Accommodation / Highlight |
|-----|-------------|---------------------------|
| Start | Arrival in Kenya | Jomo Kenyatta International Airport |
| Day 1 | Nairobi | Hemingways Nairobi |
| Day 2 | Lake Naivasha | Loldia House |
| Day 3 | Lake Naivasha | Crescent Island Game Sanctuary |
| Day 4 | Masai Mara | Governors Camp |
| Day 5 | Mara Triangle | Mara Triangle |
| Day 6 | Talek region | Talek |
| Day 7 | Return to Nairobi | Hemingways Nairobi |
| Day 8 | Departure | Jomo Kenyatta International Airport |
 
**To the lake:** Nairobi → Limuru Hills → Lake Naivasha
**To the Mara:** Naivasha → Mai Mahiu → Narok → Masai Mara
**Back:** Talek → Narok → Mai Mahiu → Nairobi
 
The interface labels are in Polish, matching the tour page the map is embedded on.
 
## Features
 
- **Satellite basemap with 3D terrain.** The map uses the Mapbox Standard Satellite style with DEM terrain at 1.5× exaggeration and a tilted camera. This makes the Rift Valley escarpment and the volcanic landscape around Lake Naivasha stand out.
- **Animated route line.** A golden "marching ants" dashed line connects every stop in order. Hidden waypoints (Limuru, Mai Mahiu, Narok) guide the line along the real travel corridor.
- **Interactive itinerary panel.** A glassmorphism sidebar lists all eight days. Clicking a card flies the camera to that stop.
- **Lightweight.** The route is drawn directly from the itinerary coordinates, with no external routing calls, so it appears instantly.
- **WordPress-ready.** Styles are scoped to a single container, so the code can be pasted into a Custom HTML block.
## Tech stack
 
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/) v3.9.0
- Vanilla JavaScript, no build step
- Plus Jakarta Sans (Google Fonts)
## Usage
 
1. Copy the HTML into a WordPress **Custom HTML** block or any web page.
2. Replace the Mapbox access token with your own and restrict it to your domain in your [Mapbox account](https://account.mapbox.com/access-tokens/).
3. Adjust the container height in `.wp-safari-itinerary-container` to fit your layout.
To change the route, edit the `itineraryData` array. Entries with `isWaypoint: true` shape the route only. All other entries get a marker and a sidebar card.
 
## About
 
Built for [Safari Kenia](https://safarikenia.com.pl/), Polish-language safari tours and travel guides for Kenya.
 
➡️ [View this Lake Naivasha & Masai Mara itinerary](https://safarikenia.com.pl/jezioro-naivasha-maasai-mara/)
