# The dominant influence of terrain and geology on vegetation mortality in response to drought: Exploring resilience and resistance

![](images/129d921627bbee21f71f767a29c8f6e117691927b1a77f5e86a24b6767a82874.jpg)

Linying Xiao <sup>a,b,c</sup>, Jinxing Zhou <sup>b,c,\*</sup>, Xiuqin Wu <sup>a,b,c</sup>, Muhammad Anas Khan <sup>a,b,c</sup>, Sen Zhao <sup>d,e</sup>, Xinliang Wu <sup>a,b,c</sup>

<sup>a</sup> School of Soil and Water Conservation, Beijing Forestry University, Beijing 100083, China

<sup>b</sup> Key Laboratory of State Forestry Administration on Soil and Water Conservation, Beijing Forestry University, Beijing 100083, China

<sup>c</sup> Yunnan Jianshui Desert Ecosystem National Positioning Research Station, Yunnan Jianshui 654399, China

<sup>d</sup> Research Institute of Highway, Ministry of Transport, Beijing 100088, China

<sup>e</sup> Key Laboratory for Environmental Protection Technology on Road Traffic, Ministry of Transport, Beijing 100088, China

## A R T I C L E I N F O

Keywords: Disturbed vegetation Drought event Random forest classification Drought-resistant efficiency

## A B S T R A C T

Drought is recognized as a prominent natural hazard that significantly impacts forest ecosystems. However, our understanding of the mechanisms that drive vegetation responses to drought is still insufficient due to limited data availability and methodological approaches. This study aims to analyze vegetation mortality in Southwest China during an extremely severe drought, which is considered a rare event that happens once in a century. To do this, we will use the normalized burn ratio (NBR) and Land Trendr algorithms. Our analysis reveals that there is a vegetation mortality rate of 1.65% in Southwest China, which does not align with the geographical dynamics shown by the normalized difference vegetation index (NDVI). Additional spatial analysis of vegetation mortality highlights the substantial impact of topographic features on vegetation death caused by dryness. Slope and elevation had trait significance values of 0.276 (MSE = 2%), indicating their importance. Areas with permanent water scarcity, defined as high elevation, steep slopes, and karst landforms, are more favorable for vegetation survival. This phenomenon can be attributed to the increased ability of plants in these locations to withstand drought, which is different from the prevailing strategy of resilience in more wet places. Our research adds to the increasing amount of evidence highlighting the crucial influence of local topography on the development of strategies by ecosystems to cope with drought.

## 1. Introduction

As a giant and most persistent carbon sink, forest ecosystems provide one-third of the global net primary productivity and play a vital role in the global carbon cycle (Harris et al., 2021). However, drought has become a major threat, leading to significant declines in vegetation and altering forest ecosystems. This shift turns them from being carbon sinks to becoming carbon sources (Jiao et al., 2021).

Recently, there has been a significant focus on post-drought vegetation characteristics due to the detrimental and specific impacts of drought on ecosystems. Compound droughts have been the primary cause of plant browning and have led to a decrease in the Normalized Difference Vegetation Index (NDVI) of 64.56% of the Earth’s surface since the 1990 s (Liu et al., 2023). The decline of vegetation can be extensively observed after significant drought episodes (Senf et al.,

2020), and it is nearly irreversible, persisting for years even after drought stress relief (Anderegg et al., 2015). Insufficient water following a severe drought can result in physiological or functional harm to plants, which can lead to a decrease in resilience, diminished resistance, and finally vegetation mortality (Schwalm et al., 2017). Recent research has repeatedly shown that drought episodes have had a major impact on vegetation mortality and have played a crucial role in determining the rate at which regional greening occurs (Rao et al., 2019; Liu et al., 2023). With the expected increase in drought frequency, duration, and intensity in the future (Yin et al., 2023; Pokhrel et al., 2021), it is crucial to understand how post-drought vegetation will change.

The spatial variety in vegetative responses to drought events has received considerable recognition (Chen et al., 2022; Li et al., 2020). However, there is still a lack of consensus on the fundamental reasons for this heterogeneity. Efforts to attribute drought effects are typically divided into two categories: those associated with plants and those associated with geography. Particularly, certain research examines the effects of drought on different types of vegetation and regions (Li et al., 2020), considering plant types as the primary cause of variation. Moreover, increasing the variety of plants is a critical approach to improving plant life’s ability to withstand the challenges posed by drought (Liu et al., 2022). This phenomenon may be attributed to the collaborative effects of varying drought response methods among diverse vegetation. Furthermore, topography plays a crucial role in shaping vegetation’s functional benefits and tactics for responding to drought, as it affects both runoff and solar radiation. Shallow soils in high-slope areas have a low water retention capacity, causing them to dry rapidly after rainfall. In contrast, heavier soils near the base of slopes have the ability to store water, which helps alleviate the impacts of drought (Zhong et al., 2022). The angle of the slope has a direct impact on solar radiation, which in turn impacts photosynthesis and the drought response strategies of regional flora. Hence, it is necessary to examine the attributes of local flora and how it reacts to topographical elements in order to have a comprehensive understanding. The composition of the bedrock might also affect the vulnerability of the forest after a drought, since it determines the capacity to store water and supply nutrients through weathering processes (Callahan et al., 2022). With increased storage capacity, weathered rocks can facilitate accelerated development in wet years and raise the water requirements of vegetation, resulting in flora being unable to meet its water needs during drought, a process referred to as structural overshoot. Nevertheless, certain studies contradict this notion by suggesting that water stored in weathered rocks during humid periods can be utilized during drought years (Shi et al., 2023; Hollunder et al., 2021; Esteban et al., 2021). To fully comprehend the geographical variations in vegetation changes during drought circumstances, it is imperative to combine and incor porate the various individual components that have been extensively studied.

