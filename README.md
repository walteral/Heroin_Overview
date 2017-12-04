# Heroin_Overview

Title: Ther Heroin Epidemic

Description: The purpose of the project was to show awareness of the opiate epidemic that has grown over the last few decades. The project starts by showing the top producing regions of Afghanistan, where 80% of the worlds opium is grown. Then it shows in greater detail each of the three trade routes where opium and heroin get smuggled out. Each route showcases a different aspect of the trade: The northern route focuses on transportation methods, the Balkans route focus on the profit aspect and the southern route focus on how disperse the route is. The end of the project shows a county map of drug-related deaths in America, attempting to show the impact on a local scale the effects of the drug trade starting in Afghanistan.

Goal: The goal of the project is to spread awareness about the impacts of the opiate trade originating in Afghanistan. 

Technical Summary: 1)System architecture: Based on a storymanp tempate there are scenes that, as you scroll through them, show you different aspects of the drug trade. First there two scenes that give an overview of where opium is grown in Afghanistan and where the major trade routes are. The next three sections going into greater detail on each trade route, with two scenes each having an overview scene and an impacts scene. The last section shows the impact of drugs in America. This web map was based on client-side instead of server-side because there wasn't large amounts of data that needed to be processed or stored. 

2) Main functions: The main function of the map is to tell a story. As you scroll through the scenes the story takes you through the opium trade. Other major functions are: about and credit modals with a collapsing side navigation bar. Social media buttons that take you to the respective sites. a scrolling button to move through the scenes. a mini-map displaying where in the world you are. 
In the screenshot below you can see several of the main features including a minimap in the bottom left, and nnavigation arrow in the bottom center, self-drawn arrows on the main map, and a moving icon (the truck).

<img src="">

Reflection: This course was excellent. In my past courses both at Oregon State and Michigan State we focus on static maps created in a GIS. These maps are often meant to be 2D and printed out on paper. This class showed how benifital it can be to showing a map on a website. The interactivity and ability to change the map really add an element to understanding what is trying to be shown on the map. When designing a web map there are a lot more tools that are avaliable to you to showcase your data, each tool adding an element that can assist the creator. 

Data Source: The main source of data in creating this web map was three United Nations Office on Drugs and Crime reports covering each of the three trafficking routes out of Afghanistan. The information was transcribed by Alex Walters onto the map in order to tell the story of how drugs move across the earth. The second sources of data was the drug-related deaths by county, which came from the Center for Disease Control and Prevention (CDC). This data layer was joined with a county map, which was downloaded from census.gov. That last source of data that was used on the web map was country shapefiles that were downloaded from GADM.org. All pictures and videos were aquired from google searches or youtube.

Libraries: Leaflet, Bootstrap, Jquery, font=awesome, google fonts, chroma.js, and topojson. Web services were provided by github and CartoDB.

Credits:D3 Video Credits: "The Unseen Afghanistan", YouTube video, 3:35, posted by Khyber Khan, Nov 20, 2016, https://www.youtube.com/watch?v=JDrScVo7aBs
End photo credits: https://userscontent2.emaze.com/images/7d765166-02ae-4221-b3a4-c755f5e8827a/32509c83-ac87-4dc2-8f67-7fe76a86e8b0.jpg 
Country shapefiles:http://www.gadm.org/download
CDC data: https://wonder.cdc.gov/mortsql.html
Picture sources: https://www.globalresearch.ca/afghanistan-britain-is-protecting-the-biggest-heroin-crop-of-all-time/6405; 
http://www.freemalaysiatoday.com/category/world/2017/08/08/from-poppy-to-heroin-taliban-move-into-afghan-drug-production/;
http://www.railwaypro.com/wp/the-historical-silk-road-reinvented-on-railways/;
http://www.balkaninsight.com/en/article/drug-lord-shot-in-%D0%B0-gunfight-at-bulgarian-sea-resort-06-09-2016;
https://www.expresstorussia.com/moscow-tours.html; 
https://www.vice.com/en_us/article/vdxegj/french-connection-kevin-perry-marseille;
http://www.cnn.com/2017/07/31/asia/india-heroin-drug-bust/index.html; 
https://www.statista.com/statistics/269857/most-profitable-companies-worldwide/ 
Icons made by Freepik from www.flaticon.com is licensed by CC 3.0 

Acknowledgement: I would like to acknowledge Bo Zhao for helping me with this project, and helping me understand new source codes for creating web maps. 



