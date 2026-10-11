
# My Personal Website and Web GIS Project

## About the Project

This website was developed as part of the GMT458 course. It introduces me, presents technologies I have used during my Geomatics Engineering studies, and displays some of my favourite places in Ankara on interactive maps.

## Website Content

- **Home:** My personal introduction and career goals in Geomatics Engineering.
- **About:** My education and experience in Geomatics Engineering.
- **Technologies:** GIS software and other technologies I have used during my studies and internship.
- **Projects:** Two interactive maps showing my favourite places in Ankara.
- **Contact:** My email address and GitHub profile.

## Technologies Used

- **HTML:** To create the structure of the web pages.
- **CSS:** To design the pages, manage layouts, and add animations.
- **JavaScript:** To control interactive features and map behaviour.
- **OpenLayers:** To create a map showing locations in Ankara and manage markers.
- **Leaflet:** To display the same locations using a different Web GIS library.
- **OpenStreetMap:** To provide the base map data.

## Map Features

The Projects page contains two interactive maps created with OpenLayers and Leaflet. Both maps display the same locations in Ankara.

Markers appear when the zoom level reaches 12 or higher. The OpenLayers map uses marker clustering to reduce overlap between nearby locations. On the Leaflet map, clicking a marker displays the place name and category.

Settings have been applied in both libraries to prevent the world map from repeating horizontally when zooming out.

## Problems Encountered and What I Learned

One issue I encountered during development was that the maps did not load properly when I opened `projects.html` directly in the browser. However, the same page worked when I used the Live Server extension in Visual Studio Code. I researched this difference using online resources and learned why running web pages through a local development server can be important.

I also addressed the problem of markers overlapping when locations were close together. With AI assistance, I implemented marker visibility based on the zoom level and clustering for nearby locations in OpenLayers.

Additionally, I explored settings that prevent the world map from repeating when zooming out. Through this process, I gained a better understanding of how zoom levels affect map features and how two different Web GIS libraries can provide similar functionality.

## AI Usage

AI tools were extensively used during the coding process to create and improve HTML, CSS, and JavaScript code, develop the OpenLayers and Leaflet maps, and address technical issues.

I used AI assistance to work on marker visibility, clustering, and settings that prevent the world map from repeating. I also researched some of the problems I encountered using online resources.

**Estimated total AI usage:** Approximately 5–7 hours.