# Dust_PSD_Project
Data for dust particle size distribution analysis

## Authors

Nicholas P. Webb1*, Sandra L. LeGrand2, Bradley F. Cooper1, Ericha M. Courtright1, Brandon L. Edwards1, Christopher Felt2, Justin W. Van Zee1, Nancy P. Ziegler2

1 USDA-ARS Jornada Experimental Range, Las Cruces, NM 88003, USA

2 US Army Engineer Research and Development Center, Cold Regions Research and Engineering Laboratory (CRREL), 72 Lyme Rd, Hanover, NH 03755-1290, USA

## Created
Spring 2017/2018

## Purpose

This repository contains data used by Webb et al. for the manuscript "Size distribution of mineral dust emissions from sparsely vegetated and supply-limited dryland soils" submitted for publication in Geophysical Research Letters.

## Data

Measurements were collected during 10 dust emission events in March to May of 2017 and 2018 at three sites on the Jornada Experimental Range in south-central New Mexico, USA. The study sites were named Site 3 (playa), Site 4 (mixed bunchgrasses and forbs) and Site 5 (open shrublands), as described by Webb et al. (2016). 

Meteorological data were measured with centrally-located meteorological towers equipped with RM Young 3101 cup anemometers at heights of 0.7 m, 1.4 m and 2.4 m above ground level, and one RM Young 3002 anemometer and wind vane at 4.8 m height. Temperature sensors (Campbell Scientific 107-L) were mounted at 2.0 m and 4.0 m heights. Data were sampled at 1 Hz and were logged every 1 min on Campbell Scientific CR1000 data loggers. 

Dust concentrations were measured using a pair of optical particle sizer (OPS) spectrometers (TSI model 3330) mounted on a mast at 1.25 m and 2.5 m heights adjacent to the meteorological tower. The spectrometers were configured to measure count size distributions and reported concentrations for particles in 12 bins with diameters 0.3-0.5, 0.5-0.7, 0.7-1.0, 1.0-1.5, 1.5-2.0, 2.0-2.5, 2.5-3.0, 3.0-4.0, 4.0-5.0, 5.0-6.0, 6.0-8.0, 8.0-10.0 μm. 

Horizontal sediment mass flux was measured using five Modified Wilson and Cooke (MWAC) sediment samplers with inlet 2.34 x 10-4 m2 (Webb et al., 2019). Five freely rotating masts, each with four MWAC samplers (0.1, 0.25, 0.5 and 0.85 m above ground level) were located surrounding the meteorological towers. 

Transect data were collected on three parallel 50 m transects spaced 25 m apart with the central transect passing through the center of the fenced areas. On the morning of each dust event, methods of Herrick et al. (2018) were used to measure vegetation height, the size distribution of canopy gaps >=5 cm (unvegetated spaces between plant canopies), and foliar cover of vegetation by species and soil surface properties.

Data files include:
1. Event_Meteorological_Data_2017_2018.csv - This file contains raw meteorological data for each measured dust event.
2. OPS_Spectrometer_Data - This folder contains raw TSI Optical Particle Sizer (OPS) spectrometer data for each measured event from instruments mounted at 1.25 m and 2.5m above ground level.
3. 2017-2018 FINAL DIMA 5.3b as of 2018-10-23.mdb - This file is a MS Access database containing vegetation transect data collected for each measured dust event.
4. Event_MWAC_Data_2017_2018.xlsx - This file contains raw Modified Wilson and Cooke (MWAC) sediment sampler data for each measured dust event.

The following lists provide field definitions for the MWAC data and meteorological data.

### Event_MWAC_Data_2017_2018.xlsx

- Site - Study site name (general locality).
- Monitoring Plot - Identification of plot at which data were collected.
- Stack Location - Identification of MWAC mast (stack) location within plot.
- MWAC Height (opt) - Height (cm) above ground level at which inlet of MWAC sampler can was installed.
- MWAC Location - Descriptor of where on the MWAC mast a sampler (can) was installed.
- Box Type (Rotating or Static) - Differentiates whether the MWAC mast could freely rotate into the wind or if the mast was fixed to sample from a set azimuth.
- MWAC Internal Diameter - Internal diameter of MWAC sampler inlet (inches).
- Inlet Area (cm2) - Area of MWAC sampler inlet (cm2).
- Processing method (Wet/Dry) - Identification of whether a dry (sample tapped out of MWAC can into weigh boat) or wet (sample rinsed out of MWAC can into pre-weighed beaker then oven dried) sediment retrieval method was used.
- Drying Oven temp (c) - Temperature of oven at which samples were dried prior to weighing.
- Date Collected - Day, month and year on which the samples were collected in the field.
- No. days exposure - Number of days for which the MWAC samplers were in the field collecting sediment.
- Can No. - Identification number assigned to MWAC sampler can.
- Empty Boat wt. (g) - Weight of weigh boat (grams) without sediment sample (i.e., prior to weighing sample).
- Boat + sed. Oven dry wt. (g) - Weight of weight boat containing sediment sample (grams).
- Bulk Soil Sediment wt. (g) - Sediment sample weight (grams).
- Sediment archived (y/n) - Record of whether the physical sediment sample was stored or discarded.
- Collection Notes - Notes describing sample pertinent to data quality and interpretation.
- Sample Discarded (any non-blank means) - Record of whether the physical sediment sample was discarded.

### Meteorological data

- TIMESTAMP - Month/Day/Year (MM/DD/YYYY)and time (HH:MM) of observation.
- Event - Date (YYYYMMDD) on whcih dust event was measured.
- Site - Name of study site at which data were collected.
- Rain_mm_Tot - Total rainfall collected in 1 min logging period (mm).
- T107_2M_Avg - Air temperature (C) measured at 2 m above ground level.
- T107_5M_Avg - Air temperature (C) measured at 5 m above ground level.
- WS_ms_4.8m_Max - Maximum wind speed sampled at 4.8 m above ground level within 1 min logging interval.
- WindDir_D1_WVT	- Wind direction (vector) for 1 min loggin interval.
- WS_ms_4.8m_Avg - Average wind speed at 4.8 m above ground level within 1 min logging interval.
- WS_ms_2.4m_Avg - Average wind speed at 2.4 m above ground level within 1 min logging interval.
- WS_ms_1.4m_Avg - Average wind speed at 1.4 m above ground level within 1 min logging interval.
- WS_ms_0.7m_Avg - Average wind speed at 0.7 m above ground level within 1 min logging interval.
- WS_ms_2.4m_Std - Standard deviation of wind speed at 4.8 m above ground level within 1 min logging interval.

## References
Herrick, J.E., Van Zee, J.W., McCord, S.E., Courtright, E.M., Karl, J.W., & Burkett, L.M. (2018), Monitoring Manual for Grassland, Shrubland, and Savanna Ecosystems, Volume 1: Core Methods, Second EditionRep., USDA-ARS Jornada Experimental Range, Las Cruces, New Mexico.

Webb, N.P., Galloza, M.S., Zobeck, T.M., & Herrick, J.E. (2016), Threshold wind velocity dynamics as a driver of aeolian sediment mass flux, Aeolian Research, 20, 45-58.

Webb, N.P., Chappell A., Edwards, B.L., McCord, S.E., Van Zee, J.W., Cooper, B.F., et al. (2019), Reducing sampling uncertainty in aeolian research to improve change detection, Journal of Geophysical Research Earth Surface, 124, 1366-1377.
