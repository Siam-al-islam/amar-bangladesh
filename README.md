# আমার বাংলাদেশ (Amar Bangladesh)

A single-file website: open `index.html` in any modern browser (double-click, or serve with any static host).

- No build step, no npm packages. Data is saved in the browser's localStorage.
- The Bangla font (Hind Siliguri) loads from Google Fonts, so it needs internet the first time. Offline it falls back to a system font.
- Map: currently an APPROXIMATE district layout, not real boundaries. To use real boundaries, open the page and use
  "মানচিত্রের ফাইল যুক্ত করুন" to load a 64-district GeoJSON (Polygon/MultiPolygon with district names).
  To bake real data in permanently, replace the `buildMap()` fallback in `index.html` with your GeoJSON.
- District places/foods are starter data in the `RAW` constant near the top of the script. Please review before publishing.
