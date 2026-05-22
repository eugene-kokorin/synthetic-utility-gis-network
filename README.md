# synthetic-utility-gis-network
Synthetic GIS-based energy distribution network model created in QGIS for infrastructure and topology practice.
## Project Overview

This project represents a synthetic medium- and low-voltage electrical distribution network created in QGIS for GIS infrastructure practice and topology modeling.

The model includes:
- HV/MV substation (110/22 kV)
- MV distribution substations
- MV feeders 22 kV
- LV distribution lines 0.4 kV
- Power poles
- Consumer connection points

All infrastructure objects, attributes, IDs, and technical parameters are synthetic and created for educational and portfolio purposes only.

---

## Technologies Used

- QGIS
- GeoJSON
- CSV
- OpenStreetMap
- QuickOSM
- Python (basic data generation)

---

## Topology Validation Principles

The project follows basic utility GIS topology rules:

- MV and LV lines must maintain geometric continuity
- Power poles act as network connection nodes
- Feeders must terminate at valid infrastructure objects
- Consumer branches must remain connected to LV distribution lines
- Synthetic asset IDs and attributes follow utility-style hierarchy logic

The model is designed for GIS infrastructure practice, topology understanding, and utility data structuring.

---

## Project Status

LEVEL 1 — Basic synthetic utility network modeling.

Focus:
- topology logic
- utility hierarchy
- GIS data structure
- infrastructure visualization

---

## Coordinate Reference System

EPSG:3857 / EPSG:4326

---

## Author

Eugene Kokorin
GIS & Infrastructure Data Specialist
