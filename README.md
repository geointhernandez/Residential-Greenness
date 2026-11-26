# Residential-Greenness
Python source code for calculating distances between homes and parks in the municipality of Mérida, Yucatán

The calculation of distances between residences and parks in the municipality of Mérida, Yucatán, was performed using Euclidean distance, based on geodataframes containing location data for both residences and parks.

The locations of the residences were obtained via Google Maps services, using addresses provided by participants in a mental health survey. Park locations were sourced from the DENUE (National Directory of Economic Units – INEGI).

To calculate the minimum distance between a residence and a park, the `sjoin_nearest()` function in Python was used.
To determine the number of parks within a maximum distance of one kilometer from each residence, the `sjoin()` function in Python was employed, with a defined buffer of 1 km.
