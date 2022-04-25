## UX Design

### Mind Maps

| Alex Bezirjyan | Cameron Jewett | Yvonne Nguyen  | Camille Wong |
| ------------- | ------------- |------------- | ------------- |
| ![](/newfolder/mmab.png)  | ![](/newfolder/mmcj.png)  | ![](/newfolder/mmyn.png)  | ![](/newfolder/mmcw.png)  |
| The layout of the page was quite unified with four rectangular divisions for each mapped stadium but the zooming for each map would be a bit of an inconvenience. The sidebar descriptions on the other hand can really help the viewer of the webpage quickly grasp what the map is really meant for with a few lines of text. In addition the side arrows could be valuable in transitioning from one year to another and further examining changes in the maps based on different years of census data.| For temporal elements of the project, we can make use of the sliding bar style map to easily show change over time. A scrollable page could also be a cool interactive feature. Doing relatively few maps but with high levels of interactivity where the user can easily change the variable they’re looking at.| Instead of traditional headers (e.g., each stadium would be represented by its name), I was thinking we could use a png of the stadium (i.e., a picture of it) to represent each stadium. Perhaps when one hovers the picture, the name of the stadium comes up. Underneath the header would the map. Underneath the map would contain information/our findings related to each stadium.| I created a webpage that had a sidebar on the left side of the page, and the map would be contained in a panel on the right. On the sidebar, there is the option to navigate to the four cities we’re investigating, as well as the Census data that we’re using to prove our thesis. What’s successful about this design is that the information is laid out in a way that’s easy to navigate––there’s no hyperlinks that require you to jump to another page to receive the information. However, what I think could be improved about this map is the organization and hierarchy of information.  |

### Crazy 8s

| Alex Bezirjyan | Cameron Jewett | Yvonne Nguyen  | Camille Wong |
| ------------- | ------------- |------------- | ------------- |
| ![](/newfolder/c8ab.png)  | ![](/newfolder/c8cj.png)  | ![](/newfolder/c8yn.png)  | ![](/newfolder/c8cw.png)  |
| Color coordination in a small map key for each stadium would make it easier for the viewer to understand the different variables in each region. In addition, bolded, dotted, and colored lines may also be useful in illustrating boundary lines. For aesthetic design without real practical use, a cursor can be changed into a stadium theme such as a baseball. | Choropleth maps will be helpful with our variables that show a range of financial data that can be sorted into categories based on ranges. We can choose one color and do increasing ranges to darker hues; ie the greater the earnings, the darker the color. An introductory slide potentially with an interactive timeline documenting the history of the stadiums and providing links to outside content to learn more such as videos. Prioritizing accessibility in our code structure, color scheme, adding alt text for images, etc. | Vertical scrolling, png images of the stadium, a slider on each map that shows transition over time, dark mode (or non-white background…helps the eyes), using web accessibility tests to make sure our website is user friendly (e.g., using Stark, a plugin on Figma, to determine if our color palette contrasts each other well), each stadium having its open dedicated page, a timeline detailing the stadiums’ histories. | Moving the layers from buttons on the sidebar to checkboxes could make it easier to understand the hierarchy of information (i.e. first you select the location/stadium, then you click the checkboxes to activate the Census data). Also experimenting with how to display the locations and stadiums in the sidebar––is it a button, is it tabs? Also thinking about how much information/description to display––is it a popup marker, or is it displayed on the sidebar? 

### Prototype
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="1000" height="600" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FeYQUfoDWIkTfYXLzYvx3qU%2Fwireflow%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

### Features
1. Navigation Bar with clickable links that takes the user to different pages. 
2. Each staidum will have its own page. 
3. Filtering option that lets the user different layers of the map. "Census layer" refers to which specfic dataset is used to make that layer (e.g., housing costs or yearly income).
4. The filtering button changes color when the user hovers over it and transforms into a darker opacity of the hover color once the user clicks on it. 
5. An "About Us", "Data", and "Sources" page. 
