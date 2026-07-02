---
layout: default
title: Mapping San Diego Bicycle Risk
---

<style>
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  align-items: stretch;
}

.cards a {
  height: 100%;
  display: flex;
  flex-direction: column;
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

Built by a team of four using **ArcGIS** and **CARTO**, this project combines collision records and infrastructure data to visualize bicycle safety across San Diego County.

This project examines how infrastructure, weather, driver behavior, and alcohol involvement shape bicycle risk across the region. By mapping these patterns, the team highlights areas where cyclists may face the greatest danger and where safety improvements may be most needed.

## Project Goals

This project uses spatial analysis to better understand the factors that contribute to bicycle crashes and injuries. The goal is to identify patterns that can inform safer cycling conditions and more effective transportation planning.

---

Browse each team member's map below to explore a different dimension of bicycle safety.

<div class="cards">

<a href="./Sebastian/">
<img src="./assets/images/Sebastian.png">
<p class="credit">Image credits to https://www.pexels.com/photo/person-riding-on-bicycle-2972948/</p>
<h3>Map 1 — Bike Protection Gap</h3>
<p><b>By: Sebastian</b><br>
Explore how collision severity and bicycle infrastructure overlap to identify areas where cyclist safety may be most at risk.</p>
<p><b>Tools Used:</b><br>
ArcGIS</p>
</a>

<a href="./Devon/">
<img src="./assets/images/Devon.png">
<p class="credit"> /** blank for formatting **/</p>
<h3>Map 2 — Weather Conditions</h3>
<p><b>By: Devon</b><br>
Examine how weather conditions and collision severity relate to bicycle crashes across San Diego County.</p>
<p><b>Tools Used:</b><br>
ArcGIS</p>
</a>

<a href="./Isaac/">
<img src="./assets/images/Isaac.png">
<p class="credit">Image credits to https://www.pickpik.com/bike-blur-cars-city-cyclist-road-147367?__cf_chl_f_tk=oYMEpHTsNqb8dq15c2MmFZFusffvltTm3Xp_y.Ky3WE-1782955070-1.0.1.1-C2f7r9wY_zJpufrysAOyanHHPpuci.Ks_.vd4qRiPck</p>
<h3>Map 3 — Driver Behavior</h3>
<p><b>By: Isaac</b><br>
Analyze aggressive driving patterns and relationships with bicycle safety.</p>
<p><b>Tools Used:</b><br>
ArcGIS</p>
</a>

<a href="./Amy/index.html">
<img src="./assets/images/Amy.png">
<p class="credit"> /** blank for formatting **/</p>
<h3>Map 4 — Alcohol Involvement</h3>
<p><b>By: Amy</b><br>
Highlight the role of alcohol in bicycle collisions and show where injury risk is concentrated near areas with limited infrastructure.</p>
<p><b>Tools Used:</b><br>
CARTO</p>
</a>

</div>

## Data Sources

- [SWITRS — California Statewide Integrated Traffic Records System](https://iswitrs.chp.ca.gov): crash records used to identify collision locations, severity, and patterns.
- [City of San Diego Open Data Portal](https://data.sandiego.gov): local street and infrastructure data used to compare crash locations with existing bike facilities.
- [SANDAG Regional GIS Data](https://sandag.org): regional transportation and planning data used to contextualize the maps within the broader San Diego area.

---

## Tools Used

| Tool | Purpose |
|------|---------|
| ArcGIS | Used to build interactive dashboards and visualize collision and infrastructure patterns |
| CARTO | Used for web-based map visualization and spatial storytelling |
| GitHub Pages | Used to host and publish the project website |

---

## Team

| Name | Focus Area |
|------|-----------|
| Sebastian | Infrastructure and collision hotspot analysis |
| Devon | Weather conditions and crash severity patterns |
| Isaac | Driver behavior and road safety relationships |
| Amy | Alcohol-related collisions and injury risk |

---

*GEOG 583 · San Diego State University · Summer 2026*
