# Identifying-Nightlife-Hubs-in-NYC
Spatial autocorrelation analysis to identify hotspots for nightlife activity using taxi trip data, seatgeek events data, and yelp bar location data. Seatgeek and Yelp data were accessed via API and taxi trips were sourced from OpenData NYC. Initially spatial autocorrelations (local and global) are performed on the data sets separately to identify clusters of nightlife activity. In an effort to consolidate, a kmeans clustering algorithm is implemented, however, the results are not intuitive - implying spatial autocorrelation is sufficient to identify nighlife activity.

Maps are included for visualization purposes.
