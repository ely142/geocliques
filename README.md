# GeoCliques

**GeoCliques** is a social, map-based web application where users can create and join "cliques" (groups), place markers on a map, leave reviews and events, and collaborate in a dynamic geospatial environment. The app includes user authentication, interactive mapping with custom icons, notifications, multi-layer map support, and full admin control over user content.

## Features

- **Interactive Map**: Add markers, view reviews, and schedule events directly on a Leaflet.js map.
- **Cliques System**: Create, join, or manage public, protected, and private cliques.
- **Review System**: Leave star ratings and optional commentary for each marker.
- **Event Scheduling**: Plan and view events tied to specific locations.
- **Notifications**: Receive and manage invitations, join requests, bans, and kicks.
- **Admin Control Room**: Manage clique membership, review content, and moderate user activities.
- **Custom Styling**: Dynamic marker icons, color-coded cliques, modern UI/UX styling.
- **Map Layers**: Switch between multiple map providers (OpenStreetMap, Esri Satellite, Thunderforest).

## Tech Stack

- **Backend**: Python, Flask, Flask-Login, Flask-SQLAlchemy, SQLAlchemy
- **Frontend**: HTML, JavaScript, CSS, Bootstrap
- **Database**: SQLite (local development), PostgreSQL (production)
- **Mapping**: Leaflet.js
- **Libraries**: RapidFuzz for search, Werkzeug for password hashing and verification


## Folder Structure

```
geocliques/
├── static/
│   ├── css/         # Stylesheets
│   ├── files/       # Images, logos, avatar pics (created using Canva and excluded from this public repo due to licensing restrictions), and other static media assets
│   ├── instance/    # Local development folder storing the SQLite database file (not tracked in version control or production)
│   └── js/          # JavaScript
├── templates/
│   ├── user/        # User-facing pages
│   └── master/      # Master facing pages
├── main.py          # Main Flask app
├── databases.py     # SQLAlchemy models
├── utils.py         # Helper functions (colors, deletion functions)
├── requirements.txt
└── README.md

```

**GeoCliques** – Proprietary License (Personal and Educational Use Only)

Copyright © 2025

All rights reserved.

This software and associated documentation files (the "Software") are the exclusive property of the copyright holder.

You are **permitted** to:

- View and use the Software for **personal**, **non-commercial**, or **educational** purposes only.

You are **NOT permitted** to:

- Copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.
- Use the Software for any **commercial**, **organizational**, or **public deployment** purposes.
- Reverse engineer, decompile, or disassemble any part of the Software.

Any use of the Software beyond these permissions requires prior, explicit, and written consent from the copyright holder.

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT.  
IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
