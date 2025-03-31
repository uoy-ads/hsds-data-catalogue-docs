# The Resource page
Clicking on the title of a resource from the Search results page will display the metadata record and all associated information for that resource on a new web page. At the top of the page, the resource’s location is shown on a map where zoom in and out can be done using the ‘+’and ‘-‘ icons on the right hand side. The is also the option to change the layers. Below these icons there is a further rectangular icon which is a pop-up menu with options for changing the size of the dislayed map, these being small (default), medium and full screen. 

![Alt text](../assets/32-Resource_top.png){ width="850" }
<p align="center"><I>Top part of the Resource page</I></p>

[This example](https://portal.ariadne-infrastructure.eu/resource/24d2b18c2f6c0ebe0d3ad5eb5238028efa63d8f03cdd9a7a8c210cd94ae1c1be) is from the DIME database and since it is a find, the location is shown as an approximate area where this particular coin was found. The Geo shape indicates that there is at least one other find nearby and clicking on it will display the relevant record. Multiple finds are displayed in sequence (i.e. click through one at a time) to avoid displaying multiple bounding boxes. The rest of the Resource page is shown below - this collection also has images of the finds so the resource data includes thumbnails pictures.

![Alt text](../assets/33-Resource_bottom.png){ width="850" }
<p align="center"><I>Remaining part of the Resource page</I></p>

The map can be enlarged by clicking on the frame icon below the Zoom icons to display the Map size menu as shown here. The size of the map on the resource page  can be increased (and reduced) using the Medium and Full Screen options, the default setting being Small.

## Display of near-by resources on the map

For each record for an individual resource, the map may also display Geo points or shapes for other resources located close by which are included in the returned search results. In the example below, the search term ‘Sword’ was used and this record (published by the National Monuments Service, Republic of Ireland) includes this word in the description of the Chest tomb panel that this record refers to (denoted by Geo shape with the red circle inset). Note that this resource would not be included in the search results if the Getty AAT term filter was used. There are several other sites and monuments of interest in this area, each denoted by a separate Geo shape. Clicking on any of the Geo shapes will display the associated resource.

![Alt text](../assets/34-Resource_map.png)
<p align="center"><i>[Chest Tomb](https://portal.ariadne-infrastructure.eu/resource/7c2db68bc992937c2c71040f9da411c0a6f75bb56d139b1570bdce84412502e4), Tralee, County Kerry, Ireland and other nearby resources</i></p>

The display of nearby resources can result in an approximate location shape for the current resource containing one or more icons (as well as close by) which refer to different nearby resources. In the following example, the resource map shown is for a Gold Quarter stater (resulting from a search for gold coins). There is no Geo shape for the coin as an approximate location is used as indicated by the red bounding box.  However, seven other nearby resources are shown as separate Geo shapes and each record can be displayed by clicking on the Geo shape associated with it.

![Alt text](../assets/35-Resource_bound_area.png)
<p align="center"><I>Approximate location of Gold Quarter stater shown by red bounding box along with nearby resources</I></P>

![Alt text](../assets/36-Resource_hide_nearby.png)
<p align="center"><I>Approximate location of Gold Quarter stater shown by red bounding box with nearby resources now hidden</I></P>

Nearby resources can be hidden and shown by clicking on the toggle Geo shape icon “Nearby resources”  on the left below the map. In the above example, only the approximate location of the resource is now shown after hiding the nearby resources. Note that where the location of a nearby resource is also defined by an approximate location, this is shown as a Geo point as displaying overlapping shapes would get messy. If there is more than one resource with an overlapping bounding box, only the next resource in the sequence is shown. Each (overlapping) resource may be displayed in turn by clicking through the sequence. 


