**How to use this file:**

Before anything, you will need to ensure you have the following files/csv's downloaded in the appropriate directories:
- **State.shp**
    - This contains the outline of NY, this will be used on the maps, creating a statewide border on the map for reference. This file can be found in the swrcc/Shapefiles GitHub section. You will need to make a directory called State_Shapefiles in python that you will then place this state shapefile into
- **Counties.shp**
    - Just like the state shapefile, this contains the borders of each NY county and will be placed onto the maps in the code. This can be found in the swrcc/Shapefiles GitHub section. Place into State_Shapefiles diretcory in python
- **NWS_COLORS.csv**
    - This file contains a way of decoding the nws warnings. The first column will have the code name and the 2nd will have the color hex code. This needs to be placed in a directory called "Decoder" 
- **VTEC_PHENOMENA.csv**
    - This file contains the decoder of the warning code and its name. The first column contains the two letter code and the 2nd contains what that two letter code means. This also needs to be put in the "Decoder" directory
- **VETC_SIGNIFICANCE.csv**
    - This file contains the way of decoding the level of the alert, like warning, watch, advisory, etc. This also needs to be placed in the "Decoder" directory.
 
Once you ensure all of the proper files are downloaded. You will need to set a date range. This will be done by changing the start date and either changing the end date or comment the end date out and uncomment the other end date out and allow it to be now (most recent)

This code will make you a map for the desired warning as well as a combined map of all of the warnings in the shapefile (you still have to define which ones, just need to do it in the code).