The main mechanisms contributing to vegetation die-back include diminished resistance and resilience (Hollunder et al., 2021; Ding et al., 2020; Liu et al., 2022), resulting in alterations to the ecosystem (Martinez-Vilalta and Lloret, 2016). Resilience is the rate at which ecosystems return to their previous condition after a disturbance, whereas resistance refers to the ability to remain unchanged amid drought events (Yang et al., 2023). Studies show substantial variations in the ability to withstand drought among different environmental settings (Li et al., 2020; Liu et al., 2018). According to certain studies, plants with a small amount of leaf surface area (Mcdowell and Allen, 2015) and intense water pressure (Liu et al., 2022), which grow in areas with unweathered, nutrient-rich bedrock or steep slopes, are more likely to withstand future drought conditions. This is because these plants have developed deeper roots over time to cope with prolonged water scarcity (Callahan et al., 2022). In contrast, other research suggests that locations with higher elevations, drier temperatures, and more soil volume have a strong ability to withstand drought. These areas are considered potential ref uges from drought due to the high water-holding capacity of their soil (Cartwright et al., 2020). Furthermore, certain studies have found that reduced vegetation resilience is the main reason for vegetation death after a drought. This is supported by a strong association between resilience and vegetation mortality (Boulton et al., 2022). Further exploration is needed to understand vegetation drought response methods, including both resistance and resilience, in different geographical settings due to the significant variation in research outcomes.

The drought that occurred in Southwest China from 2009 to 2011, commonly known as a “once-in-a-century drought,” had a significant negative effect on the forest ecosystem (Li et al., 2019). Yunnan, located in China’s southern border area, has a distinct geographical location and is less affected by the monsoon. Most parts of Yunnan face precipitation formation challenges due to its high terrain, elevated altitudes, and intricate topography dotted with numerous mountains. The region’s elevated topography restricts water vapor entry, resulting in inadequate rainfall and worsening the intensity and duration of droughts in Yunnan Province. As a result, Yunnan Province experiences longer and more intense droughts than other regions in southern China. The prolonged duration and severe water shortage of this drought led to a substantial decrease in vegetation coverage in Yunnan Province, resulting in capital losses exceeding 30 billion Yuan (Yuan et al., 2016). The aim of our research is to analyze the spatial and temporal patterns of vegetation mortality resulting from this exceptional drought and to understand the root causes in order to enhance preparedness for future episodes of severe drought. This study aims to fill a research vacuum on vegetation mortality in karst areas caused by drought. Furthermore, it investigates the various strategies employed by vegetation to cope with drought in different site conditions. Expanding upon the technique used by Liu et al., we utilized a Land Trendr model, which is renowned for its efficacy in many geographical areas, to conduct a comprehensive temporal analysis of NDVI and NBR (Liu et al., 2019). By employing this method, we were able to ascertain and measure the rates at which vegetation perishes as a consequence of severe drought occurrences. We also used a neural network model to carefully examine how different factors, including the type of vegetation that was there before the drought, geological features, and topographic features, affected spatial heterogeneity. This approach helped to understand the variations in vegetation response to drought events over a wide range of site conditions. Furthermore, this study aims to clarify the mechanisms behind drought induced vegetation mortality by defining vegetation resilience and resistance to drought. The aims of this study are to (1) examine the scale and severity of the Yunnan drought from 2009 to 2011 in a historical context, (2) clarify the reasons and factors that contribute to variations in vegetation affected by the drought, and (3) analyze the mechanisms by which drought leads to the death of vegetation under different circumstances.

## 2. Data and methods

## 2.1. Study region

The geographical coordinates of Yunnan Province range from 21◦8′N to 29◦15′N in latitude and from 91◦31′E to 106◦11′E in longitude. The research area includes six distinct climatic zones that are strongly associated with specific types of flora. These zones include the north tropical, south subtropical, mid-subtropical, north subtropical, midtemperate, and plateau climates. The study region consists of diverse topography, ranging from very high elevation (6663.6 m) with an average temperature of 5.4 ◦C to low elevation (below 100 m) with an average temperature of ${ 2 3 } ^ { \circ } \mathrm { C }$ . The province experiences significant variations in precipitation distribution, both seasonally and geographically. In the majority of regions, the mean annual precipitation (MAP) is around 1100 mm, while in the southern parts, it exceeds 1600 mm. (Zhang et al., 2021). The region is extensively affected by karst landforms, which are prone to significant erosion of soil and water. These landforms are particularly susceptible to drought episodes (Li et al., 2019) (Fig. 1).

## 2.2. Data

## 2.2.1. Drought metrics

This study utilized the Standardized Precipitation Evapotranspiration Index (SPEI) to accurately measure and quantify the severity of drought. This statistic highlights the significance of considering the effect of drought on vegetation and biomes. Various Standardized Precipitation-Evapotranspiration Indices (SPEIs) were calculated for different time periods ranging from 1 to 48 months. These indices indicate the cumulative water balance over the past n months, as described by Vicente-Serrano et al. (2013). To analyze the monthly fluctuations between dry and wet conditions, we employed the

![](images/9522ae4ca8f174357616782a7dda1f8f247676b47be8ddcffe74a8fc12356ab4.jpg)

![](images/57ba30259b4806367d92936efae5223ad4f921c20eb442b05ede0865633ff77e.jpg)

![](images/50cb807b57a8b8f748ee3cf5b7579280c4c4a5fb412bb7c1ed9a542928c68054.jpg)

![](images/1d941c58a1661e533a3452b34141acce98f78c24eff2fdf715f5727ac1f25f41.jpg)

![](images/454356380197df1820ec223b8c6cb05f6a62b79d5a6f6eb86684babc343c27d0.jpg)  
Fig. 1. (a) Location map of the research area, showing elevation indicated by background color. Elevation data were derived from the NASADEM data product (NASA JPL, 2020). (b) Distribution map of karst areas, sourced from monitoring data on rocky desertification in Yunnan Province. (c) Map of land use types, based on land cover data provided by the China National Ecological Science Data Center (Yu et al., 2022).

Standardized Precipitation Evapotranspiration Index (SPEI-1) produced using Python 3.10. The gridded Standardized Precipitation Evapotranspiration Index (SPEI) dataset, version 2.5, was provided at a spatial resolution of $0 . 5 ^ { \circ } \times 0 . 5 ^ { \circ }$ and a monthly time step. The dataset can be accessed at https://digital.csic.es/handle/10261/153475. The study utilized meteorological station data to produce the Standardized Precipitation-Evapotranspiration Index (SPEI) for validation and time series analysis.

## 2.2.2. Climate datasets

