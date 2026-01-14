# WME Segment Node Count Script

This script shows the number of geo-nodes in a given selection of segments, 
within the segment attribute panel of Waze Map Editor (WME), 
under additional attributes section at the bottom.

It warns if a segment is too complex (i.e. has too many nodes), which will prevent
it from being saved on the Backend.

Warnings are shown (once per 30 seconds block) when one of the selected segments 
exceed the soft-threshold of 450 nodes.

Danger notification is shown when exceeding the hard-threshold of 500 nodes.

## Installation
Install from GreasyFork: https://greasyfork.org/en/scripts/562605-wme-segment-node-count

Or manually from GitHub releases: https://github.com/darkfishtech/WME-Segment-Node-Count/releases

## Screenshots

Segment with normal node count

![Normal Node Count](img/wme-snc-normal-count.jpg)

Segment with high node count (warning)

![High Node Count](img/wme-snc-warning-display.jpg)
![High Node Count Notification](img/wme-snc-warning-notification.jpg)

Segment with too high node count (danger)

![Too High Node Count](img/wme-snc-danger-display.jpg)
![Too High Node Count Notification](img/wme-snc-danger-notification.jpg)

New or Merged segment with too high node count (danger)

![New/Merged Segment with Too High Node Count](img/wme-snc-danger-display-new-segment.jpg)
![New/Merged Segment with Too High Node Count Notification](img/wme-snc-danger-notification-new-segment.jpg)
