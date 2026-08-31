# Earth Monitor

Real-time Earth & Space Weather Observatory

A single-file dashboard that monitors earthquakes, solar activity, ENSO (El Niño/La Niña), Schumann resonance, and seismic risk factors.

## Features

- **Earthquake Dashboard** — Live seismic data from USGS, EMSC, and GeoNet with interactive Pacific-centered map
- **Solar Activity** — Solar flares, CME alerts, Kp index, and live NASA satellite imagery
- **El Niño / La Niña** — ONI chart, Pacific SST anomaly map, and NZ-specific impact forecasts
- **Schumann Resonance** — Predicted SR spectrum based on solar-geomagnetic correlation model
- **Seismic Risk Factors** — Multi-factor model combining lunar tidal stress, geomagnetic activity, and SR anomalies

## Data Sources

- USGS Earthquake Hazards Program
- NOAA Space Weather Prediction Center
- NASA DONKI (CME/Flare data)
- NASA SDO & SOHO (Solar imagery)
- NOAA Climate Prediction Center (ENSO)
- GeoNet New Zealand
- EMSC SeismicPortal

## Setup

Just one file — open index.html in a browser or host it on any static web server. No build step, no dependencies beyond D3.js loaded from CDN.
