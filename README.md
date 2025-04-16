WIP  

I am trying to generate .gpx files sticking to my way of practicing gravel bike.  
I don't want technical singles, I don't want to have my derailleur soaking in the mud, I want to cover great distance taking tracks and paths
instead of road as much as possible. In cities, I want to avoid to go in reverse direction in one way streets. 
And I don't care that much about cycleways.

## Forbidden segments:

* bad paths:
  - paths with smoothness impassable/very_horrible_horrible
  - paths with sac_scale (Swiss Alpine Club 🇨🇭) difficult_alpine_hiking/demanding_alpine_hiking/alpine_hiking/demanding_mountain_hiking/mountain_hiking/hiking
  - paths with mtb_scale 2/2+/2-/3/4/5/6 or mtb_scale_uphill 2/3/4/5

* bad one ways:
  - everything when we are in reversed direction which is oneway=yes and not set specifically to no for bicycles
  - if we are in reversed direction in a roundabout/circular

* bad highway
  - footway/bridleway/pedestrian when bicycle is not set to yes
  - motorway/trunk/raceway/corridor because we don't want to die
  - bicycle=no

* no access:
  -all access marked as no/private with no exceptions for bicycles
