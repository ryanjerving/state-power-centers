# state-power-centers
A look at where the centers of political power in U.S. states sit in relation to where most people in those states live.

https://ryanjerving.github.io/state-power-centers/

Let's get this out of the way: here's my modification of the course's leaflet template map, which I've used to chart the geocoded locations of the State Capitol buildings for all 52 U.S. States (including Washington, D.C., and Puerto Rico). You should be able to toggle between the Carto Light and Stamen Terrain basemaps, and turn the markers off and on.

I did this as part of a kind-of-hard-to-explain project in which I wanted to look at where the center of political power in each U.S. state (represented by the building in which each State legislature meets) sat in relation to what the U.S. Census for 2010 describes as the "Mean Center of Population" for each state -- essentially, the balancing point around which the population of each state is distributed. (For the whole U.S., it's in Plato, Missouri!) My thought was that there must be something worth knowing about states in which people would feel geographically close to or far from their elected representatives.

<iframe src= "https://ryanjerving.github.io/leaflet-map-State-Capitols/" width="90%" height="350"></iframe>

I calculated the distance between the political and population center for each state in a pretty manual way -- entering into Google Maps the address for the State Capitol and the GPS coordinates the Census provides for the mean population center and using the fastest route driving miles that Google Maps spits out (in retrospect, the driving MINUTES might have been a better measure). Using a simple BatchGeo map, this looks like this:

<iframe src="//batchgeo.com/map/19dd2ef6abebead8ac56ee7dc6aa337f" frameborder="0" width="100%" height="550" style="border:1px solid #aaa;"></iframe></p><p><small>View <a href="https://batchgeo.com/map/19dd2ef6abebead8ac56ee7dc6aa337f">Mean Center of Population for U.S. States</a> in a full screen map</small>

There is a pretty interesting clustering here, with a bunch of blue, a bunch of yellow, and then a bunch of red states together. Why it happened that way, and what it portends for AMERICAN DEMOCRACY is another question. The scatter charts I created for different variables didn't suggest any obvious correlation between this population-to-political center distance and overall population, land area, population density -- or even the percent of that state's popular vote in 2016 for Hillary Clinton or Donald Trump! 

But there is a pretty clear East-to-West shift, and without doing much else in the way of looking, my suspicion is it has something to do with when European settlement took hold in each state and (perhaps) the dominant mode of moving goods and people when that happened: in other words, how far you could be dispersed and still be served by foot, horse, water, rail, or highway. Here's the Highchart scatter plot for that distance relative to longitude (what I'm calling "westerliness"):



