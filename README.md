# New York Taxi Pickup and Drop-off Clustering Analysis
This project analyzes New York City taxi pickup and drop-off locations to identify high-demand hotspots and optimize fleet management and dispatch strategies. By employing DBSCAN (Density-Based Spatial Clustering of Applications with Noise), this study provides actionable insights into passenger travel patterns and resource allocation across the city.

**Project Overview**

The dataset contains 9,914 entries and 7 columns, including:

Key: Unique identifier for each taxi ride
Pickup Date and Time: Timestamp of the ride start
Pickup Coordinates: Latitude and longitude of the pickup location
Drop-off Coordinates: Latitude and longitude of the drop-off location
Passenger Count: Number of passengers per ride

Dataset Characteristics:
The data exhibits irregular shapes and varying densities, making DBSCAN an ideal clustering technique. DBSCAN groups closer points based on Euclidean distance and the minimum number of samples while effectively handling noise, which represents sporadic or unconventional rides.

Key Findings
Clusters and Insights

## Pickup Clusters:

Major clusters were identified in Manhattan (Cluster 0), Williamsburg Bridge (Cluster 2), and LaGuardia Airport (Cluster 3).
John F. Kennedy Airport (JFK) exhibited less dense activity for pickups and was not clustered effectively by DBSCAN.

## Drop-off Clusters:

Similar patterns were observed for drop-offs, with Manhattan, Williamsburg Bridge, and LaGuardia Airport showing high-density clusters.
Washington Heights (Cluster 1) emerged as a significant drop-off cluster, particularly due to its concentration of hotels and frequent drop-offs, despite being less active for pickups.
Travel Routes:

A prominent travel route exists between JFK Airport, LaGuardia Airport, and Manhattan.
These routes suggest consistent travel patterns between airport zones and Manhattan city, driven by high demand from passengers traveling to commercial and residential areas.
Passenger Count and Geographical Patterns:

Passenger count influences travel patterns within Manhattan, with specific areas like Central Park, Lower Manhattan, and New York Penn Station showing varying levels of activity.
Unique travel patterns also emerge around airports and bridges, highlighting their importance in city travel dynamics.
Temporal Variations:

Analysis of ride times revealed significant variations in demand across different days of the week, months, and seasons.
These patterns help pinpoint when and why taxi services are needed the most, improving fleet planning.

## Methodology
**DBSCAN Clustering:**

Used for identifying clusters of pickup and drop-off locations.

Parameters:
Epsilon (ε): Determines the neighborhood radius for clustering.
Minimum Samples: Minimum number of points required to form a cluster.
DBSCAN’s ability to handle noise is crucial for taxi ride data due to random or outlier rides.

Visualization:

Clusters for pickup and drop-off locations were visualized, highlighting high-demand areas.
Common travel routes were mapped to identify connections between key zones like airports and Manhattan.
Geospatial Analysis:

Focused on dense urban areas like Manhattan and specific hotspots like bridges and airports.
