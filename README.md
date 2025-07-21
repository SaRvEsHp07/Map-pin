# Map Pin Tool

A simple interactive map tool that allows users to drop pins, enter remarks, and optionally fetch addresses using coordinates. Useful for visualizing and annotating custom locations on a map.

### Demo
[Click here to watch the demo](https://www.loom.com/share/1b2916e0e22b4544b54d3067313af794?sid=5152e310-0b7d-4dce-b370-4c624a585178)

---

###  Features

- **Interactive Map Interface**  
  Users can drop pins anywhere on the map.

- **Add Remarks**  
  A popup allows users to add notes to each pin.

- **Address Fetching** *(optional)*  
  Automatically retrieves address using pin's lat/lng via OpenStreetMap (Nominatim API).

- **Local Storage Support**  
  Pins, remarks, and addresses are stored locally for persistence.

- **Sidebar Listing & Navigation**  
  View all saved pins in a sidebar and navigate to each by clicking on them.

---

### Success Criteria

- Easy-to-use map interface.
- Pins with remarks and optional addresses.
- Persistent data using local storage.
- Sidebar to manage and revisit saved pins.

---

### Tech Stack

- React
- Leaflet.js
- OpenStreetMap API
- Local Storage

---

### Setup

```bash
npm install
npm run dev
