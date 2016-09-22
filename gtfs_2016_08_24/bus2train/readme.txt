Trains and buses calling at trains stations
Created using C:/data/dev/transport/openbus/gtfs/bus2train/calling_at_station.py
Date for data: 2016-09-01

GTFS data from: ../openbus_data/gtfs_2016_08_24

Walking distance file (for bus stops serving train stations: ../openbus_data/gtfs_2016_08_24/stop_station_walking_distance_350m.txt


Fields:
stop_id - MoT identifier of the bus stop or station. For trains, this is always the id of the station for buses it's the id of the bus stop
stop_code - another MoT identifier for the stop or station
line_number - for buses, line number presented to passengers (e.g. on bus signage)
route_desc - an MoT identifier of the bus or train route
route_long_name - the name of the route
arrival - time of arrival to station \ stop
departure - time of departure from station
pickup - 0 if pickup is allowed, 1 if it's a drop off only stop
dropoff - 0 if pickup is allowed, 1 if it's a pickup only stopstop_station_distance - staight line distance between the stop and the associated train station
google_walking_distance - walking distance to train station, calculated with google maps apigh_walking_distance - walking distance to train station, calculated with graph hopper api 