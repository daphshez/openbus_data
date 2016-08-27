Data created for\using the [Israel Open Bus](<https://github.com/hasadna/open-bus>) project.

Source 

## gtfs_2016_05_25
Derived data for the 2016-05-25 gtfs file. 

The original GTFS file (israel-public-transportation.zip) can be found [here](<http://gtfs.otrain.org/static/archive/2016_05_25_00_00_04/>). 

* route_stories.txt and trip_to_stories.txt: route stories, a compressed alternative to stop_times. See [```gtfs.parser.route_story```](<https://github.com/hasadna/open-bus/blob/master/gtfs/parser/route_stories.py>)
* stop_station_distance.txt: nearest train station to each bus stop, and the distance between them. Generated using ```gtfs.kavrazif.kavrazif.generate_station_distance```

## gtfs_2016_08_24
Same as gtfs_2016_05_25, different date.


## train_access_map_300m
Data used to create [this map](<http://arcg.is/29XN6km>), showing from where you can get to a train station in 30 an hour.   

Generated from 25-05-2016 GTFS data using the ```gtfs.kavrazif.station_access``` module.

* stops_and_stations.txt - a csv file with all bus stops linked to train stations. 
* stops_and_stations_*.txt - data filtered from stops_and_stations to create the actual map layers in the map.

## other
* train_stations.txt - list of train stations. The stop_id comes from the 2016-05-25 and may change, but the stop_code should always be correct.
