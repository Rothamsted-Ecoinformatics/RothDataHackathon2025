# Rothamsted National Bioscience Research  Infrastructures 
This pack is a summary of the information held in the web platforms for each of our data collecting infrastructure and specially tailored for use during the Hackathon. 

## Rothamsted Long-term Experiments Data

Rothamsted Research’s long history of collecting data from field experiments started in 1843 when Sir John Lawes asked Henry Gilbert to methodically try different fertilizer treatments to improve crop yields on his Harpenden farm. From then follows a  a continuous record of data, and samples, from grain to straw, rain to wind, and various types of soils. Experiments continued, sites got added (Brooms Barn, Woburn, North Wyke, Saxmundham…) and the breadth of information increased. First recorded in neatly handwritten books, then typed and printed, now the recording of results (data) and the information about  it (metadata) takes advantage of an electronic technology that is rapidly advancing. This document is a very short guide to a very long story.

1990 and e-RA, the electronic Rothamsted Archive was the first attempt to a relational database for the complex data for the classical and long-term experiments. It had several versions; the latest one is e-RAdata (2005) which is still used to access raw data from some experiments (plus the daily weather data)

From 2013, selected datasets started being made Open Access and provided with Digital Object Identifiers (DOI) incorporating FAIR data principles [(Wilkinson et al 2016)](https://doi.org/10.1038/sdata.2016.18).

We are at the dawn of the latest generation of delivery for the Rothamsted Long Term Experiment Data – an API which enable direct programmatic access to the data.

Further information and cases studies of uses of the data are described in [Perryman et al, 2018](https://doi.org/10.1038/sdata.2018.72) and in [Ostler et al, 2023.](https://doi.org/10.1007/978-3-031-13276-6_7)

[https://www.era.rothamsted.ac.uk/index.php](https://www.era.rothamsted.ac.uk/index.php) : the home page has a 5-minute video that explains the whole project.

Then you may want to explore Broadbalk or Park Grass

### Broadbalk:

[https://www.era.rothamsted.ac.uk/experiment/rbk1](https://www.era.rothamsted.ac.uk/experiment/rbk1) : the Broadbalk Experiment, , designed to test the effect of different organic manures and inorganic fertilizers on the yield of winter wheat and still going on. [https://www.youtube.com/watch?v=BH3Wc3U-oys&t=1s](https://www.youtube.com/watch?v=BH3Wc3U-oys&t=1s) for a 3:37 mins video.

Data for the Broadbalk Experiment is associated with key management changes in its history: 1852-1925 when there were single long plots testing different fertilizers; 1926-1967 when the plots were divided to investigate fallowing and crop rotations; and the current period from 1968- when short straw wheat varieties were introduced.

Ø  Datasets available for Broadbalk:  [https://www.era.rothamsted.ac.uk/experiment/rbk1#datasets/](https://www.era.rothamsted.ac.uk/experiment/rbk1#datasets/)

Ø  Broadbalk Wheat annual grain and straw yields 1852-1925 – a good example of a frictionless data package with extensive metadata. [https://doi.org/10.23637/rbk1-1796346264-1](https://doi.org/10.23637/rbk1-1796346264-1)

Ø  Broadbalk mean long-term yields of winter wheat 1852-2022 – an example of the summarized dataset: [https://doi.org/10.23637/rbk1/meanWWYields1852-2022-03](https://doi.org/10.23637/rbk1/meanWWYields1852-2022-03)  This shows you the main management changes and their effects on yields since the start of the experiment.

### Park Grass:

[https://www.era.rothamsted.ac.uk/experiment/rpg5](https://www.era.rothamsted.ac.uk/experiment/rpg5): the effects of fertilizer treatments on botanical composition and yields of hay on permanent grassland - and a 4:20 min video [https://www.youtube.com/watch?v=-3-Pm5JUQZ4](https://www.youtube.com/watch?v=-3-Pm5JUQZ4)

Data for the Park Grass experiment is also associated with key changes in its management history: 1856-1902 when the original whole plots had fertilizer treatments but no liming; 1902-1964 when plots were split in half to look at the effects of with and without lime; then from 1965- present when whole plots became four plots a,b,c,d to investigate the effects of different soil pHs on yield and plant species.

Ø  Datasets available for Park Grass: [https://www.era.rothamsted.ac.uk/experiment/rpg5#datasets/](https://www.era.rothamsted.ac.uk/experiment/rpg5#datasets/)

Ø  Park Grass Hay Yields, Fertilizer and Lime Treatments 1965-2024:  [https://doi.org/10.23637/rpg5-PGYields19652024-1](https://doi.org/10.23637/rpg5-PGYields19652024-1)

Ø  Park Grass species: A ten-year record of all the species on all the plots of Park Grass [https://doi.org/10.23637/rpg5-species_1991-2000-01](https://doi.org/10.23637/rpg5-species_1991-2000-01)

Ø  Park Grass Plot Photos: a visual exploration of differences in species composition depending on treatments  [https://www.era.rothamsted.ac.uk/info/rpg5/plot-photos](https://www.era.rothamsted.ac.uk/info/rpg5/plot-photos)  - [https://doi.org/10.23637/rpg5-plotphotos-01](https://doi.org/10.23637/rpg5-plotphotos-01)

Ø  Park Grass timeline[[SP1]](#_msocom_1) [[NC2]](#_msocom_2) [[3]](#_msocom_3)  of plot and fertilizer changes: it's a complicated experiment with many plot changes so this should help understand its layout over time: see it at[  
https://doi.org/10.23637/rpg5-PGtimeline-1856-2025-01](https://doi.org/10.23637/rpg5-PGtimeline-1856-2025-01)

### Others

There are a lot more experiments data in e-RA. A list is available for you here to find out if there are other experiments or open datasets that you would like to work with on the day – plus the daily weather data too!

Ø  [https://www.era.rothamsted.ac.uk/info/RLTEdatavailable](https://www.era.rothamsted.ac.uk/info/RLTEdatavailable)  listed by experiments

Ø  [https://www.era.rothamsted.ac.uk/info/datasets](https://www.era.rothamsted.ac.uk/info/datasets) : listed by type of observation – open data only

On the day, we will NOT use the e-RAdata tool.

### Meteorological Data

Weather records help us to understand the spread of crop diseases and insect behaviour. Rainfall and wind direction have been measured at Rothamsted every day since 1853, temperature since 1878 and sunshine since 1890, making this one of the longest sets of meteorological data available in the UK. As new equipment was invented to measure different meteorological variables, scientists added them to the Rothamsted weather station. Now over 25 different weather measurements are made every day. Various summaries of our weather data are provided on the e-RA web site as Spreadsheets  - [https://www.era.rothamsted.ac.uk/station/rms#datasets/](https://www.era.rothamsted.ac.uk/station/rms#datasets/)

  

## The Insect Survey

Collecting insect data since 1964

The Rothamsted Insect Survey (RIS) has been running two trap networks since 1964. The long-term data generated is unique, providing information on aphids, larger moths and many other migrating insects to scientists, growers, conservation organisations, individuals and policy makers. As such, the networks represent the most comprehensive standardised long-term data on insects in the World and have a wide range of fundamental and applied uses.

**The suction-trap network** began operation on the 29th April 1964 and continues to this day to monitor the aerial fauna migrating at height of 12.2m. Essentially, these suction-traps can be thought of as upside-down hoovers that indiscriminately catch small to medium-sized insects (≤5mg), particularly **aphids**. The height of these traps has been optimised with aphids representing the key target of interest. Suction-trap catches are monitored daily during the aphid season and weekly at other times.

**The light-trap network** currently comprises 58 traps across the UK and Ireland with most traps run by over 160 volunteers who contribute data to the network. The Rothamsted light-traps are emptied daily throughout the year. Over time, the trap network has caught over 1,500 species, primarily macro-**moths** with a small number of micro-moths. The samples generated are generally representative of the 'field scale'. Daily records are available, but samples are not stored.

Bell, J.R., Blumgart, D. and Shortall, C.R. (2020): has a good overview of the network and of the output potentials [**https://doi.org/10.1111/icad.12412**](https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdoi.org%2F10.1111%2Ficad.12412&data=05%7C02%7Cnathalie.castells%40rothamsted.ac.uk%7Cf53e2ae3aef6431b9d0a08dde587ec68%7Cb688362589414342b0e37b8cc8392f64%7C0%7C0%7C638919094145651951%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=Yi1zRPyS2Bt9tyJCja6a7xo55x7u718NflAeT2CqHhs%3D&reserved=0) 

### The Data: 

- **RIS data warehouse:** Our data warehouse is a client-facing service that hosts aphid and moth data from 1990 onwards. Data includes daily, weekly,  and annual summaries as well as infographics to visualise these data.
- Notable and/or recent RIS outputs include contributing to:

- the ‘Insect decline and UK food security’ enquiry actioned by the UK Parliament/House of Commons Science, Innovation and Technology Committee ([https://publications.parliament.uk/pa/cm5804/cmselect/cmsctech/326/summary.html)](https://publications.parliament.uk/pa/cm5804/cmselect/cmsctech/326/summary.html\)) ;
- the modelling of likelihood for extreme early flight of one of the most important UK aphid species, _Myzus persicae_ ([https://doi.org/10.1093/jee/toac012](https://doi.org/10.1093/jee/toac012)) ;
- a case study for high-throughput sequencing of archived insect bulk material ([https://doi.org/10.1002/edn3.542](https://doi.org/10.1002/edn3.542)); and forecasting of aphids ([https://doi.org/10.1002/ps.7292](https://doi.org/10.1002/ps.7292)).

- **RIS Bulletin API**: an API, not available to the larger public yet, that provides the same data as the last published Aphid Bulletin. It is based on data from a network of sixteen suction-traps, representative of what is flying across the UK over an area of radius approximately 80 km. Access to this API will be possible during the Hackathon

  

## The North Wyke Farm Platform

A pioneering, farm-scale intensively instrumented research facility

### Overview

The North Wyke Farm Platform (NWFP) is a farm scale (63 ha) platform, established in 2010, designed to compare numerous agronomic and environmental factors associated with farming. The NWFP is split into a number of 'farmlets', each of which has a different farming system operating on it, and these farmlets are completely independent of one another to allow comparisons between them. The farming system operating on the farmlets changes over time, but currently includes livestock production for meat (cattle, sheep) on grassland, an arable system, and livestock housed indoors year round. The NWFP is highly instrumented and sampled. Data includes the flow rate and chemistry of water running off of the fields (taken at 15 min intervals), meteorological measurements (15 min intervals), soil moisture (15 min intervals), greenhouse gas emissions (30 minute intervals), soil, crop and botanical field survey data, livestock and crop performance data, and farm operational activities (including the time taken and fuel used for activities).

### The NWFP design

The NWFP is comprised of fields, catchments and farmlets.

**Fields** are the smallest unit over which the farming operations are divided. Livestock will (typically) graze a whole field and arable operations will be done across a whole field. There are 6 or 7 fields per farmlet in the NWFP.

**Catchments -** The fields of the NWFP are hydrologically isolated, and the highly impermeable subsoil means that water moving as surface or subsurface runoff is captured by a bounding drainage system and directed towards a flume, with one flume per catchment. A catchment may comprise 1-2 fields, and there are five catchments per farmlet.

**Farmlets** are the division of the NWFP into different farming systems or treatments (further details of these below). The farmlets are completely independent, with livestock and any inputs or outputs (such as silage and manure) not passing between them. It is important to note that the farmlet is the only scale at which the farming systems can truly be compared, because farming operations may take place at different times or to different degrees on different fields, as influenced by the farming system.

**Sheds** are the indoor areas where livestock are housed. All cattle remain indoors over winter, while sheep are brought in prior to lambing. The brown farmlet have cattle who are housed all year round. While in the sheds, livestock from the different farmlets are kept separate, and are fed silage made from their respective farmlet.

![fields](file:///C:/Users/castells/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)

### A brief history of the farming systems on the farmlets

**The baseline period:** 2010 to between 2013 and 2015 (depending on the catchment). All fields in the NWFP were under permanent pasture, in order that baseline data could be collected.

**The first system change:** between 2013/2015 and 2019. The NWFP land was split into 3 catchments:

·         Red farmlet: Land reseeded with an innovative grass species with desirable traits, such as high sugar grasses. Predominantly this was perennial ryegrass (Abermagic), although one field had a festulolium (Prior).

·         Blue farmlet: Land reseeded with the same innovative grass species, but also increased use of legumes in order to replace nitrogen fertilizers with biological fixation of nitrogen. Predominantly perennial ryegrass (Abermagic) and white clover (Aberherald), with one field of festulolium (Prior) and white clover (Aberherald).

·         Green farmlet: Continuation of the permanent pasture.

The reseeding of land took place over 2 years, and the new systems were in full operation by the end of the 2015 grazing season.

**The second system change:** Autumn 2019. Conversion of the red treatment to arable and a new farmlet with continually housed cattle.

·         Red farmlet: converted to arable. Grass cover sprayed off and sown with milling quality winter wheat (variety = Crusoe). In subsequent years the crops have been: 2020 winter wheat (variety = RGT Skyfall), 2021 winter oats (variety = Mascani), 2022 winter wheat (variety = Crusoe), 2023 winter wheat.

·         Brown farmlet: new farmlet made with continually housed cattle to evaluate more intensive finishing.

### Useful links

The NWFP website contains a wealth of information. In particular:

**Map** of the NWFP [https://nw-farmplatform.rothamsted.ac.uk/content/map](https://nw-farmplatform.rothamsted.ac.uk/content/map)

**Overview** and treatments [https://nw-farmplatform.rothamsted.ac.uk/content/overview](https://nw-farmplatform.rothamsted.ac.uk/content/overview)

**Data user guides** [https://nw-farmplatform.rothamsted.ac.uk/nw-guides](https://nw-farmplatform.rothamsted.ac.uk/nw-guides) There are separate user guides to different aspects of the NWFP, including the design.

### Data

**The NWFP portal**

Core datasets are available from the NWFP portal. To see what data is available, go to [https://nw-farmplatform.rothamsted.ac.uk/content/data_collection](https://nw-farmplatform.rothamsted.ac.uk/content/data_collection)

To access the NWFP portal data, you can either:

1)      Access the data as yearly .csv files, [https://nwfp.rothamsted.ac.uk/](https://nwfp.rothamsted.ac.uk/). **Please note that you must register to use the portal via this method, and must have done so prior to the hackathon.**

2)      Via the API [https://api-nwfp.rothamsted.ac.uk/](https://api-nwfp.rothamsted.ac.uk/)

Due to the quantity of data available and the complexity, the NWFP portal is most useful if you already have a clear idea of what question you might like to answer with the data.

**Worked-up datasets**

If you just wish to browse datasets, you may wish to look instead at the data repository, which contains non-core and worked up datasets, [https://data.rothamsted.ac.uk/group/north-wyke-farm-platform](https://data.rothamsted.ac.uk/group/north-wyke-farm-platform).

In particular, we highlight these datasets for you to consider:

**Productivity**

**Yield – measured**  
At arable harvest, or silaging of herbage, measurements of yield may be made. This dataset covers the years 2011-2024. Silage data (159 measurements) includes silage dry matter yield; arable data (30 measurements) includes grain and straw wet yield and grain moisture content.  
_This dataset is not published, but the data, metadata and column units/descriptors are available as separate files._ - [[Yields unpublished dataset]]

**Yield – estimate via Platemeter**  
Herbage biomass/yield can be estimated by a rising plate meter, which an operator walks around the field to take measurements. Data were collected over 6 years, from April 2018 to March 2024, with either fortnightly (in the summer) or monthly (in the winter) measurements. In each field, multiple measurements were made and are presented as both individual points (with latitude and longitude, where available)(~50,000 measurements), and as a summary per field (~1650 values).  
[https://doi.org/10.23637/ihvddnpp](https://doi.org/10.23637/ihvddnpp)

**Emissions**

**Greenhouse gas emissions**  
Soils and livestock emissions of greenhouses gases (carbon dioxide, methane) can be measured in-field using eddy covariance towers. This dataset takes data available on the NWFP portal, removes poor data, and gap-fills the CO2 dataset. The dataset contains meteorological data, information about what animals were grazing in the field, and calculations of Net Ecosystem Exchange (NEE) for 2017-2019. Data are on a 30 minute timestep, so ~130,000 rows of data.  
[https://doi.org/10.23637/rothamsted.99192](https://doi.org/10.23637/rothamsted.99192)

**Water – daily means  
**The NWFP portal contains water flow and various chemical or physical properties of the water in surface runoff and subsurface lateral flow on a 15-minute timestep. This dataset provides daily means of those values after quality control and the removal of data points below a minimum threshold of missing values. The data cover Jan 2012-Dec 2023, with ~66,000 rows of data on 16 variables. Precipitation data are also included.  
[https://doi.org/10.23637/mqrcjnur](https://doi.org/10.23637/mqrcjnur)An equivalent dataset covering the variance of the daily data is at [https://doi.org/10.23637/dfzekfy1](https://doi.org/10.23637/dfzekfy1)

**Water – processed 15-minute data**  
This dataset contains data on the flow rate and chemistry (sediment, nitrate) of water in surface runoff and throughflow, plus rainfall quantities. The data were taken from the NWFP portal, cleaned according to the quality control tags, and infilled to produce a continuous dataset. Data available between 1/10/2016 and 31/3/2020, for 4 of the 15 NWFP catchments. Quantity of data dependent of the variable, but in the order of ~200,000 rows.  
[https://doi.org/10.23637/17dquvlt](https://doi.org/10.23637/17dquvlt)

You may wish to use the data in conjunction with Google Earth Engine ([https://earthengine.google.com/](https://earthengine.google.com/)).


 