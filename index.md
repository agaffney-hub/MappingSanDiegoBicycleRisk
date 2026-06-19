---
layout: default
title: Mapping San Diego Bicycle Risk
---

<style>
.cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
}

.cards a {
  display: block;
  border: 1px solid #ddd;
  padding: 1rem;
  text-decoration: none;
  color: inherit;
}

.cards img {
  width: 100%;
  height: auto;
}
</style>

# Mapping San Diego Bicycle Risk

> An interactive web mapping project exploring where, when, and why cyclists face the greatest risk across San Diego County.

Built by a team of four using **ArcGIS** and **Leaflet**, this project combines collision records and infrastructure data to visualize bicycle safety across the county.

---

<div class="cards">

<a href="./Sebastian/index.html">
<img src="./assets/images/page1.png">
<h3>Map 1 — Bike Protection Gap</h3>
<p><b>By: Sebastian</b><br>
Overlay collision severity hotspots against bikeways and bike infrastructure to examine whether severe cyclist injuries occur in areas lacking protection.</p>
</a>

<a href="./Devon/index.html">
<img src="./assets/images/page2.png">
<h3>Map 2 — Weather Conditions</h3>
<p><b>By: Devon</b><br>
Explore how weather conditions relate to bicycle collisions throughout San Diego County.</p>
</a>

<a href="./Isaac/index.html">
<img src="./assets/images/page3.png">
<h3>Map 3 — Driver Behavior</h3>
<p><b>By: Isaac</b><br>
Analyze aggressive driving patterns and relationships with bicycle safety.</p>
</a>

<a href="./Amy/index.html">
<img src="./assets/images/Amy.png">
<h3>Map 4 — Alcohol Involvement</h3>
<p><b>By: Amy</b><br>
Map alcohol-related bicycle incidents by location and timing patterns.</p>
</a>

</div>

## Data Sources

- [SWITRS — California Statewide Integrated Traffic Records System](https://iswitrs.chp.ca.gov)
- [City of San Diego Open Data Portal](https://data.sandiego.gov)
- [SANDAG Regional GIS Data](https://sandag.org)

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Leaflet | Interactive map rendering and layer control |
| Carto | Interactive map rendering, file processing and layer control |
| Mapbox | Basemap tiles and custom styling |
| GitHub Pages | Hosting and deployment |

---

## Team

| Name | Focus Area |
|------|-----------|
| Sebastian | Collision/Infrastructure hotspots |
| Devon | Weather/Public Safety Risk |
| Isaac | Events/Angry Driver risk |
| Amy | Alcohol Risk |

---

*GEOG 583 · San Diego State University · Summer 2026*
