# Fixes
## General considerations
* Accuracy becomes less important the further away from danger you are
## Three point
### Things to note
* If it's a dangerous area you may need to 'hove-too' (stop) to take bearing, but if safe you can take it underway.
* Picking a marker:
  - markers that are close to each other are useless as they create large margins of error
  - reciprocal markers (ones that are either side of the boat) may not converge to a point, meaning the fix doesn't work
  - markers that are too far away cause fixes that have too large an error
  - if there are no artificial markers you can use the edges of land
  - using stuff that is fixed in the bottom of the sea is much better than buoys and non-fixed structures
### How to do it
1. Pick three markers
2. Note the time that you took the bearings
3. Note your log reading - how far you've travelled through the water
4. Note the depth (to check that makes sense once plotted on the chart)
5. Take bearings of markers - note that using a hand compass means that no deviation is assumed so the bearing reading is magnetic (M).
  a) take bearing of marker that is going to change most given your current heading (so the thing at a lateral orientation to your current direction of travel)
  b) next take a bearing of the next most affected marker
  c) last bearing should be taken of the marker that is most on your beam
6. Convert from magnetic to true by applying variation
7. On the chart
  a) draw lines that represent the bearings with arrows pointing away from the markers
  b) circle the position of the boat - in the resulting triangle mark the estimated position of the boat in the middle of that triangle, unless there is danger nearby, in which case you note the position of the boat to be the point in the trangle closest to the danger.
  c) at this point check that the depth makes sense (roughly working out tidal height above chart datum for that time of day) this is just a sense check
  d) note the time
  e) in brackets beneath the time, note the log reading
## Two points
* Also use the depth
* In this case you can
  1. take the bearings of the two points
  2. work out the tide
  3. measure the depth and plot depth 'reduced to soundings' (chart datum)
  4. mark depth on chart with
      - arrows on two bearings
      - arrows on contour
      - mark time and log on chart as normal
## Other methods
* If you're right next to a charted mark then it is simple to mark that position on the chart
* Use a transit
  1. on the chart draw a line straight through the two markers in the transit - this means you are definitely on that line
  2. use one more marker to get a cross on that line - this is accurate at least in one dimension
* Use GPS (making sure 'horizontal datum' type matches chart), as an alternative to using the lat and long, you could:
  1. mark current waypoint on chart (square with cross through it)
  2. use the bearing to waypoint output to draw line at bearing orientation coming from line
  3. use distance output from the gps to measure how long along the line we are

## Dead reckoning
### Tracks
#### Water track
* represents the direction sand distance travelled through the water, at the end of this track is the 'dead reckoning' this is represented on the chart by a small perpendicular line through the water track
* represented on the chart by a line with one arrow pointing along it
#### Tidal track
* represents the direction of tide plus distance that an object would be moved by tide of the time period
* represented on the chart by line with three arrows on it
* for time periods that are >1hr or that run into the next tidal period (1, 2, 3 hours after high water) use a composite tidal track, draw
#### Ground track
* the direction and distance travelled over the ground or over the surface of the planet - always a combination of what the boat does through the water plus what the tide is doing
* represented on the chart by a line with two arrows pointing along it
### Estimated position (EP)
* this is the position at the end of the ground track and is the estimated position on the chart of the boat
* represented on the chart by a dot with a triangle round it
* must also record time and log reading next to the EP on the chart
* COG is 'course over ground' and is the heading that is estimated to have been travelled over the surface of the earth
* SOG is 'speed over ground' and is the speed that is estimated to have been travelled over the surface of the earth
### Projected EP
* this is exactly the same as a normal EP except that the speed is an estimate given wind and all available information
### Circle of uncertainty (not in day skipper paper)
* there are a lot of potential errors with EPs
  - the log might be incorrect
  - the helmsman won't be able to secure an accurate course
  - leeway will be inexact
  - tidal streams are inexact
* depending on a judgement of the above factors we estimate the error as either 5, 10 or 15% of the distance travelled over water (so taken as a percentage of the water track) - this is represented as circle around the EP on the chart
* circle of uncertainty must not touch a dangerous area marked on the chart because this means we cannot be sure that the boat is not in danger
### Leeway
* this is the effect of getting pushed sideways by the wind (whilst being being close hauled or on a reach - does not occur on a broad reach)
* this is difficult to measure and so is often 'best guess'
* leeway is measured in degrees and is a direction
* when the wind is ahead of the beam, the leeway effect is strongest because the boat is heeled over and so the keel is doing a poorer job at keeping the boat from going sideways
* wind can be drawn on the chart for ease of calculation
* always apply leeway after variation
* leeway can only be worked out from comparing a fully adjusted estimated COG and actual COG
* leeway is reflected into the water track - this is the line on the chart that is adjusted for leeway

