# SDS 110 Lab 2

## WHO
Patrick Moore, SDS 110, University of Zurich.  
Historical map from the U.S. Army Map Service.  
Modern imagery from Google Satellite.

## WHAT
Land area added to Heimaey by the 1973 Eldfell eruption, about 1.76 km².  
Data used: a georeferenced 1950 AMS map (1:50,000, Series C762) and two digitized island polygons (one for 1946 and one for today).

## WHEN
Historical map based on 1945–46 aerial photography.  
Eruption in 1973.  
Modern imagery from 2026.

## WHERE
Heimaey, Vestmannaeyjar, Iceland (63.43 N, 20.27 W), eastern coast.

## WHY
To measure how much new land the eruption created.

## HOW
In QGIS: georeferenced the old map (Thin Plate Spline), digitized the old coastline, reshaped the eastern edge to match modern imagery, then subtracted the two areas.
