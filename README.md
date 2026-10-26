# Soybean Canopy by Tillage

**Dr. Raziel A. Ordóñez**, Plant Scientist and Root Biologist

An interactive teaching model that shows how soybean plants grow, close their canopy, and senesce under four tillage systems (**plow, chisel, strip-till, and no-till**) in two cropping systems: **soybean after corn (rotation)** and **continuous soybean**.

Each plant is drawn from field-measured canopy cover (%) at each thermal-time sampling point (°C·d), and sized from measured plant height, main-stem nodes, branches, and pods per plant. Move the slider or press **Play** to watch the plants develop from emergence to maturity.

**Open the interactive page:** use the website link in the *About* section of this repository.

## Views

- **Rotation:** all four tillage systems, soybean after corn.
- **Continuous soybean:** all four tillage systems, soybean after soybean.
- **Compare: strip-till rotation vs no-till continuous:** two plants side by side.
- **Compare: plow rotation vs plow continuous:** two plants side by side.

## What students can explore

- **Plant development:** growth stages (VE to R8) advance with thermal time.
- **Plant size:** height, nodes, branches, and pods reach the measured values for each tillage and cropping system.
- **Leaf area:** canopy cover is converted to leaf area index, which sets leaf size on each plant.
- **Canopy closure:** when each system reaches 50% and 90% cover.
- **Senescence:** how quickly leaves yellow and drop after peak cover.
- **Top view:** a 1.52 m strip of row filled to the exact measured cover.
- **Growth sequence:** plants side by side at 10 sampling dates.
- **Rotation effect:** the cover chart shows the selected system as solid lines and the other system as dashed lines.

## How the plants are built

| Component | Basis |
|---|---|
| Canopy cover | Measured treatment means, rotation and continuous soybean |
| Plant height, main-stem nodes, branches, pods per plant | Measured treatment means at maturity |
| Leaf area index | Beer's law: LAI = −ln(1 − cover) / k, with k = 0.5 |
| Leaf area per plant | LAI × 286 cm² (35 plants/m²) |
| Height over time | Logistic curve ending at the measured height |
| Main-stem nodes | One new trifoliate every 55 °C·d until the measured node number |
| Branches | Whole branches for the integer part of the mean, one shorter branch for the fraction |
| Pods | Measured number shared among main-stem and branch nodes, appearing from R3 |
| Reproductive stages | Assumed: R1 540, R3 720, R5 950, R6 1150, R7 1480, R8 1640 °C·d |
| Leaf drop | Fraction of peak LAI lost after peak cover; oldest leaves drop first; unifoliates drop at V5–V6 |
| Soil | Drawn as a Mollisol (dark, organic-rich surface horizon) |
| Surface residue | Illustrative only. Rotation (corn residue): plow ~5%, chisel ~30%, strip-till ~50%, no-till ~75%. Continuous (soybean residue): plow ~3%, chisel ~15%, strip-till ~25%, no-till ~40% |

Canopy cover and plant traits are field measurements (treatment means). Growth-stage timing, the shape of the height curve, leaf placement, and residue are modeled assumptions for visualization, not measured data.

## Use on any device

The page runs in any modern web browser on computers, tablets, and smartphones. No installation or account is needed.

## Copyright

© 2026 Dr. Raziel A. Ordóñez. All rights reserved. This model and its figures are provided for students enrolled in the course. Do not copy, modify, or redistribute without the author's written permission. See [LICENSE](LICENSE).
