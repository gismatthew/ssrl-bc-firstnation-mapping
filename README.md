# BC First Nation Project
## Update the presentation maps

### Overview
Maps in David's slides need to be updated with latest dataset for the 2 first nations: SFN and WMFN.

### Tasklist
- 2 sets of maps for now
  - [] SFN
  - [] WMFN
- Next phase:
  - [] McLeod FN
  - [] total of 3 FNs
- Maps required
  - Total Harvest by Percentage and Weight
    - [] SFN
    - [] WMFN
  - SFN Total Harvest of Large Mammals
    - [] SFN
    - [] WMFN
  - Total Harvest of Small Mammals by Percentage
    - [] SFN
    - [] WMFN
  - Total Harvest of Fish by Percentage and Weight
    - [] SFN
    - [] WMFN
  - Total Harvest of Birds by Percentage
    - [] SFN
    - [] WMFN
  - Areas Used for Berry and Plant Harvesting
    - [] SFN
    - [] WMFN
  - Concentration/Distribution of Cabins and Camps
    - [] SFN
    - [] WMFN
  - Areas No Longer Used
    - [] SFN
    - [] WMFN
  - Hotspots maps for all harvest
    - [] SFN
    - [] WMFN

### Data

- Project folder is in `/Server/David/BCGIS/May2018/Finalize_SFN_WMFN`
  - This folder will be self-contained: all maps will reference data from this folder, instead of pulling data from other folders/gdbs of previous stages of this project.
- Matthew organized Abi's final Excel data.
  - What he did: split/remove cells according to our meeting with David
  - 4 `csv` files for WMFN
    - the `csv` contains data for mapping
    - some `csv` file has `txt` file of the same name. The `txt` has notes indicating what cells are spit/removed. In case of removing, we need to put a note in the map indicating a "undisclosed harvest".
----

## David's comments in the meeting
Here are David's comments he made in our meeting on May 1st, about the dataset and the maps. Note that Abi has addressed most, if not all, data related issues. Info listed here is our general guide for data QA and also serves as our future reference:
  - removing redundant species such as
    - 5 spp of grouses becomes 1 spp of grouse
    - only one trout
    - only one moose (no bulls nor cows)
  - grizzly bear is not foods, thus should it excluded
  - sheep is not goat
  - swans should be excluded, it is illegal to hunt them
  - moose is the most important
    - for food and culturally
    - we may want to make a moose-only map
  - no need to put weights on grids
  - hotspots here (SFN) are actually for moose and bison, not all species, due to their weights%
  - where is the distance map?
  - SSRL is encouraged to make awesome, creative maps
    - link 'zones no longer used' and 'disturbances'
    - future: online maps
    - future: disturbance maps
    - see how disturbances cause social impact (on cabins/camps etc)
  - fish maps:
    - they catch fish and some release due to potential pollution
  - household map
    - [] use zone# instead of household#
    - houses/huts are mainly used as base of hunting and recreation activity
    - raw data: more camps than cabins
  - [] multiple zones
    - if 2 next to each other, split them
    - if too big, (David) say > 4 grids, put a note, "undisclosed location"
  - [] plants
      - table shows all details (each spp)
      - map: berry picking, plant etc.
  - WMFN, SFN, combined, another community (McCloud) data coming soon
  - [] household# and their geolocation
    - social network map
  - some data on Alberta
    - to show on maps
  - [] food exchange
    - spp exchange
    - red going out caribou, blue going back salmon, distinguish by lines
  - more data coming
    - RSEA on pipelines, mines
      - Abby's is looking at the archived data
        - industrial development
      - Oil&gas dev in blueberry community
        - visualization overtime (50yr)
    - library UBC
      - Alaska pipeline 1980s project
    - compile data of various resolution, will be good
    - sport hunting locations in the past (registration)
      - David's hypothesis: white hunters pushing first nation hunters in the bush?
  - 3 presentations
    - make maps (3 communities)
    - David: maybe get rid of grid lines and see how it looks
    - try to finish it soon