## Course to steer
* the course to steer is the course that gives the fastest path between two points
* the key things that we are interested in in terms of course to steer are
  1. the course to steer
  2. the SOG
  3. the time
* to work this out:
  1. work out how far the distance is between the two points (A to B)
  2. write down the distance and the boat speed
  3. decide on the duration of plot - choose half an hour, 1 hour or multiples of hours (do this to avoid complicated mathematics)
  4. draw a ground track between the two points (and then beyond the later point)
  5. find the tide for the time period
  6. draw the tidal track eminating from the start point
  7. work out how far along the ground track you will travel in the time period (0.5hrs, 2, 3, 4... hours)
  8. draw the water track between the position on te ground track that you will hit after the time period and the end of the tidal track
  9. the length of this line is the SOG
  10. the angle of this line is the true CTS (must adjust this for variation and leeway to get a course to )
  11. get the time it will take to get from one point to another by
    a) measuring the distance along the ground track between the two points
    b) dividing that by the SOG
  12. once we have worked out all of this we can get rid of the water track and the tidal track because we have the information we needed
  13. if speed differs significantly from what we had thought then we were going to do then we will need to revise our course to steer
* for time periods <= 1 hour the course to steer gives a course that keeps the boad on the ground track
* if the course to steer is worked out over two hours, then the boat will not stay on the ground track, it will deviate from the ground track before returning back towards it

## Cross chanel course to steer (will not be tested for day skipper)
* to find the fastest possible course to steer across the channel, rather than drawing a huge horrible composite tidal track, use a rough aggregate using the following process:
  1. draw ground track
  2. establish what speed you are going to go
  3. work out tide that you are going to face hour by hour by hour using a piece of paper
    a) mark on a piece of paper nautical mile intervals representing the hours of the passage
    b) on the first page, place the piece of paper on the rough course and note the speed and the direction of the tide
    c) do the same on the next page and so on and so on until you have speeds and directions for all hours of the journey
  4. then going back to the ground track, mark the arrows on the chart, either side of the ground track
  5. tally up the tidal speeds on each side of the ground track
  6. the difference between the two tallys is the aggregate tide for the whole time
  7. the aggregate is the tidal track for the entire journey
  8. draw the water track
  9. consider the rough true ground track to investigate dangers that might be encountered - if there are no dangers on this ground track then we accept that we will be dragged about with the tide and use this as our course to steer. To do this use composite tidal tracks layered on top of the course to steer. Do this every few hours
* note that if it's going to take you 12 hours to get anywhere then steering the ground track course will be a safe bet because the tides will cancel out (6 hours one way, 6 hours the other)
* if there is uneven number of hours in each direction then always better to aim to be slightly upstream of the location tide wise, otherwise the final few miles will be spent battling tide to get to the location.

## Pilotage
### General
* GPS not always most useful for smaller scale navigation, often have to resort to traditional methods
* always look at the pilotage notes in the Almanac
* the shell channel pilot is also useful to have on board (there are different pilot books for different areas) this book has photographs of what the important markers on the chart look like as well as detailed notes and more useful pictures of the area
### Plans
* define a starting point first in safe water
* useful to have a pilotage plan which is essentially a drawing of the area with:
  - prominent markers
  - courses
  - transits marked
  - bearings
* as an alternative you can use a 'rolling road'
  - draw two tram lines
  - either side of the tram lines draw what you will see
  - in the center of the tram lines note the bearing
  - can draw contours on next to the tram lines
* another alternative is just to have bullet pointed instructions
### Tactics
* forward bearing
  1. take a bearing of a prominent marker on a line that avoids danger
  2. keep the bearing constant to avoid the dander
  3. make course alternations:
    - if bearing increases must turm to starboard
    - if bearing goes down must turn to port
* back bearing - same process as forward bearing but taken from behind instead of the front
  - if bearing increases, turn to port
  - if bearing decreases, turn to starboard
back bearings are a really good option because it is usually taken based on markers that we have recently passed and so we can easily identify
* cross bearing - wait for bearing on a marker to read a defined level, once it hits this level then make course alteration and proceed on new forward/back bearing
* clearing bearing - define a bearing on a prominent marker beyond which it is not safe to proceed
* tacking cone - two clearing bearings funelling in between zones of danger
* transit - whether set up or made up by us, keep two points in line to mark a safe path
* depth contours - use two contours to mark a safe path, useful when in a channel, in this case choose the starboard side rather than the centre so that you know which way to turn when the depth starts getting shallower
