# placedata-2022
Data from r/place 2022


## Structure
The data is laid out as a CSV file, with three columns: timestamp, colour, and location.
- Timestamp is the UNIX timestamp at which the pixel was placed.
- Colour is an integer representing the colour of the pixel. To see what each integer means, consult the `colours.json` file.
- Location is a pair of X,Y coordinates for the location where the pixel was placed. In some instances, there may be 4 coordinates, X1,Y1,X2,Y2, which represents a moderator's use of a rectangle fill tool to remove inappropriate content.
