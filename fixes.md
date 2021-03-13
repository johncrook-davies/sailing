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
