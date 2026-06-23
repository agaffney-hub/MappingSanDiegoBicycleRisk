---
layout: default
title: Map 2 — Weather Conditions
---

<style>
.iframe {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.iframe a {
  display: block;
  text-decoration: none;
  color: inherit;
  border: 1px solid #ddd;
  padding: 1rem;
}

.iframe img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
}

.iframe p.credit {
  font-size: 0.75rem;
  color: #666;
}
</style>

# Map 2 — Weather Conditions
### By Devon

> An interactive web mapping project exploring where, when, and why cyclists face the greatest risk across San Diego County.

Built by a team of four using **ArcGIS** and **Leaflet**, this project combines collision records and infrastructure data to visualize bicycle safety across the county.

---

<div class="iframe">

<iframe src="https://sdsugeo.maps.arcgis.com/apps/dashboards/3329512e13ec4e16a0c4d38dbb4904ff" width="200%" height="600px"
frameborder="0"></iframe>