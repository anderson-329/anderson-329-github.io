# botw-korok-path
BOTW map with numbered korok seed locations.
This project originated from Mr Cheeze botw-object-map.
Seed locations were extracted from map_locations.js.
Seed location at Shrine of Resurrection was used as the starting point (Korok 1).
Then for each seed, the closest unvisited seed was determined (Korok 2, Korok 3, etc.).
Seed locations then sorted from 1-900 and embedded in index.html as a var.
Map marker clustering disabled so all markers shown regardless of zoom.
There is also an index_shortest file which shows a starting point
that yields the shortest overall path.
This was developed by determining the overall path distance using each korok as
the starting point, then picking the starting korok yielding the shortest overall path.
