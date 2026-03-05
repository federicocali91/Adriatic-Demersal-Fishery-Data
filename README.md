# Adriatic-Demersal-Fishery-Data
Datasets and code for: Fishery-dependent surveys reveal the spatiotemporal dynamics of four valuable demersal species in the Northern Adriatic Sea

-------------------------------------------------------------------------
METADATA DESCRIPTION - Northern Adriatic Fishery Dataset
-------------------------------------------------------------------------
Associated Publication: Fishery-dependent surveys reveal the 
spatiotemporal dynamics of four valuable demersal species in the Northern Adriatic Sea.
Authors: Calì F., Santon M., Cacciamani R., Raicevich S., Santojanni A.
-------------------------------------------------------------------------

DATASETS:
1. dataset_OTB.csv : Contains fishery-dependent data from Otter Trawlers.
2. dataset_TBB.csv : Contains fishery-dependent data from Beam Trawlers (Rapido).

Both files share the same structure and column headers described below.

COLUMN DESCRIPTIONS:

1. vessel_Id
   - Anonymized unique identifier for each fishing vessel.
   - Format: Categorical/Factor.

2. horizontal_net_opening_km
   - Effective horizontal width of the trawl net opening.
   - Unit: Kilometres (km).

3. duration_h
   - Duration of the fishing haul.
   - Unit: Hours (h).

4. speed_kmh
   - Average trawling speed during the haul.
   - Unit: Kilometres per hour (km/h).

5. effort
   - Swept area (fishing effort), calculated as: 
     (horizontal_net_opening_km * duration_h * speed_kmh).
   - Unit: Square kilometres (km^2).

6. depth
   - Sea bottom depth at the haul location.
   - Unit: Metres (m).

7. season
   - Sampling season (Spring, Summer, Autumn, Winter).
   - Format: Categorical (Factor).

8. species
   - Scientific name of the target species (S. officinalis, E. moschata, 
     S. solea, S. mantis).
   - Format: Latin binomial (String).

9. east_cs
   - Centred and scaled longitudinal coordinate used in the models.
   - Format: Numeric (Decimal).

10. north_cs
    - Centred and scaled latitudinal coordinate used in the models.
    - Format: Numeric (Decimal).

11. time_year
    - Temporal variable representing the year of the haul (2011–2019).
    - Format: Integer (YYYY).

12. catch_kg
    - Weight of the target species caught in the single haul.
    - Unit: Kilograms (kg).
