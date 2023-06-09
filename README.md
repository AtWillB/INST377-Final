# NASA EXOPLANET ARCHIVE DASHBOARD
This repository will serve as the final project submission for my INST377 course at the University of Maryland
https://atwillb.github.io/INST377-Final/

This Project is titled NASA EXOPLANET ARCHIVE STATISTICS. Its goal is to display some key statistics contained within the [NASA Exoplanet Archive](https://www.google.com/search?client=safari&rls=en&q=NASA+exoplanet+archive&ie=UTF-8&oe=UTF-8) dataset. The big part of this website is the drop-down menu that allows you to select between 3 different visualzations aquired via my API. The three visualizations are a bar chart, a pie chart, and a line graph. 

The second part of the website will display 3 numerical staticis, which as of the writing of this Readme have not been explicity identified. 

The displayed data for this project do not go through any NASA API. Rather, they go through a website created by myself and Ethan Heugler, a computer science student at the University of Maryland. We collaborated on a project that I wrote the back-end for. In order to get data to Ethan, I created API endpoints using Python's Flask which generated appropriate JSON objects from a SQL database I set up. No specific browser was targeted. No css framework was used. An image of the NASA Exoplanet Archive's logo is featured in the header of the web page. This header links to the website that I originally got this data from. 

Below is a list of the endpoints I used for this project.
<ul>
    <li>Visualizations</li>
    <ul>
        <li>Discovery Method Frequency: https://exo-dash-planets.vercel.app/api/vis/discovery_methods_bar</li>
        <li>Star Spectral Type by Percentage: https://exo-dash-planets.vercel.app/api/vis/stellar_type_pie</li>
        <li>[Discoveries made per Year: https://exo-dash-planets.vercel.app/api/vis/disc_year_line</li>
    </ul>
    <li>Statistics</li>
    <ul>
      <li>Total number of Confirmed Exoplanets: https://exo-dash-planets.vercel.app/api/stat/num_planets</li>
      <li>Total number of Star Systems that Exoplanets Orbit: https://exo-dash-planets.vercel.app/api/stat/num_systems</li>
      <li>Average mass of a Exoplanet(in Earth Masses): https://exo-dash-planets.vercel.app/api/stat/avg_mass_planet_e</li>
    </ul>
</ul>


