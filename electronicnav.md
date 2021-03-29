# Electronic navigation
* Vector charts
  - can zoom in and out
  - hide information
  - show information
  - click on markers to get more information
* Raster charts are just straight copies of a paper chart
* brands of GPS:
  - GPS
  - Glonass
  - Beidou
  - Galileao
* terms
    - WPT - waypoint
    - COG - course over ground
    - SOG - speed over ground
    - TTG - time to go
    - BTW - baring to waypoint
    - DTW - distance to waypoint
    - XTE - cross track error (error to port or starboard of ground track to waypoint) (sometimes activated using 'rolling road mode' or 'cross track error mode')
    - ETA - estimated time of arrival
    - VMG - velocity made good (speed at which you are closing on your destination)
    - HDOP - horizontal dilution of precision (a scale 0-10 measuring how accurate your position is - higher values are a worse position 9+ cannot be relied upon)
    - proximity waypoint - an anti waypoint - something to avoid - a waypoint with a defined circumference that will trigger an alarm if GPS detects that you have strayed into that area
* always back up GPS position with visual fix (at least every hour)

## Outputs
* Vessel position
* Maybe cursor position too (careful not to mix these up)
* SOG
* COG (variation can be keyed in if you want)
* Depth
* Time (time can be set to any time zone)
* MOB mode indicator
* Water track - called heading on a GPS plotter
* Ground track
* Intended ground track to waypoint
* Hovering the cursor over chart features gives details of the features, such as colour, IALA system, pattern, topmark, lights and sounds
* BTW - bearing to waypoint
* DTW - distance to waypoint
* Warnings for areas to avoid
* Trip - how far we have gone since we last reset the trip, this is not the same as the log, which keeps counting up continuously as measured by an impeller
* ETA - estimated time of arrival
* TTG - time in minutes to get there
* VMG - speed at which you are closing on your destination, this is really handy when tacking
* AIS overlay - highlighting potential danger vessels
* Radar overlay - showing land against chart, buoys as blobs (the width of the bandwidth, the smaller the radar the bigger the band, the further away the radar, the bigger the band), ring width, VRM (variable range marker) which is a circle placed around the radar that can be lined up against markers ont he chart to get range, EBL (electronic bearing line) a straight line bearing, using the VRM and EBL we can do a radar plot of our position getting the distance and the bearing to the marker
* Display - either 'north up', 'head up' or 'course up' (or for radar 'RM' - relative motion) - this is the orientation of the display
* Triangle with exclamation mark - physical danger to boat requiring further investigation
## Configuration
* Units of distance, speed, depth etc. Can be set
* Geodetic datum can be set
* Variation can be specified
* How close you have to be to waypoints before they are marked as being visited
## Functions
* You can enter in a route using waypoints
  - this can be done manually, if so then it's worth placing the waypoints somewhere close to something that we can measure against eg. Contor or charted mark
  - auto-route will plan a route for you if you enter in your hull depth, most GPS versions will not be able to adjust for tide and tidal streams
  - waypoints are marked as reached if you get close enough to them (distance configurable) or if you click advance waypoint
  - waypoints can be positioned using lat and long, the cursor or current position of the boat
* Split screen mode showing more information on one side than the other
* 'Go To'
  - place one waypoint at the end of your journey
  - drag ground track around to avoid obstacles
* Man over board mode
  - press the MOB button as soon as someone goes overboard
  - this starts a counter, place a marker on the chart, give the lat and long, output a range and a bearing to the marker and sound a continuous alarm
  - some sophistocated GPS units can also move the marker with the assumed tide
## Errors
* position fix lost
  - aerial needs to be as low as possible to prevent signal bounce (bouncing off the water before it gets to the receiver) this means it can sometimes be knocked
  - could have been turned off by the US
  - could be interference with a mobile phone
