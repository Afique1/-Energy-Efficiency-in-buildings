# -Energy-Efficiency-in-buildings
This dataset contains information about 768 simulated residential buildings, each described  by architectural design parameters. The goal of this dataset is to predict how much energy  is needed to heat and cool the buildings under different design configurations.

| Column | Name                        | Description
|---|---|---|
| X1 | Relative Compactness | A measure of how compact the building shape is. Higher compactness often improves energy efficiency. |
| X2 | Surface Area (m²) | Total external surface area of the building. |
| X3 | Wall Area (m²) | Total area of the external walls. |
| X4 | Roof Area (m²) | Total roof area. |
| X5 | Overall Height (m) | Height of the building (either single-storey or two-storey). |
| X6 | Orientation | Building orientation: 2 = East, 3 = South, 4 = West, 5 = North. |
| X7 | Glazing Area (%) | Total area of windows as a percentage of the building's floor area. Values used are 0%, 10%, 25%, and 40%, representing the extent of window coverage. |
| X8 | Glazing Area Distribution | Describes how the glazing area is distributed across the sides of the building. Values range from 0 to 5, representing: 0 = No glazing, 1 = 55% North-facing + 15% others, 2 = 55% East-facing + 15% others, 3 = 55% South-facing + 15% others, 4 = 55% West-facing + 15% others, 5 = Uniform (25% on each side). This feature influences how sunlight enters the building and can be treated as categorical. |
| Y1 | Heating Load (kWh/m²) | Amount of energy required to heat the building. |
| Y2 | Cooling Load (kWh/m²) | Amount of energy required to cool the building. |