This study used monthly precipitation measurement products (Monthly Global Precipitation Measurement (GPM) v6) and MDIS products (MOD11A2 V6) to measure temperature and precipitation. The MOD11A2 V6 product (https://lpdaac.usgs.gov/products/mod 11a1v006/) offers an 8-day average land surface temperature (LST) with a resolution of 1 km × 1 km. Conversely, the GPM maintains a spatial resolution of 0.1◦ and provides monthly data. In order to align them, all of the data were resampled to a spatial resolution of 1 km x 1 km with a monthly time step. Furthermore, this study used meteorological station data to calculate and validate trends.

## 2.2.3. Vegetation indices

We used two satellited- derived vegetation indices to detect vegetation greenness impacted by the drought. These vegetation indexes, Normalized Difference Vegetation Index (NDVI) and normalized burn ratio (NBR), were obtained from Landsat 5 Thematic Mapper (TM),

Landsat 7 Enhanced Thematic Mapper Plus (ETM+), and Landsat 8 Operational Land Imager (OLI) images spanining from 1990 to 2020, and calculated by Google Earth Engine (GEE) cloud computing platform (https://earthengine.google.com/).

## 2.2.4. Factors affecting vegetation drought response

We selected six possible dominant factors from three dimensions, including vegetation coverage before drought, topographic features and geological background (Table 1). Here, all those data were resampled to a 1 km × 1 km spatial resolution.

Table 1  
Possible dominant factors data description and source

<table><tr><td>Possible dominant factors</td><td>Temporal resolution/extent</td><td>Spatial resolution</td><td>Data source</td></tr><tr><td>Average normalized Difference Vegetation Index (NDVI)</td><td>Monthly, 2008.4–2015.10</td><td>1 km</td><td>https://ladsweb.modaps.eosdis.nasa.gov</td></tr><tr><td>vegetation type</td><td>2010</td><td>1 km</td><td>https://www.gisrs.cn</td></tr><tr><td>Tree height</td><td>2005</td><td>927.67 m</td><td>Simard et al. (2011)</td></tr><tr><td>Slope</td><td>2010</td><td>90 m</td><td>https://www.gisrs.cn</td></tr><tr><td>Elevation</td><td>2010</td><td>90 m</td><td>https://www.gisrs.cn</td></tr><tr><td>Lithology</td><td>2010</td><td>5400 m</td><td>https://www.gisrs.cn</td></tr></table>

## 2.3. Methods

We used Landsat time series data and the Google Earth platform to randomly select sample points. Through a combination of visual interpretation and supervised classification, we calculated the threshold for vegetation mortality during the severe drought of 2009–2011. Subse quently, this threshold was entered into the Land Trendr algorithm to produce a map illustrating the extent of vegetation mortality across this specific timeframe. In addition, we determined and computed resistance and resilience to understand the vegetation’s approach to dryness prior to mortality. In order to examine the ways in which vegetation respond to drought in various site conditions, we utilized a neural network classification model to pick many factors for investigation, including vegetation, topography, and geology. The precise process is depicted in the subsequent figure (Fig. 2).

## 2.3.1. Drought identification

The Standardized Precipitation Evapotranspiration Index (SPEI) was computed after 1960 in order to examine the temporal patterns. The majority of Yunnan’s regions show a decreasing trend in drought severity of 0.0006/year $( \mathbb { R } ^ { \bar { 2 } } = 0 . 0 0 1 4 )$ , with no discernible change in the degree of drought. Nevertheless, the severity of drought conditions has increased since the beginning of the 21st century, especially during specific time frames such as August 1988 to September 1989, June 2001 to April 2002, and December 2009 to August 2011. Furthermore, the drought occurrence between 2009 and 2011 was the most severe (SPEI = −1.83) and longest-lasting, spanning a duration of 23 months, when compared to the drought events in 1988 and 2001. Throughout this time frame, we noticed a significant decrease in the Normalized Difference Vegetation Index (NDVI) compared to non-drought periods. This indicates that the drought experienced from 2009 to 2011 had a discernible effect on the ecosystems (Fig. 3).

## 2.3.2. Quantification of the mortality

The NBR images captured during the growing season, specifically from April to September each year, were selected to differentiate the features of vegetation that has been disrupted. Each of these inputs was fed into the Land Trendr, a temporal analysis technique, in order to identify the attributes of forest disruption, such as the exact timing and intensity of the disturbance. Land Trendr is a spectral time segmentation technique that can detect signal noise in time-series data. It identifies breakpoints in each pixel’s spectrum history and provides information about disturbance occurrence time, amplitude, and recovery time.

Land Trendr requires a certain set of control settings in order to guarantee the accuracy and reliability of change detection. To ascertain these characteristics, we conducted a random selection of 100 forest sample points to observe the variations in NBR during periods of drought. All of those locations experienced drought, leading to the destruction of vegetation. The normalized burn ratio (NBR) values of the samples before the drought event ranged from 124.64 to 783.09. By looking at the data visually and using supervised classification, we saw that NBR of pixels that showed a lot of plant death went down a lot. This drop exceeded 288.19. We set a limit for the Normalized Burn Ratio (NBR) before the drought to be above 124.64 and for the reduction in NBR after the drought to be greater than 288.18. This is done to rule out any other sources of interference and areas that aren’t forests.For each grid, the LandTrendr output was used to compute the vegetation death rate.

$$
\text { Mortality } = \frac {\frac {m a g}{m a g _ {m a x}} \times a r e a _ {d}}{a r e a _ {g i r d}}
$$

where mag is the disturbance intensity of vegetation; $\mathtt { m a g } _ { \mathrm { m a x } }$ is the maximum disturbance intensity of the area; area<sub>d</sub> is the disturbance area; $\mathtt { a r e a } _ { \mathtt { g r i d } }$ is the grid area.

## 2.3.3. Definition of vegetation drought resilience and resistance

The MODIS NDVI, which serves as an indicator of ecosystem productivity, was used in this study as the foundation for determining ecosystem drought tolerance. Here, we implemented the methodology proposed by Liu et al. (2022) in order to obtain the regional pattern of vegetation drought resistance.

$$
R _ {t} = \frac {Y _ {r e f}}{Y _ {r e f} - Y _ {e}}
$$

where $\mathrm { Y _ { r e f } }$ and ${ \mathrm { Y } } _ { \mathrm { e } }$ are vegetation productivity when not affected by drought and when affected by drought, respectively; the bigger the value of $\mathrm { R } _ { \mathrm { t } } ,$ the smaller the impact on the vegetation, the stronger the drought resistance.

In addition, we utilized the reduction in disturbance caused by unit vegetation increase to represent the drought resistance efficiency of vegetation, which can also be calculated from a linear regression between disturbance and NDVI:

![](images/cea24107b1c2fe7bb7e29cb7199f5aac73ed2838b007ce374c7e84cb2c03e7e5.jpg)  
Fig. 2. Research methodology flowchart. The orange section in the figure illustrates the methodology used for calculating the vegetation mortality rate map, while the green section depicts the attribution analysis of geographic spatial heterogeneity in vegetation mortality rate.

![](images/decd6f6098fb9777738470b509df18c8b6ae383818fcee7efc060a13f7fb5be3.jpg)

![](images/0bc95b61c7f84574990fd6133334c8995a437c78c5e25c05c4f5390f29b6fb6c.jpg)  
Fig. 3. Monthly changes of SPEI and NDVI from 1960 to 2020. (a) (b) The monthly changes in SPEI are shown in the sub graph above. The red part has a negative SPEI value, indicating relative drought, while the blue part has a positive SPEI value, indicating relative humidity. The smaller the SPEI value, the more severe the drought is. (c) NDVI residual time series (c4) after removing the trend (c2) the seasonality (c3).

$$
\gamma = \frac {| \Delta D |}{\Delta Y}
$$

where ΔD is the decrease in drought disturbance; ΔY is the increase in vegetation; the higher the $\gamma ,$ the smaller the drought disturbance and the stronger the drought resistance efficiency of vegetation as vegetation increases.

We used a similar approach to define drought resilience as the ratio of productivity under affected conditions to the drought restores increased vegetation productivity:

$$
R _ {s} = \frac {Y _ {r e v} - Y _ {e}}{Y _ {e}}
$$

where ${ \mathrm { Y } } _ { \mathrm { e } }$ and $\mathrm { Y } _ { \mathrm { r e v } }$ are vegetation productivity when affected by drought and when recover from drought, respectively; the smaller the value of $\mathrm { R } _ { \mathrm { t } } ,$ the bigger the impact on the vegetation, the stronger the drought resilience.

## 2.3.4. Attribution the spatial heterogeneity of the vegetation mortality

To identify the factors influencing the effects of the drought, we used an ensemble learning method called a random forest model (Duncan et al., 2019). This method is widely recognized for its high level of accuracy in classifying data and has been effectively utilized in multiple research projects (Cutler et al., 2007; Prasad et al., 2006). Before employing the random forest model, we fine-tuned and optimized the parameters. Augmenting the number of decision trees improves the model’s precision, but it also lengthens the computation time. Similarly, increasing the depth of the decision trees may improve accuracy, but it may also result in overfitting.

To ensure the precision of the estimated weights, we created 500 arbitrary trees, each ending in ten ultimate nodes. This resulted in a classification accuracy of 57.1%. We employed permutation testing to validate the correctness of the model. Afterwards, we chose six potential influential parameters—slope, elevation, pre-drought NDVI, tree height, vegetation type, and lithology (Table 1)—and evaluated the significance of each factor’s effect on vegetation death. The choice of these elements was influenced by recent studies on the effects of vegetation growth.

## 3. Results

## 3.1. Regional forest mortality patterns

This study utilized Landsat data (30 m resolution) to generate an unprecedented high-resolution map of forest mortality in Southwest China during a “once in a century drought.” We utilized the highest degree of vegetation loss obtained from LandTrender to compute the rate of vegetation mortality. The outcomes align well with the worldwide vegetation mortality rate during drought conditions, as reported by Steinkamp and Hickler (2015).

In the period from 2009 to 2013, we observed a total of 2024 disturbance patches in Yunnan province. These patches resulted in a disturbed forest area of 0.38 million hectares, which accounts for approximately 1.65% of the total vegetation area. The highest death rate of vegetation is concentrated in the eastern and southern regions of the study area, while it is least prevalent in the northwest (Fig. 4a). While the NDVI also shows a decline with time, there is a notable disparity between the geographical variations in the NDVI and the death rates. The decreasing NDVI area is predominantly located in the central region of Yunnan Province. Thus, during drought conditions, the distribution pattern may not necessarily result in vegetation dieback. Instead, vegetation survival may be more influenced by the growth conditions (see Fig. 4b).

In terms of temporal changes in time series, the vegetation mortality rate exhibits a pattern resembling an inverted U shape. This means that with the onset of the drought, the vegetation mortality rate steadily rises and reaches its highest point in 2012. In 2012, the year following the return of SPEI to normal levels, the areas of vegetation experiencing dieback reached their highest point, accounting for 10.80% of the total.

![](images/b945c0abad040227d15b1e7e8ab8be0c42a1666d29d4db31fed726f11d0d7154.jpg)

![](images/3c2b2fa4a1267e1e97aad7beba461a56e75cce16b93cdad143a0f14c9084af4e.jpg)

![](images/d0c071f888ff54a7051e43ad95ee6c4c4af6250e7cb8ed2c76978c7c8120a20b.jpg)  
Fig. 4. Characteristics of vegetation change and mortality rate in Yunnan Province. (a)The interannual variation trend of NDVI during the drought period from 2009 to 2013 (b) the distribution of vegetation mortality rate during the drought period, and (c) trends in the number of dead vegetation pixels from 2009 to 2015.

This percentage was even greater than during the most severe meteorological drought in 2010, which accounted for 8.3% (Fig. 4c).

![](images/b1a1fd0cb95a202a189807fd466f99594a861791943b9d15ccb346340eaf0279.jpg)  
Fig. 5. Smooth curves of vegetation, terrain, geological factors and changes in vegetation mortality rate (with a curve smoothing factor of 5000), with shaded areas indicating distribution density.

## 3.2. Drivers of heterogeneity in forest mortality

We used the Random Forest model and the curve smoothing tech nique to look at the effects of different factors in order to figure out why the changes in NDVI and plant mortality were not spread out evenly. The feature relevance of the six explanatory variables can be ranked from highest to lowest as follows: slope (0.276), elevation (0.276), predrought NDVI (0.191), tree height (0.108), vegetation type (0.096), and lithology (0.051). The mean squared error (MSE) is around 2%.

The slope has the most significant influence on the regional variability of vegetation mortality, with a linear correlation coefficient of −0.071% per degree (R2 = 0.01). Fig. 5 demonstrates a clear inverse relationship between slope and vegetation mortality rate, with a curve smoothing factor of 5000. The impact of elevation (0.26) is about equivalent to that of slope. The distinction, however, lies in the fact that vegetation mortality exhibits a variable decline in relation to changes in elevation, with valleys found at 2000 m and 3000 m. This pattern may also be linked to the vertical arrangement of vegetation. In regions characterized by elevated terrain and steep slopes, the rate of vegetation mortality is comparatively lower, enabling a greater number of plants to withstand dry conditions. Of all the parameters related to vegetation, the pre-drought NDVI has the most impact. During NDVI changes, the rate of vegetation death remains relatively stable at roughly 0.5% and exhibits a gradual increase over time $( \mathrm { R } ^ { 2 } = 0 . 0 0 7 )$ . Furthermore, within the height range of 0.8 to 1.5 m, there is an increasing trend in the vegetation death rate, with a growth rate of 3.5% per meter. On the other hand, when the tree’s height is between 3.4 and 4.0 m, the rate at which vegetation dies steadily drops by 5% for each additional meter of height. Arboreal vegetation has the highest survival rate among all types of vegetation, followed by grassland. Conversely, shrubs have the worst mortality rate. Typically, having a broader and taller canopy does not guarantee that vegetation will be able to resist a severe drought that occurs only once every century. Consequently, improving the effectiveness of forest drought resistance is presently an urgent matter that requires attention.

We conducted an examination of the susceptibility of forest mortality to various types of bedrock. More precisely, the mortality rate of vegetation in the clastic rock distribution region is significantly higher than that in the carbonate rock area, and it exceeds the mortality rate in the limestone distribution area, which has the second highest mortality rate, by more than 1%. The mortality rate of plants in the limestone-dolomite complex area is the lowest among carbonate rocks, with dolomite and limestone following suit (Fig. 5).

## 3.3. Characteristics of vegetation mortality after drought in different climatic regions

The sequence of vegetation mortality following the severe drought event was as follows: temperate zone, south subtropics, north tropics, south temperate zone, middle subtropical zone, north subtropics, and plateau climate zone. The results obtained from random forest models for various climate zones further validate that topographical characteristics, specifically slope, and height, exert a significant influence on vegetation death following drought. Furthermore, the importance of tree height and vegetation types in different temperate zones demon strates comparable trends. Nevertheless, the abundance of karst in the South Asian tropics results in considerably greater lithology significance in comparison to other areas. Previous estimates may have overestimated the impact of lithology, particularly carbonates, on vegetation mortality (Table 2).

## 4. Discussion

## 4.1. Drought vegetation response strategies

Worldwide research has proven the prediction that plants respond to drought events mostly through resistance and resilience (Wu et al., 2022; Yu et al., 2021). This assumption can also be demonstrated by examining the interannual fluctuations in vegetation mortality rates, which display a tendency that resembles an inverted U-shape when droughts occur. In our research, we computed post-drought resilience (RS) and resistance (RT) to gain a better understanding of the mechanism by which drought affects plants. Our study’s results indicate that vegetation’s ability to recover after a drought is more important than its ability to withstand the drought in southwest China (Xiao et al., 2024). Resistance and resilience both contribute to reducing vegetation mortality, but they exhibit different spatial distributions, as illustrated in Fig. 6. The regions exhibiting high drought resistance are primarily found in the northern mountainous sections of Yunnan Province and along the flanks of the Ailao Mountains. These locations are the primary regions of the Karst Plateau landform, characterized by elevated heights and steep slopes. On the other hand, regions that show a strong ability of plants to recover after a drought are mostly found in flat areas in the west, where the ability to withstand drought is not as strong (Fig. 6).

<table><tr><td></td><td>NDVI Trends</td><td>Mortality (%)</td><td>Slope (°)</td><td>Tem (°C)</td><td>Pre (mm)</td><td>Altitude (m)</td><td>Slope-mortality relative important</td><td>Lithology-mortality relative important</td><td>Altitude-mortality relative important</td><td>NDVI-mortality relative important</td><td>Vegetation type-mortality relative important</td><td>Canopy height-mortality relative important</td><td> $R^2$ </td></tr><tr><td>South Temperate Zone</td><td>-0.4</td><td>5.6%</td><td>19.4</td><td>25.1</td><td>28.4</td><td>2049.1</td><td>25.7%</td><td>5.1%</td><td>28.2%</td><td>19.7%</td><td>10.4%</td><td>10.7%</td><td>0.9</td></tr><tr><td>North Subtropics</td><td>-0.6</td><td>5.5%</td><td>15.0</td><td>26.4</td><td>22.9</td><td>1997.1</td><td>25.9%</td><td>5.1%</td><td>26.3%</td><td>24.7%</td><td>9.1%</td><td>8.9%</td><td>0.8</td></tr><tr><td>Middle Subtropical Zone</td><td>-0.4</td><td>5.6%</td><td>17.9</td><td>26.8</td><td>28.5</td><td>1634.5</td><td>26.2%</td><td>4.8%</td><td>27.2%</td><td>25.9%</td><td>6.8%</td><td>8.9%</td><td>0.7</td></tr><tr><td>South Subtropics</td><td>-0.3</td><td>5.9%</td><td>18.9</td><td>26.5</td><td>35.0</td><td>1437.8</td><td>25.5%</td><td>10.3%</td><td>26.5%</td><td>25.2%</td><td>2.7%</td><td>8.8%</td><td>0.6</td></tr><tr><td>North tropic</td><td>-0.2</td><td>5.7%</td><td>19.5</td><td>26.8</td><td>36.8</td><td>1282.5</td><td>24.2%</td><td>3.3%</td><td>26.6%</td><td>24,9%</td><td>11.6%</td><td>9.3%</td><td>0.6</td></tr><tr><td>Temperate zone</td><td>-0.7</td><td>6.1%</td><td>24.2</td><td>21.5</td><td>25.6</td><td>2818.7</td><td>26.2%</td><td>4.7%</td><td>27.8%</td><td>18.7%</td><td>10.6%</td><td>12.1%</td><td>0.8</td></tr><tr><td>Plateau climate zone</td><td>-0.10</td><td>5.4%</td><td>27.7</td><td>15.8</td><td>24.8</td><td>3398.8</td><td>24.3%</td><td>4.3%</td><td>27.3%</td><td>20.3%</td><td>11.7%</td><td>12.1%</td><td>0.1</td></tr><tr><td>Yunnan Province</td><td>-0.46</td><td>5.7%</td><td>16.9</td><td>24.5</td><td>29.4</td><td>1889.0</td><td>27.6%</td><td>5.1%</td><td>27.6%</td><td>19.1%</td><td>9.6%</td><td>10.8%</td><td>0.2</td></tr></table>

Possible dominant factors data description and source. Table 2

By utilizing both random forest regression and classification models, we have shown that topographical features have a significantly greater impact on vegetation’s reaction to drought. Interestingly, forests that showed stronger resistance and weaker ability to recover from the 2010 drought event may be found in regions with higher altitudes and steeper inclines, where the forests had a higher chance of surviving. Consistent with previous research (Vicente-Serrano et al., 2013; Xu et al., 2018; Wang et al., 2022), regions experiencing prolonged water scarcity show negligible harm to flora. The vegetation in these areas demonstrates a remarkable ability to withstand drought events due to its long-term adaptation to poor soil and water conditions, as well as its physiological, anatomical, and functional strategies. This adaptability is attrib uted to the influence of high slopes, high altitudes, and carbonate rocks, which have shaped the vegetation’s resilience to drought-related dam age (Fu et al., 2022; Devi and Reddy, 2020). According to Li et al. (2023), the process of physiological downregulation is most pronounced during the peak of drought in sub-humid and semi-arid areas. In dry regions, however, physiological anomalies appear one month before the peak of drought, which is sooner than in other regions. During the early phases of a drought, plants that are used to experiencing lengthy periods of water scarcity quickly adapt by closing their stomata. This reduces photosynthesis and carbon consumption, which helps to improve their ability to withstand drought conditions (Stocker et al., 2018). Furthermore, because of the persistent water scarcity conditions, the flora in these dry locations typically exhibits greater intrinsic resistance to drought, allowing it to endure more severe droughts (Ranjan et al., 2022). As a result, it is reasonable to speculate that increased resistance may explain the higher likelihood of survival observed in areas with chronic water scarcity, which are characterized by steep slopes, high elevations, and the presence of carbonate rock formations during the severe drought of 2010. As water scarcity becomes more prevalent in certain areas, the importance of resilience decreases, while resistance becomes more important. In relatively humid areas and regions marked by enduring water scarcity, the vegetation response strategies to drought can be explained by either lower resistance and higher resilience, or by higher resistance and lower resilience. This observation further confirms the trade-off between resistance and resilience (Li et al., 2020) (Fig. 7).

## 4.2. Implication for tree plantation campaigns

Since the 20th century, numerous afforestation initiatives have been implemented in various places worldwide, demonstrating their efficacy in mitigating temperature and extreme weather events. Currently, planted forests make up approximately 7% of the total global forest cover (Bukoski et al., 2022) and have the potential to play a vital role in addressing climate change.

Our research findings indicate that plants growing in persistently water-deficient areas exhibit greater resilience to drought. This discov ery has significant implications for future environmental conservation efforts, especially in the context of restoring ecosystems in complex karst settings. Rocky desertification is a concentrated occurrence in regions with high altitude, steep slope karst development, and relatively thin soil layers. This phenomenon is primarily caused by the combined influence of gravity. In areas prone to rocky desertification, afforestation is seen as the most effective strategy for improving land degradation (Jiang et al., 2014). Our article emphasized the ability of afforestation to withstand drought in such environments.

Based on the map depicting the effectiveness of vegetation in resisting drought ( ), we have determined that the drought resistance efficiency of vegetation planted on steep slopes has risen by 1.6% $( \mathrm { R } ^ { 2 } =$ 0.018) in comparison to flat areas (Fig. 8).

![](images/9dc4c3edec9acaaccca7b27af717c8e0207ce946d8eefc1ab77a33a915b47e63.jpg)  
Fig. 6. The drought resistance (a) and resilience (b) of vegetation are divided into five levels of 1–5, which are gradually increasing and represented by spatial distribution maps.

![](images/f79ce7a3a10389a2834636b196fd580553d753554342308ac4215a0c76809aef.jpg)

![](images/09da23114779b1929e3a0905211e1027822d1a2c8bd72f79e1676f27848d709f.jpg)  
Fig. 7. Identifying drivers of patterns of resilience (RS) and resistance (RT) under drought. Considered drivers include vegetation and topographical factor. Results show their relevance in explaining the spatial variabliities of RS and RT. \*denotes the variables in the top 3. The red and blue columns represent negative and positive correlations, respectively.

This increase will not only reduce vegetation mortality resulting from severe drought, but also save the soil in elevated regions. This discovery demonstrates the advantages of planting trees on steep inclines and aligns with prior global research. The robust ability of vegetation and soil microorganisms to withstand drought conditions leads to a mutually beneficial interaction, resulting in the presence of dense vegetation in this challenging environment that is adapted to drought. Another possible reason why drought works better in forests, according to the stress gradient hypothesis (SGH), is that when ecosystems are under stress, they form helpful relationships based on shared interests (He and Bertness, 2014). According to some experts, an increase in the diversity of plant species is believed to be an essential method for reducing mortality and improving the effectiveness of vegetation in resisting drought (Liu et al., 2022). (It is undeniable that certain areas of the ecosystem restoration project have been more vulnerable to drought because of the limited diversity of tree species and the absence of synergistic effects among communities, which has resulted in imperfect ecological functions.) Hence, we assert that implementing multi-species plant restoration in challenging site locations is both imperative and highly effective.

![](images/f6203da55b5dfe04b4d731725b4ce8026beeabe7957bd24d2d1d71362b757783.jpg)  
Fig. 8. Regression Analysis and Box Testing of Drought Resistance Efficiency and Slope.

## 4.3. Robustness in our quantification of vegetation die-back

In accordance with the recommendation of Senf et al (2020), we calculated the extent of vegetation die-back, excluding areas where dieback was not caused by drought, such as human activities or fire. However, it is challenging to completely exclude other causes of vegetation die-back unrelated to drought. As a result, the extent of droughtinduced vegetation dieback may be overstated. Due to the study’s focus on common extreme weather occurrences and the limited scope of this research, we did not analyze all potential non-drought-induced vegetation. Hence, forthcoming approaches should delve more extensively into additional elements that do not contribute to drought. While certain non-climate impact factors may still exist, our assessment of vegetation die-back after a drought is reliable and shows a strong correlation with the overall world numerical value (Steinkamp and Hickler, 2015).

## 5. Conclusions

In this study, we combined remote sensing data, random forests, and LandTrendr algorithms to look at how vegetation dies and is disturbed after a drought, as well as which geographical features are most likely to cause vegetation to die back. We also defined and calculated the resistance and resilience of vegetation in order to analyze the mechanism of vegetation dieback after drought. Our findings indicate that even an extremely rare drought event, occurring once in a century, has a minimal impact on vegetation mortality. Specifically, just 1.52% of the vegetation experienced die-back as a result of the drought. The spatial distribution of vegetation mortality rates does not align with the distribution of the decreasing trend in NDVI. Topographical characteristics, such as slope and elevation, have the most significant influence among the several elements affecting spatial heterogeneity when it comes to the distribution of vegetation mortality. The NDVI (Normalized Difference Vegetation Index) before drought follows these factors, tree height, and vegetation type. Vegetation is more likely to thrive in regions with high altitudes and steep slopes that have experienced prolonged periods of limited soil moisture. The primary cause of this phenomenon is that vegetation in regions experiencing prolonged water shortages exhibit more drought resistance than resilience, which contrasts with the drought response strategy observed in humid environments over an extended period of time. After comparing the elements that influence vegetation mortality in various climate zones, we discovered that the lithology in locations with a high concentration of karst is also a significant factor that affects vegetation death following drought. Thus, we highlight the significant influence of terrain and geology on the rate of vegetation mortality after a drought in karst environments, mostly through the manipulation of elasticity and resistance.

## CRediT authorship contribution statement

Linying Xiao: Writing – review & editing, Writing – original draft, Visualization, Validation, Software. Jinxing Zhou: Supervision, Resources, Methodology. Xiuqin Wu: Writing – review & editing. Muhammad Anas Khan: Writing – review & editing. Sen Zhao: Writing – review & editing. Xinliang Wu: Software.

## Declaration of competing interest

The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this paper.

## Data availability

Data will be made available on request.

## References

Anderegg, W.R.L., Schwalm, C., Biondi, F., et al., 2015. Pervasive drought legacies in forest ecosystems and their implications for carbon cycle models. Science 349, 528–532.

Boulton, C.A., Lenton, T.M., Boers, N., 2022. Pronounced loss of Amazon rainforest resilience since the early 2000s. Nat. Clim. Chang. 12, 271–+.

Bukoski, J.J., Cook-Patton, S.C., Melikov, C., Ban, H., Chen, J.L., Goldman, E.D., et al., 2022. Rates and drivers of aboveground carbon accumulation in global monoculture plantation forests. Nat. Commun.

Callahan, R.P., Riebe, C.S., Sklar, L.S., et al., 2022. Forest vulnerability to drought controlled by bedrock composition. Nat. Geosci. 15, 714–+.

Cartwright, J.M., Littlefield, C.E., Michalak, J.L., Lawler, J.J., Dobrowski, S.Z., 2020. Topographic, Soil, and Climate Drivers of Drought Sensitivity in Forests and Shrublands of the Pacific Northwest. Scientific Reports, USA, p. 10.

Chen, Q., Timmermans, J., Wen, W., Van Bodegom, P.M., 2022. A multi-metric assessment of drought vulnerability across different vegetation types using high resolution remote sensing. Sci. Total Environ. 832.

Cutler, D.R., Edwards, T.C., Beard, K.H., Cutler, A., Hess, K.T., 2007. Random forests for classification in ecology. Ecology 88, 2783–2792.

Devi, M.J., Reddy, V.R., 2020. Stomatal closure response to soil drying at different vapor pressure deficit conditions in maize. Plant Physiol. Biochem. 154, 714 722.

Ding, Y.B., Xu, J.T., Wang, X.W., Peng, X.B., Cai, H.J., 2020. Spatial and temporal effects of drought on Chinese vegetation under different coverage levels. Sci. Total Environ. 716.

Duncan, J.M.A., Boruff, B., Saunders, A., et al., 2019. Turning down the heat: an enhanced understanding of the relationship between urban vegetation and surface temperature at the city scale[J]. Sci. Total Environ. 656, 118 128.

Esteban, E.J.L., Castilho, C.V., Melgaco, K.L., Costa, F.R.C., 2021. The other side of droughts: wet extremes and topography as buffers of negative drought effects in an Amazonian forest. New Phytol. 229, 1995 2006.

Fu, Z., Ciais, P., Prentice, I.C., et al., 2022. Atmospheric dryness reduces photosynthesis along a large range of soil water deficits. Nat. Commun. 13.

Harris, N.L., Gibbs, D.A., Baccini, A., et al., 2021. Global maps of twenty-first century forest carbon fluxes. Nat. Clim. Chang. 11.

He, Q., Bertness, M.D., 2014. Extreme stresses, niches, and positive species interactions along stress gradients. Ecology 95, 1437–1443.

Hollunder, R.K., Mariotte, P., Carrijo, T.T., et al., 2021. Topography and vegetation structure mediate drought impacts on the understory of the South American Atlantic Forest. Sci. Total Environ. 766.

Jiang, Z.C., Lian, Y.Q., Qin, X.Q., 2014. Rocky desertification in Southwest China: impacts, causes, and restoration. Earth Sci. Rev. 132, 1–12.

Jiao, T., Williams, C.A., De Kauwe, M.G., Schwalm, C.R., Medlyn, B.E., 2021. Patterns of post-drought recovery are strongly influenced by drought duration, frequency, postdrought wetness, and bioclimatic setting. Glob. Chang. Biol. 27, 4630–4643.

Li, X.Y., Li, Y., Chen, A.P., Gao, M.D., Slette, I.J., Piao, S.L., 2019. The impact of the 2009/2010 drought on vegetation growth and terrestrial carbon balance in Southwest China. Agric. For. Meteorol. 269, 239 248

Li, X.Y., Piao, S.L., Wang, K., et al., 2020. Temporal trade-off between gymnosperm resistance and resilience increases forest sensitivity to extreme drought. Nat. Ecol Evol. 4, 1075–+.

Li, K.W., Tong, Z.J., Liu, X.P., Zhang, J.Q., Tong, S.Q., 2020. Quantitative assessment and driving force analysis of vegetation drought risk to climate change: methodology and application in Northeast China. Agric. For. Meteorol. 282.

Liu, Y., Kumar, M., Katul, G.G., et al., 2019. Reduced resilience as an early warning signal of forest mortality. Nat. Clim. Chang. 9, 880–885. https://doi.org/10.1038/s41558- 019-0583-9.

Liu, Y., Ding, Z., Chen, Y.A., et al., 2023c. Restored vegetation is more resistant to extreme drought events than natural vegetation in Southwest China. Sci. Total Environ. 866.

Liu, M.X., Huang, J.Y., Sun, A.Y., Wang, K.L., Chen, H.S., 2022. What roles can waterstressed vegetation play in agricultural droughts? Sci. Total Environ. 803

Liu, X.F., Sun, G.P., Fu, Z., Ciais, P., Feng, X.M., Li, J., Fu, B.J., 2023a. Compound droughts slow down the greening of the Earth. Glob. Chang. Biol. 29, 3072–3084.

Liu, X., Sun, G., Fu, Z., et al., 2023b. Compound droughts slow down the greening of the Earth[J]. Glob. Chang. Biol. 29 (11), 3072–3084.

Liu, L., Zhang, Y., Wu, S., et al., 2018. Water memory effects and their impacts on global vegetation productivity and resilience[J]. Sci. Rep. 8 (1), 2962.

Martinez-Vilalta, J., Lloret, F., 2016. Drought-induced vegetation shifts in terrestrial ecosystems: the key role of regeneration dynamics. Global Planet. Change 144, 94–108.

Mcdowell, N.G., Allen, C.D., 2015. Darcy’s law predicts widespread forest mortality under climate warming. Nat. Clim. Chang. 5, 669–672.

Pokhrel, Y., Felfelani, F., Satoh, Y., et al., 2021. Global terrestrial water storage and drought severity under climate change. Nat. Clim. Chang. 11.

Prasad, A.M., Iverson, L.R., Liaw, A., 2006. Newer classification and regression tree techniques: bagging and random forests for ecological prediction. Ecosystems 9, 181–199.

Ranjan, A., Sinha, R., Singla-Pareek, S.L., Pareek, A., Singh, A.K., 2022. Shaping the root system architecture in plants for adaptation to drought stress. Physiol. Plant. 174.

Rao, K., Anderegg, W.R.L., Sala, A., et al., 2019. Satellite-based vegetation optical depth as an indicator of drought-driven tree mortality[J]. Remote Sens. Environ. 227, 125 136.

Schwalm, C., Anderegg, W., Michalak, A., et al., 2017. Global patterns of drough recovery. Nature 548, 202–205. https://doi.org/10.1038/nature23021.

Senf, C., Buras, A., Zang, C.S., Rammig, A., Seidl, R., 2020. Excess forest mortality is consistently linked to drought across Europe. Nat. Commun. 11.

Shi, P., Bai, L.L., Zhao, Z., et al., 2023. Vegetation position impacts soil carbon losses on the slope of the Loess Plateau of China. Catena 222.

Steinkamp, J., Hickler, T., 2015. Is drought-induced forest dieback globally increasing? J. Ecol. 103, 31–43.

Stocker, B.D., Zscheischler, J., Keenan, T.F., Prentice, I.C., Penuelas, J., Seneviratne, S.I., 2018. Quantifying soil moisture impacts on light use efficiency across biomes. New Phytol. 218, 1430–1449.

Vicente-Serrano, S.M., Gouveia, C., Camarero, J.J., et al., 2013. Response of vegetation to drought time-scales across global land biomes. PNAS 110, 52–57.

Wang, W.D., Pijl, A., Tarolli, P., 2022. Future climate-zone shifts are threatening steepslope agriculture. Nature Food 3, 193–196.

Wu, D.H., Vargas, G.G., Powers, J.S., et al., 2022. Reduced ecosystem resilience quantifies fine-scale heterogeneity in tropical forest mortality responses to drought. Glob. Chang. Biol. 28, 2081–2094.

Xiao, L., Wu, X., Zhao, S., et al., 2024. Memory effects of vegetation after extreme weather events under various geological conditions in a typical karst watershed in southwestern China[J]. Agric. For. Meteorol. 345, 109840.

Xu, H.J., Wang, X.P., Zhao, C.Y., Yang, X.M., 2018. Diverse responses of vegetation growth to meteorological drought across climate zones and land biomes in northern China from 1981 to 2014. Agric. For. Meteorol. 262, 1 13.

Yang, W., Yang, J.J., Fan, Y., et al., 2023. The two sides of resistance-resilience relationship in both aboveground and belowground communities in the Eurasian steppe. New Phytol. 239, 350–363.

Yin, J.B., Gentine, P., Slater, L., et al., 2023. Future socio-ecosystem productivity threatened by compound drought-heatwave events. Nat. Sustainability 6, 259- .

Yu, H., Ma, Q., Liu, X., et al., 2021. Resistance, recovery, and resilience of desert steppe to precipitation alterations with nitrogen deposition[J]. J. Clean. Prod. 317, 128434.

Yuan, W.P., Cai, W.W., Chen, Y., et al., 2016. Severe summer heatwave and drough strongly reduced carbon uptake in Southern China. Sci. Rep. 6.

Zhang, Y.Q., Ai, J.J., Sun, Q.W., et al., 2021. Soil organic carbon and total nitrogen stocks as affected by vegetation types and altitude across the mountainous regions in the

Zhong, F., Xu, X., Li, Z., et al., 2022. Relationships between lithology, topography, soil, and vegetation, and their implications for karst vegetation restoration[J]. Catena 209, 105831.