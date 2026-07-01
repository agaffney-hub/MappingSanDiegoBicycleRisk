---
layout: default
title: Mapping San Diego Bicycle Risk
---

<style>
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.cards a {
  display: block;
  text-decoration: none;
  color: inherit;
  border: 1px solid #ddd;
  padding: 1rem;
}

.cards img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
}

.cards p.credit {
  font-size: 0.75rem;
  color: #666;
}
</style>

# Mapping San Diego Bicycle Risk

> An interactive web mapping project exploring where, when, and why cyclists face the greatest risk across San Diego County.

Built by a team of four using **ArcGIS** and **Leaflet**, this project combines collision records and infrastructure data to visualize bicycle safety across the county.

---

<div class="cards">

<a href="./Sebastian/">
<img src="./assets/images/Sebastian.png">
<p class="credit">Image credits to https://www.flickr.com/photos/geckoam/2723280096</p>
<h3>Map 1 — Bike Protection Gap</h3>
<p><b>By: Sebastian</b><br>
Overlay collision severity hotspots against bikeways and bike infrastructure to examine whether severe cyclist injuries occur in areas lacking protection.</p>
</a>

<a href="./Devon/">
<img src="./assets/images/Devon.png">
<p class="credit">Image credits to https://www.pickpik.com/fuchs-funny-tongue-animal-world-wild-animal-wildlife-photography-114225</p>
<h3>Map 2 — Weather Conditions</h3>
<p><b>By: Devon</b><br>
Explore how weather conditions relate to bicycle collisions throughout San Diego County.</p>
</a>

<a href="./Isaac/">
<img src="./assets/images/Isaac.png">
<p class="credit">Image credits to https://www.needpix.com/photo/download/1867178/dog-funny-pet-animal-cute-puppy-happy-adorable-young#google_vignette</p>
<h3>Map 3 — Driver Behavior</h3>
<p><b>By: Isaac</b><br>
Analyze aggressive driving patterns and relationships with bicycle safety.</p>
</a>

<a href="./Amy/">
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
