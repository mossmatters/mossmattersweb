---
layout: protocol
title: "Georeferencing Guide"
tagline: "Georeferencing Guide"
handle: mossmatters
category: protocol
---

# Georeferencing Guide

### E.L. Reed Herbarium, Texas Tech University

*updated 10 October 2019*

--

## Introduction

Georeferencing is the process of adding latitude, longitude, and measurement uncertainty to biological collections that do not have GPS point. Most of the time this involves taking the description of a locality:

> "State highway 87, 1 mile northwest of Post on east side of the road"

and searching on a map for this location. There are automated tools for identifying approximate location, but these can be fooled by different ways of interpreting the locality data. Unfortunately, this resulte in a lot of bad georeferencing data for the TTC herbarium. For example, here is a map of all specimens that are supposed to be in Lubbock County, Texas based on label transcription:

![](/assets/images/protocols/lubbock_points.png){:class="img-responsive"}

This poses a problem when our data is aggregated with other herbarium data and a researcher wants to know about the range of a species. We've received comments such as "Could you check this specimen? It would be the furthest east it's ever been recorded...." Our task is to fix all of the coordinates to reduce these errors.






## How to get started

To Georeference on TORCH, you will need a TORCH account. [Go to this link](http://portal.torcherbaria.org/portal/profile/newprofile.php) to create a new account. You will then need to send your username to one of the TTC Herbarium admins to get permission to edit herbarium records.

Once you are logged into TORCH, go to your profile and click on "Edit Existing Occurrence Records." You will be assigned to a State and County to work on, which you will need to enter into the Record Search Form, along with a code that will allow you to view only the records that need editing. Use the pencil/plus sign icon to add multiple search filters.\


If you were assigned to Lubbock County, Texas, that will look like this:

![](/assets/images/protocols/record_search_form.png){:class="img-responsive"}





## GeoLocate

The GeoLocate app is used within the TORCH portal to georeference specimen data. Click on the "swirly globe" image

![](/assets/images/protocols/geolocate_button.png){:class="img-responsive"}


For the specimen listed above, GeoLocate did not do a good job incorporating the precise location, and instead placed a reference point in the centroid of Lubbock County, Texas:

![](/assets/images/protocols/lubbock_centroid.png){:class="img-responsive"}

Since there is an exact intersection within city limits, we can do a lot better than that! 
Pan and zoom around the map to find the exact point.
You can use the **Measure distance** button to get a ruler for estimating distances from landmarks.
Use the **Place Marker** button when you are ready to write the new geolocation. 

Every georeferencing point needs to come with some measurement of uncertainty. Even GPS points have some uncertainty reported by the GPS device.
In our case, this is a manual estimate of how sure you are that the point is near the position indicated by the marker. To edit uncertainty, click on the marker and then click on **Edit uncertainty**. 

There is a default "uncertainty bubble" which may not be entirely visible at your zoom range.
Zoom out until you see the large gray arrow indicating the edge of the bubble:

![](/assets/images/protocols/edit_uncertainty.png){:class="img-responsive"}

You can then click and drag the arrow closer to the point to indicate low uncertainty:

![](/assets/images/protocols/low_uncertainty.png){:class="img-responsive"}

When you are satisfied with the point and the uncertainty, click the **Save to Application** button which will close the GeoLocate window and return to your specimen.


## Georeferencing Tips

- Some specimens will not have precise enough locality data; for example, it may only identify a county or municipality. That is ok, in this case drop a point at the approximate center (centroid) of the area and make the "uncertainty bubble" large enough to reflect the lack of precision. 
- There are other map layers available! Use the small plus sign on the right side of the GeoLocate window to bring up a toolbar that allows you to switch between map layers, including USGS Topo maps. There aer even historical maps! Be sure to record which map layer(s) you used when writing your Georeference Remarks.
- If the **Locality** field is blank but there is text in **Locality Remarks**, please copy/paste the information into the **Locality** field as well. 
- If you are not sure what to do with a specimen, you can mark it for further review (see below). You can also ask for help on Slack!

## Final Checklist

When you are done reviewing the georeferencing for this specimen, you also need to record what you did.

#### If you are not sure about a specimen

- Change *Georef Verification Status* to **Checked by [your username]"**
- Change *Processing Status* to **Expert Required**

#### If coordiantes NOT changed

- In *Georef Verification Status* write "Checked by [your username]"
- Change *Processing Status* to **Reviewed**

#### If coordinates changed
 
- Change *Georeferenced by* to your username
- In *Georeference Remarks* indicate any map layers you used
- In *Georef Verification Status* write **Manually updated**

#### If the record is now complete (transcribed label, image, reviewed georeference):

- Change *Processing Status* to **Reviewed**

#### **If one of these is missing:**

- Change *Processing Status* to **Pending Review**



## Examples

Here are some examples of using different tools to identify the correct location

### Using Old Maps 

Here is the locality string for a specimen from Rusk County, Texas:

> sandy soil of roadside on st.hwy. 26; 3.5 mi. n. of henderson

The current map of Henderson, TX does not show any state highway 26:

![](/assets/images/protocols/googlemap.png){:class="img-responsive"}

Geolocate used 3.5 miles north (by air) from Henderson, with a large uncertainty bubble.

However, if we use a map from around the same time as the specimen (1966), we see a different answer:

![](/assets/images/protocols/oldmap.png){:class="img-responsive"}

It appears that state highway 26 has now been re-assigned to US Hwy 259!



### Using the Measuring Tool

Continuing with the above example, we now need to measure 3.5 miles along this road, north of town.
Click on the Measure tool to pick a more specific point. 
Each time you click it will continue the measurement, so you can follow the road distance.

![](/assets/images/protocols/measuring.png){:class="img-responsive"}

You will need to switch back to Place Marker to update the coordinates.
Don't forget to change the uncertainty bubble!





