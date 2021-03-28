# Style choices explained 
In order to style a map that reflects the colors and brand of healthy ride I took the follow steps
- First, I used Canva's color palette generator to extract the theme colors from Healthy Ride's landing page. I decided on an image from the website scroll that includes a bike as it would lend itself to denoting infastructure on a map, as well as the stable image of Healthy Ride. The color breakdown is as follows:
![healthy ride color palette](https://raw.githubusercontent.com/mkay1016/portfolio/main/healthyridecolors.jpg)

-From there I used the Google Styling Wizard to create a base map. I started with the 'reto' style as the starting colors and fonts were similar to those of Healthy Ride. 
- I changed each of the major features of the map to take on one of the four thematic colors through an eyedropper tool. The staple Healthy Ride blue defined water, while the graident of neturals defined infastructure and natural land use. 
- When I changed the basemap colors the zoom view was effected, but on further inspection this layout better defined the suburban versus urban divide, which could actually be useful for an urban bike share system like Healthy Ride and its users. 
- Then I made a JSON file for the style 
- Here is a static image of the map:
![healthy ride static map](https://raw.githubusercontent.com/mkay1016/portfolio/main/healthyridemap.jpg)

## Stretch Goal
I was eager to try to get each station pin on a dynamic map as well, so I pushed on.
- First, I set up my Google API and secured the key
- Then, I created a new healthy ride github file to make the map dyanmic. THis took some trial and error as I acidentally incuded one exta } and that threw the whole document for a loop. But once I got that up and running I pressed on.
- Then, I went on the Western Pa Regional Data Center and found a csv of Healthy Ride station locations 
- I uploaded the CSV into my google maps to create a layer of staion maps. I tried to use a little bike as an icon but it seems to have been lost in the KML conversion. 
- Finally, I converted this layer to KML and added the KML code to the existing healthy ride document on github. Again, I ran into a some bumps but cleaning and editing sorted this our. 
