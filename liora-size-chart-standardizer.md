---
name: liora-size-chart-standardizer
description: Maps LIORA GRAND footwear styles (Heels, Flats, Sandals, Loafers, Sneakers) to exact Women's (EU 36-41) and Men's (EU 40-45) foot length measurements in centimeters (cm), UK, and US equivalents. Use when generating, standardizing, or validating footwear size charts and fit notes for Liora product records.
---
# Liora Size Chart Standardizer

Standardize footwear size charts across Women's (EU 36-41) and Men's (EU 40-45) collections with exact EU, UK, US, and centimeter (cm) foot length conversions.

## Verification & Execution Procedure

1. Read the gender/collection target (`Women` or `Men`), footwear sub-category (`Heels`, `Flats`, `Sandals`, `Loafers`, `Sneakers`), and sole mould type from the draft product record.

2. Attach the corresponding standardized **LIORA GRAND Size Mapping Table**:

### Women's Footwear Size Chart (EU 36 - 41)

| EU Size | UK Size (Women) | US Size (Women) | Foot Length (cm) |
| :--- | :--- | :--- | :--- |
| **EU 36** | UK 3 | US 5.5 | 23.0 cm |
| **EU 37** | UK 4 | US 6.5 | 23.5 cm |
| **EU 38** | UK 5 | US 7.5 | 24.0 cm |
| **EU 39** | UK 6 | US 8.5 | 24.5 cm |
| **EU 40** | UK 7 | US 9.5 | 25.0 cm |
| **EU 41** | UK 8 | US 10.5 | 25.5 cm |

### Men's Footwear Size Chart (EU 40 - 45)

| EU Size | UK Size (Men) | US Size (Men) | Foot Length (cm) |
| :--- | :--- | :--- | :--- |
| **EU 40** | UK 6 | US 7 | 25.0 cm |
| **EU 41** | UK 7 | US 8 | 25.5 cm |
| **EU 42** | UK 8 | US 9 | 26.0 cm |
| **EU 43** | UK 9 | US 10 | 26.5 cm |
| **EU 44** | UK 10 | US 11 | 27.0 cm |
| **EU 45** | UK 11 | US 12 | 27.5 cm |

3. Check the product notes for toe-box geometry:
   - If the product note specifies `"Narrow Toe Box"` or `"Pointed Toe"`, automatically append the fit advisory note below the table:
     > *"Fit Note: For wider feet, we recommend selecting one EU size up."*

4. Save the formatted size table and fit note into the draft product metadata.
