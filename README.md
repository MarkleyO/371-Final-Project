# 371-Final-Project
analyzing a web map applicaiton

## Report of Global Oil Imports and Exports Map <sub>- analyzing a web map application</sub>
### Introduction
The design objective of this web map is to advertise for the GSM college, which primarily focuses on courses in oil and gas management. The map does this by stressing the importance of oil and fossil fuels in the global economy. These points are driven home by the scale of the map, choosing to use a globe puts greater stress on the truly worldwide scale that this industry has. Functionally, the map is relatively simple, yet it is done remarkably cleanly and well. The primary function is to explore the globe, and learn about which countries dominate the global oil industry. Investigating any one of these at any year provides basic info about what countries the selected does business with, and in what quantities. The map was developed by the GSM in 2014 ( the last date on the timeline ) , and is designed to pique interest in the field of Oil and Gas management, and as a result encourage people to apply for the GSM London institute. 
### Systematic Architecture
Systematically, the map is relatively basic. The data present is the various locations of the countries, export/import values for each year, and consqeuently each country's position related to the others. There also aren't too many libraries included in the application. The globe, and I believe the arrows and points, come from the google analytics library. The custom globe is also just an image placed over the globe. The same goes for the stars and solar flare seen in the background. Other than that there are various fonts imported in, as well as social media sharing buttons that have been included. There is also use made of bundle.js and modernizr.js which function serve to concantenate files, and detect info about the users device to provide a more friendly experience respectively. Beyond that I couldn't find anything else too advanced or interesting about the architecture of the application.
### Map Design
Overall I think that the map is beautiful, the dark globe has great resolution, and mimics the color of oil itself. It's clear where each continent and location is, yet they still manage to blend in flawlessly with the seas around them. The contrast of the red across some of the text and lines is very well done, and the blue stands out nicely for exporting countries. The different oil drop markers, all look very good, and the changing color on click is a very nice touch. The animation of the lines when clicking a drop also looks remarkably smooth. Exporting countries also have the lines originate from themselves, while importing countries have lines converge on themselves. The data presented on mouse over, and the popup on the right side when clicking is also really well done. It was also a great choice to have the articles, about page, and school info, all be accessed from a separate portion of the site, so as not to distract from the globe. However, my one issue is the tone of the site. It might be my own aversion towards the fossil fuel industry, however the sense of domination, and the almost evil looking red and black color scheme don't really seem to paint this industry in a positive light. Constantly highlighting the United States place at the top of the importers list feels more like a subtle criticism of the industry rather than admiration of it. This is the only thing that didn't quite sit right with me.
### Data Sources
Data sources for the map are singular, coming from the UN Comtrade - Internation Trade Statistics Database. In examining this database, there are many more maps which make impressive use of their data, which are all liked on their site. Since the globe does not zoom in at all, there isn't a tile layer present, and as I stated earlier, it looks like an image of the world was simply applied to the already existing google analytics globe. The data for the points is then provided in what I would guess to be SVG, and GeoJSon for the points ( there is no data file to be found in the assets folder, and the link to the source does not direct to the actual data set ). Wherever it is, I think that it's filtered through Google analytics.
### Basemap/Features
The map's main focus is the black spinning globe, which by default has ten locations/countries marked on the map. The user can then switch between whether they want importers or exporters, and change the year from which the data is collected as well. Clicking upon one of these markers will then add points for where said country either exports or imports primarily to. Each path is marked by a red or blue line (indicating importing or exporting) and each destination is accompanies by both the mass of oil transported, and the value/cost of it. Looking to the left side of the page, we also are given a few tabs which direct towards GSM links for selected stories in oil - which highlight the different countries jostling for market power over each other - as well as information regarding the map itself and courses at GSM.
### Web Elements    
As far as web elements go, there are almost none, the only real web features, would be the way in which the user interacts by clicking on the different destinations. There isn't any scale bar, arrow, or legend, however there are a few interactive bits, namely the different locations, and time periods that I described earlier. The user is also free to move around the globe as they choose.
### Suggestions
Looking at this map, there isn't really anything that I would change. While I think it confusing that they chose such a bleak tone for something that is supposed to excite potential students to join their school, this doesn't really take away from the overall quality of the map. Everything feels clean, sleek and in place. The animations on the map all do well to complement each other, and nothing seems to get in the way of anything else. The only thing that I could possible suggest is a way of putting more information on the map, however I think that this could take away from the very minimal feel that they are going for. The map has outstanding visual styling, yet not too much beyond that, however it's clear that this is what the designers intended, and I cant really fault it for not having some substance which is out of the scope of what the developers intended this map to be. 
