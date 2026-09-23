# Malawi USAID Flood Response – Water Point Assessment 2019 - 2020

This dataset contains detailed field-level information on the status and
functionality of rural water points across Malawi, collected as part of
the USAID Flood Response initiative between 2019 and 2020. The data was
gathered using the mWater mobile data collection platform, enabling
standardized, GPS-tagged assessments directly from field locations.

## Usage

``` r
floodresponsemw
```

## Format

A tibble with 684 rows and 45 variables

- submitted_on:

  Date when the water point assessment form was submitted.

- water_point_name:

  Name or identifier of the water point site.

- latitude:

  Latitude coordinate of the water point location.

- longitude:

  Longitude coordinate of the water point location.

- total_users_of_water_point:

  Number of people currently using the water point.

- water_point_photos:

  Photos taken to show the current condition of the water point.

- likely_submerged_during_flood:

  Whether the water point was likely submerged during recent flooding
  (Yes or No).

- evidence_submerged:

  Evidence observed that the water point was submerged.

- evidence_not_submerged:

  Evidence observed that the water point was not submerged.

- functional_status:

  Current operational status of the water point.

- pumpable_at_visit:

  Whether water could be pumped during the visit (Yes or No).

- reported_problems:

  List of problems reported or observed (e.g., broken parts,
  contamination).

- reported_problems_other:

  Additional problem descriptions not in the predefined list.

- water_quality_problems:

  Specific issues related to water quality (e.g., bad smell, taste,
  turbidity).

- civil_works_problems:

  Structural or construction related issues affecting the water point.

- civil_works_photo:

  Photo documenting the civil works issue.

- pump_problems:

  Mechanical issues related to the pump (e.g., broken handle).

- pump_problems_other:

  Additional pump issues not listed in predefined options.

- pump_problems_photo:

  Photo documenting the pump issue.

- pump_operational_feel:

  Assessors impression of the pumps functionality during operation.

- time_to_pump_20l:

  Time taken to pump 20 liters of water (in seconds).

- strokes_to_yield_water:

  Number of strokes required to start yielding water.

- sediment_presence:

  Whether visible sediment was present in the water.

- electrical_conductivity_magnitude:

  Measured electrical conductivity value of the water.

- electrical_conductivity_units:

  Units used to measure electrical conductivity (e.g., uS/cm).

- total_dissolved_solids_ppt:

  Total dissolved solids in parts per thousand (ppt).

- ph:

  pH level of the water sample.

- fluoride_ppm:

  Fluoride concentration in parts per million (ppm).

- ammonia_mg_per_l:

  Ammonia concentration in milligrams per liter (mg/L).

- nitrate_mg_per_l:

  Nitrate concentration in milligrams per liter (mg/L).

- free_chlorine_mg_per_l:

  Free chlorine concentration in milligrams per liter (mg/L).

- arsenic_magnitude:

  Measured value of arsenic in the water.

- arsenic_units:

  Units used to measure arsenic concentration.

- turbidity_magnitude:

  Turbidity level measured using a turbidity tube.

- turbidity_units:

  Units used for turbidity measurement (e.g., NTU).

- temperature_magnitude:

  Temperature of the water sample (numeric value).

- temperature_units:

  Units used for temperature (e.g., degree Celcius).

- temperature_time:

  Time the temperature was recorded.

- comments:

  Additional remarks or observations by the enumerator.

- sample_type:

  Type of water sample collected (e.g., raw, treated).

- sample_date:

  Date the water sample was taken.

- mpn_100ml:

  Most probable number (MPN) of bacteria per 100 ml of water.

- upper_95_ci_100ml:

  Upper 95 percentage confidence interval of MPN per 100 ml.

- health_risk_category:

  Risk classification based on MPN results (e.g., low, medium, high).

- color_change_image:

  Image showing color change in test compartments used for bacterial
  analysis.
