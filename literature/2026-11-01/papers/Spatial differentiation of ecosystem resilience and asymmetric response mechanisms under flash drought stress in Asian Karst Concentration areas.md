# Spatial differentiation of ecosystem resilience and asymmetric response mechanisms under flash drought stress in Asian Karst Concentration areas

Haoze Ding <sup>a,b,c</sup> , Qi Guo <sup>a,b,c</sup> , Yuan $\operatorname { L i } ^ { \mathrm { a , b , c } } ( \mathbb { b } ) ,$ Zhengshan Chen <sup>a,b,c</sup>, Qiuwen Zhou <sup>a,b,c</sup>, Shunfu Yang <sup>d</sup>, Yuluan Zhao <sup>a,b,c,\*</sup>

<sup>a</sup> School of Geography and Environmental Science, Guizhou Normal University, Guiyang, 550025, China <sup>b</sup> Anshun Field Scientific Observation and Research Station of Agricultural Environment, Ministry of Agriculture and Rural Affairs, Anshun, 561000, China

<sup>c</sup> Guanling Karst Ecosystem Field Scientific Observation and Research Station, Guizhou Normal University, Anshun, 561000, China

<sup>d</sup> School of Geography and Tourism, Shaanxi Normal University, Xi’an, 710119, China

## A R T I C L E I N F O

Keywords: Flash drought Karst Soil moisture Water use efficiency Ecological resilience Ecohydrology

## A B S T R A C T

Study focus: This study aimed to determine how karst geomorphology regulates ecosystem resistance and recovery under flash drought stress. We integrated satellite-derived gross primary productivity, evapotranspiration, soil moisture, and evaporative stress index datasets from 2000 to 2024, and applied a multidimensional resilience framework, nonlinear threshold detection, and soil moisture–water use efficiency coupling analysis.

New hydrological insights for the region: The estimated karst–non-karst contrast in GPP-based resistance was sensitive to spatial grouping and uncertainty assumptions, while karst areas exhibited a smaller next-year productivity rebound. Estimated breakpoints in the resis tance–severity relationships differed between karst and non-karst areas (52.8 vs. 105.2), with distinct changes in fitted slopes rather than a common physiological collapse pattern. Median soi moisture–water-use efficiency correlations were higher in karst areas within each aridity class, although the direction of the contrast varied among aridity–vegetation combinations. Event composites showed less negative standardized soil-moisture minima but more negative water-useefficiency minima in karst areas. Together, these findings highlight the importance of considering productivity maintenance, subsequent rebound, and water-related responses jointly when assessing flash-drought vulnerability. Hydrological heterogeneity provides a plausible explana tion for these contrasting responses, but the contribution of subsurface buffering requires inde pendent validation.

## 1. Introduction

Under the backdrop of global climate warming, the paradigm of drought evolution is undergoing a profound transformation—traditional slow-onset droughts are rapidly giving way to "flash droughts" (Christian et al., 2021; Yuan et al., 2023). Characterized by an anomalously rapid onset rate and devastating ecological destructiveness, flash droughts can trigger severe soi moisture depletion, plummeting vegetation evapotranspiration, and a precipitous decline in ecosystem productivity within mere weeks (Mo and Lettenmaier, 2015; Otkin et al., 2018). Recent syntheses indicate a significant decline in the flash drought resistance of Northern Hemisphere vegetation over the past two decades, with East Asia emerging as one of the most prominent hotspots for this degradation (Yuan et al., 2019; Zhang et al., 2025). Furthermore, in drylands globally, over 57% of vegetated areas have already experienced diminished resilience (Kong et al., 2026). Consequently, flash droughts are no longer localized, episodic anomalies rather, they are systematically reshaping the functional baseline of global vegetation. Accurately characterizing and predicting flash drought resilience across diverse ecological contexts has thus become a core scientific imperative for assessing the future fate of terrestrial ecosystems (Sreeparvathy et al., 2025).

The concept of ecological resilience was first formalized by Holling (1973). Subsequently, Hodgson et al. (2015) systematically disentangled this framework into three complementary dimensions: resistance (the ability to maintain functionality during distur bances), recovery (the speed of returning from a damaged state), and recovery completeness. Ingrisch and Bahn (2018) further extended this framework into drought research, proposing multidimensional quantification methods based on vegetation productivity metrics. Crucially, systematic tradeoffs frequently exist among these resilience dimensions. From regional to global scales, numerous studies consistently demonstrate that long-lived woody plants, such as forests, generally exhibit a "high-resistance/low-recovery" combination, whereas grasslands and arid ecosystems display the inverse "low-resistance/high-recovery" paradigm (De Keersmaecker et al., 2015; Yao et al., 2024). Within this framework, Water Use Efficiency (WUE = GPP / ET) emerges as a pivotal physiological proxy, comprehensively reflecting the coupling efficiency between carbon assimilation and water consumption, thereby unraveling the regulatory strategies of vegetation under flash drought stress (Beer et al., 2009; Keenan et al., 2013). Conversely, Soil Moisture (SM) acts as the fundamental supply-side constraint. The SM–WUE coupling is essentially delineated by Budyko (1974) classical dichotomy: negative coupling in humid, energy-limited zones vs. positive coupling in arid, water-limited zones (Nelson et al., 2018; Stocker et al., 2018). However, this classical dichotomy relies heavily on the climatological demarcation of arid and humid zones—typically based on the relationship between precipitation and potential evapotranspiration—while severely neglecting how highly heterogeneous habitats with distinctive dual hydrological structures, such as Karst landscapes, profoundly reshape actual water availability. This oversimplification of geomorphological constraints frequently leads to misjudgments regarding the true boundaries of water limitation, thereby obscuring the authentic physiological feedbacks of vegetation when confronted with rapid water deficits

This distinctive dual hydrological structure fundamentally rewrites the dynamics of water supply and demand in Karst environments, making it a critical vantage point for testing and transcending the limitations of traditional climatic zoning. Karst geomorphology plays a dual role in ecohydrological processes. On one hand, well-developed subterranean conduit networks facilitate the rapid conversion of surface runoff into subsurface flow, leaving the superficial soil layer in a chronic state of low water retention (Jiang et al., 2014). On the other hand, recent field evidence indicates that fissure soil water and rock fissure water can serve as key alternative subsurface water sources for vegetation in karst ecosystems (Cai et al., 2023; Zheng et al., 2026). Karst hydrological heterogeneity provides a basis for expecting spatially variable vegetation responses to drought. Preferential flow and heterogeneous storage influence water availability, while plant access to subsurface water can modify drought vulnerability (Ding et al., 2021; Hartmann et al., 2014). These processes do not imply that all karst vegetation lacks hydrological buffering. Their ecological consequences depend on the accessibility of stored water and the environmental context. Flash droughts add a temporal challenge because vegetation carbon uptake can decline rapidly as water stress develops. FLUXNET observations demonstrate rapid productivity responses during flash droughts and differences in carbon–water responses among vegetation types (Zhang and Yuan, 2020). Consequently, productivity maintenance during drought, subsequent productivity rebound, and ecosystem water-use efficiency describe complementary aspects of response. A smaller rebound in the following year should not automatically be interpreted as a longer recovery time. What remains insufficiently resolved is whether mean productivity resistance gives a consistent assessment of karst–non-karst vulnerability when the severity dependence of resistance, next-year productivity rebound, and soil-moisture–water-use-efficiency associations are examined together within comparable aridity and vegetation categories. The core scientific question is therefore: How does the inferred contrast in flash-drought vulnerability between karst and non-karst landscapes change when these response dimensions are considered jointly? To address this question, we combine remote sensing and reanalysis data for the Asian Karst Concentration in southwestern China and the Indochinese Peninsula. We compare productivity responses, estimate breakpoints in resistance–severity relationships, and examine soil moisture (SM) and water-use efficiency (WUE, defined as GPP/ET) through interannual correlations, cross-stratified comparisons, and event composites. Spatial drought trends provide context for interpreting exposure. This joint assessment extends regional mean comparisons by examining response dependence on drought severity and environmental setting. It provides comparative observationa evidence for evaluating functional vulnerability and developing hydrological interpretations; it does not directly measure subsurface buffering or isolate the causal contribution of karst lithology.

## 2. Materials and methods

## 2.1. Study area

Following the regional terminology used by Yang et al. (2024), this study refers to the examined domain as the Asian karst concentrated distribution area (AKC). The study domain covers southwestern China and portions of the Indochinese Peninsula (Fig. 1). The analyses and conclusions are restricted to this domain.According to the World Karst Aquifer Mapping (WOKAM) project and regional geological datasets, this region is characterized by an extensive distribution of soluble carbonate rocks and highl heterogeneous geomorphological features. Driven jointly by the East Asian and Indian monsoons, the regional climate exhibits a pronounced spatial precipitation gradient and highly synchronized seasonal hydrothermal dynamics (i.e., concurrent periods of peak temperature and precipitation). The region sustains highly diverse vegetation, comprising a mosaic of ecosystem types that include evergreen broadleaf forests, deciduous broadleaf forests, shrublands, and grasslands. Crucially, constrained by the exceptionally shallow soil profiles and high rates of bedrock outcropping inherent to Karst habitats, the local vegetation is acutely sensitive to precipitation variability. Consequently, the AKC serves as an ideal natural laboratory for investigating the responses of terrestria ecosystems to water stress.

## 2.2. Data sources and preprocessing

This study integrates satellite-derived products, reanalysis data, and ancillary spatial datasets (Table 1). GOSIF-GPP provides productivity estimates; MODIS products provide evapotranspiration, potential evapotranspiration, and land-cover information; ERA5- Land provides soil moisture and air temperature; and CHIRPS provides precipitation. Aridity and geological datasets characterize the environmental setting. Specifically, Evapotranspiration (ET) and potential evapotranspiration (PET) were obtained from the MODIS/ Terra MOD16A2GF Version 6.1 product (Running et al., 2021). The MOD16 algorithm is described by Mu et al. (2011). Land-cover classifications were obtained from MODIS/Terra + Aqua MCD12Q1 Version 6.1 (Friedl and Sulla-Menashe, 2022), using the International Geosphere-Biosphere Programme (IGBP) classification.

Land-cover classes from the MCD12Q1 IGBP classification were reclassified into four broad vegetation groups for analysis, labelled evergreen forest, deciduous forest, grassland, and cropland. These labels represent the aggregated categories used in this study rather than individual classes in the original IGBP scheme. Urban and built-up lands, water bodies, permanent snow and ice, barren land, and permanent wetlands were excluded from the analysis.

Ecosystem productivity was evaluated using the 0.05◦ resolution GOSIF-GPP dataset (Li and Xiao, 2019). Soil moisture and 2-m air temperature were obtained from ERA5-Land (Munoz-Sabater ˜ et al., 2021). For the event-composite analysis, soil moisture was sampled from the hourly dataset at 00:00, 06:00, 12:00, and 18:00 UTC each day (Munoz ˜ Sabater, 2019), and these samples were averaged within each 8-day interval. Annual precipitation was derived from CHIRPS v2.0 (Funk et al., 2015). Aridity classes were defined using the Global Aridity Index and Potential Evapotranspiration Database v3 (Zomer et al., 2022). By integrating Solar-Induced Chlorophyll Fluorescence (SIF) observations from OCO-2 with meteorological drivers, this dataset robustly captures the dynamic physiological shocks of flash droughts on vegetation photosynthetic capacity. The geological basemap was synthesized using the World Karst Aquifer Mapping project (Chen et al., 2017) and soluble rock classes from the Global Lithological Map database (Hartmann and Moosdorf, 2012).

![](images/f431bfc176a141ad67d4e9e601048c02a961efea1360df7130767b8ed6079aca.jpg)  
Fig. 1. Geographical overview of the study area.

Table 1  
Overview of the main datasets used in this study.

<table><tr><td>Data category</td><td>Variable</td><td>Dataset/Product</td><td>Spatial resolution</td><td>Temporal resolution</td><td>Time span</td></tr><tr><td>Vegetation productivity</td><td>GPP (Gross Primary Productivity)</td><td>GOSIF GPP V2</td><td>0.05°</td><td>8-day</td><td>2000–2024</td></tr><tr><td>Hydro-meteorology</td><td>ET (Actual Evapotranspiration)</td><td>MOD16A2GF</td><td>500 m</td><td>8-day</td><td>2000–2024</td></tr><tr><td>Hydro-meteorology</td><td>PET (Potential Evapotranspiration)</td><td>MOD16A2GF</td><td>500 m</td><td>8-day</td><td>2000–2024</td></tr><tr><td>Hydro-meteorology</td><td>SM (Soil Moisture, four layers)</td><td>ERA5-Land</td><td>0.1°</td><td>Hourly</td><td>2000–2024</td></tr><tr><td>Climate background</td><td>Precipitation</td><td>CHIRPS v2.0</td><td>0.05°</td><td>Annual</td><td>2000–2024</td></tr><tr><td>Climate background</td><td>2-m Air Temperature</td><td>ERA5-Land</td><td>0.1°</td><td>Monthly</td><td>2000–2024</td></tr><tr><td>Geological background</td><td>Karst distribution</td><td>WOKAM + GLiM</td><td>Vector</td><td>Static</td><td>Baseline period</td></tr><tr><td>Land cover</td><td>Vegetation functional groups</td><td>MCD12Q1(IGBP)</td><td>500 m</td><td>Annual (2024)</td><td>2024</td></tr><tr><td>Climate classification</td><td>Global Aridity Index</td><td>CGIAR-CSIAIv3</td><td>0.008°</td><td>Climatology</td><td>1970–2000</td></tr></table>

Notes: GPP was derived from GOSIF-GPP V2 (Li and Xiao, 2019). ET and PET were obtained from the MOD16A2GF V061 product (Running et al., 2021), whose algorithm is based on the Penman–Monteith framework (Mu et al., 2011). Soil moisture and 2-m air temperature were obtained from ERA5-Land. For event composites, soil moisture was sampled every six hours from the hourly product (Munoz ˜ Sabater, 2019) and averaged over the matching 8-day windows. The interannual SM analysis used monthly means aggregated over January–December or March–October.Precipitation was derived from CHIRPS v2.0 (Funk et al., 2015). Karst distribution was delineated using WOKAM (Chen et al., 2017) and validated with soluble rock classes from GLiM (Hartmann and Moosdorf, 2012). Vegetation functional groups were classified from MCD12Q1 V061 using the IGBP scheme (Fried and Sulla-Menashe, 2022).Aridity classes were defined using the Global Aridity Index and Potential Evapotranspiration Database v3 (Zomer et al., 2022). All raster datasets were resampled to a $_ { 1 } 0 . 0 5 ^ { \circ }$ grid under the EPSG:4326 coordinate system.

During the preprocessing phase of the time-series datasets, observational records from the non-growing season (i.e., winter months) were systematically excluded. The rationale for this temporal filtering is that winter temperatures and incident radiation in Southwestern China are severely restricted, forcing vegetation into dormancy or substantially decelerating its growth. Under such conditions, the naturally depressed baseline of evapotranspiration frequently triggers false positives in anomaly-based drought indices. Therefore, excising winter data effectively eliminates the background noise associated with the dormant phase, allowing the analysis to strictly isolate and accurately quantify the true ecophysiological responses of vegetation to water stress during periods of vigorous growth (Christian et al., 2019).

## 2.3. Methodology

## 2.3.1. Formulation of the evaporative stress index (ESI) and flash drought identification

This study adopted the Evaporative Stress Index (ESI) as the primary metric for identifying flash drought events. Defined as the standardized ratio of actual evapotranspiration (ET) to potential evapotranspiration (PET), the ESI directly reflects the dynamic balance between surface water supply and atmospheric evaporative demand. Compared to traditional precipitation or soil moisturebased indicators, the ESI is highly sensitive in capturing the rapid physiological responses of vegetation during the incipient stages of heatwaves or abrupt water deficits, making it particularly robust for monitoring rapidly intensifying flash droughts. The tempora coverage spans from 2000 to 2024 with an 8-day temporal resolution (consistent with the MODIS composite intervals), and the spatial resolution was resampled to 0.05∘ to align with the requirements of the regional analysis.

To enable unbiased cross-latitudinal comparisons of water stress, the standardized ESI was calculated at the pixel level. Initially, the evaporative ratio (r) was computed for each pixel as $\begin{array} { r } { r = E T / P E T . } \end{array}$ . Subsequently, utilizing the 25-year long-term observational record we derived the multi-year mean (μ) and standard deviation (σ) for each specific temporal window (i.e., 46 composite periods per year). The index was then normalized using the standard Z-score formulation:

$$
E S I _ {i, j} = \frac {\boldsymbol {r} _ {i , j} - \overline {{\boldsymbol {r} _ {j}}}}{\sigma (\boldsymbol {r} _ {j})}
$$

Building upon the standardized ESI time series, we adopted the percentile-based flash drought identification framework proposed by Christian et al. (2021). Crucially, we introduced a localized parameter adaptation to this framework to better accommodate the highly fragmented geomorphology and rapid hydrological response rates characteristic of Southwestern China. Specifically, a flash drought event is positively identified only when the following three criteria are concurrently satisfied: (1) a rapid intensification phase during which the ESI drops by more than 20 %ile points within a 32-day window (i.e., four 8-day periods); (2) the terminal ESI value at the end of this intensification phase falls to or below the 20th percentile; and (3) the established drought state persists for a minimum duration of two temporal steps (i.e., 16 days).

## 2.3.2. Quantitative extraction of multidimensional flash drought characteristics

Building upon the identification of flash drought events, this study introduced a multidimensional feature extraction framework based on the Run Theory (Yevjevich, 1967) to quantify the Duration (D) and Severity (S) of each event.

Duration (D) reflects the temporal length during which the ecosystem remains under continuous water stress. It is defined as the total elapsed time from the onset of the flash drought (when the ESI percentile drops below the identification threshold) until the ESI recovers and sustainably rises above the 30th percentile:

$$
D = N _ {s t e p s} \times 8
$$

where $N _ { s t e p s }$ is the total number of consecutive 8-day time steps from the onset to the termination of the drought state. Severity S quantifies the cumulative water deficit during the drought and serves as a key driver of gross primary productivity (GPP) impairment. Using the recovery threshold (ESI = 30th percentile) as the baseline, S is computed as the time integral of the deviation of the ESI percentile from this baseline:

$$
S = \sum_ {t = t _ {\text {start}}} ^ {t _ {\text {end}}} (3 0 - E S I _ {t})
$$

where $t _ { \mathrm { s t a r t } }$ and $t _ { \mathrm { e n d } }$ denote the beginning and end time steps of the drought state. Larger S values indicate more severe water deprivation and a correspondingly higher risk of ecosystem damage.

## 2.3.3. Assessment of ecological resilience metrics

Based on the identified water stress events, three complementary metrics—resistance, resilience, and recovery efficiency—were employed to quantitatively evaluate the ecosystem's response and recovery capacity under water stress (Hodgson et al., 2015; Ingrisch and Bahn, 2018). All three metrics utilize the baseline GPP (the multi-year concurrent average over the 2000–2024 period) as a standard reference:

$$
G P P _ {a v g} = \frac {1}{n} \sum_ {\text { all   years }} ^ {t _ {0} \rightarrow t _ {1}} G P P
$$

Resistance reflects the vegetation's capacity to maintain its productivity functions during the active stress phase. It is mathematically defined as the ratio of the observed GPP during the stress period to the baseline GPP:

$$
\text { Resistance } = \frac {1}{t _ {1} - t _ {0} + 1} \sum_ {j = t _ {0}} ^ {t _ {1}} \frac {\text { GPP } _ {i j}}{\text { GPP } _ {\text { avg } , j}}
$$

Resilience reflects the absolute magnitude of productivity recovery within one year following the cessation of the stress event. It is defined as the ratio of the GPP increment in the subsequent concurrent period relative to the stress-period GPP, normalized by the baseline GPP:

$$
\text { Resilience } = \frac {1}{t _ {1} - t _ {0} + 1} \sum_ {j = t _ {0}} ^ {t _ {1}} \frac {\text { GPP } _ {i + 1 , j} - \text { GPP } _ {i , j}}{\text { GPP } _ {\text { avg } , j}}
$$

Recovery Efficiency provides a comprehensive assessment of the overall recovery status. It is defined as the ratio of the GPP in the subsequent concurrent period post-event to the baseline GPP:

$$
\text { Recovery\_efficiency } _ {i} = \frac {1}{t _ {1} - t _ {0} + 1} \sum_ {j = t _ {0}} ^ {t _ {1}} \frac {\text { GPP } _ {i + 1 , j}}{\text { GPP } _ {\text { avg } , j}}
$$

where $G P P _ { i , j }$ represents the gross primary productivity on day j of year i, and $G P P _ { a v g , j }$ denotes the multi-year baseline average for day j. A calculated ratio of 1 indicates that the ecosystem is operating at a normal, undisturbed level.

## 2.3.4. Water use efficiency

Water Use Efficiency (WUE) is defined as the amount of carbon fixed per unit of water consumed, i.e., $W U E = G P P / E T ( { \bf g } { \bf C } { \cdot } { \bf k g } ^ { - 1 }$ H₂O), and integratively reflects the coupling between carbon assimilation and water loss (Beer et al., 2009; Keenan et al., 2013). An increase in WUE indicates that vegetation enhances carbon gain per unit water loss through stomatal regulation, representing a conservative adaptive strategy; a decrease in WUE implies that photosynthesis is suppressed more strongly than transpiration, signalling the onset of functional impairment. The difference between WUE during the flash drought period and the corresponding normal period, $\Delta W U E = W U E _ { \mathrm { s t r e s s } } - W U E _ { \mathrm { n o r m a l } }$ , further delineates the direction of physiological adjustment: $\Delta W U E > 0$ indicates that vegetation adopts a water-saving strategy via stomatal regulation.

## 2.3.5. Statistical analysis and the analytical framework for coupling mechanisms

The statistical framework comprises four tiers: group difference tests, trend identification, nonlinear threshold detection, and a three-level coupling analysis.

Group differences and trend analysis: Differences in resilience metrics between karst and non-karst areas, vegetation functiona groups, and aridity classes are examined. Multi-group comparisons use the Kruskal–Wallis test, and pairwise comparisons employ the Mann–Whitney U test. Interannual trends are assessed with the Mann–Kendall test (Kendall, 1975; Mann, 1945) and the Theil–Sen slope estimator (Sen, 1968), with the significance level set at $\alpha = 0 . 0 5$

Nonlinear threshold detection: A continuous piecewise linear regression was fitted to the relationship between GPP-based resistance (R) and mean event-level cumulative drought severity (S):

$$
R = a + b _ {1} S + b _ {2} \max (0, S - T) + \varepsilon
$$

here, a is the intercept, T is the estimated breakpoint, b₁ is the slope below $^ { \mathrm { T , } }$ and b₂ is the change in slope at T. The slope above T is b₁ + b₂. Fifty candidate breakpoints were evaluated between the 10th and 90th percentiles of S. For each candidate, coefficients were estimated by least squares, and the breakpoint minimizing the residual sum of squares was selected. The estimated breakpoint describes a change in the fitted association rather than a directly observed physiological failure point.

For pixel i, mean event-level cumulative severity was calculated as:

$$
S _ {i} = \frac {1}{N _ {i}} \sum_ {e = 1} ^ {N _ {i}} \sum_ {t \in E _ {i, e}} \max (0, 3 0 - P _ {i, t})
$$

here, $\mathrm { P _ { i , t } }$ is the ESI percentile on a 0–100 scale, $\operatorname { E i } , \mathrm { e }$ contains the valid 8-day time steps within the identified event window, and Nᵢ is the number of identified events at that pixel. Deficits below the 30th percentile were summed over time steps without multiplication by eight and then averaged across events. S is therefore a cumulative-deficit index rather than a single percentile and can exceed 100.

## 2.3.6. Soil moisture aggregation and SM–WUE analysis

Four nested soil-moisture variables were constructed from the native ERA5-Land layers to examine how interannual soil moisture–water-use efficiency (SM–WUE) relationships varied with soil depth and temporal aggregation. Let $\begin{array} { r } { \theta _ { 1 } , \theta _ { 2 } , \theta _ { 3 } , } \end{array}$ and θ₄ denote volumetric soil water content $( \mathbf { m } ^ { 3 } \mathbf { m } ^ { - 3 } )$ in the native layers at 0–7, 7–28, 28–100, and 100–289 cm, respectively. Their corresponding thicknesses were 7, 21, 72, and 189 cm. Soil moisture over the cumulative depth intervals of 0–7 cm (L1), 0–28 cm (L12), 0–100 cm (L123), and 0–289 cm (L1234) was calculated by thickness-weighted averaging:

$$
\begin{array}{l} \mathrm{L1} = \theta_ {1} \\ \mathrm{L12} = \frac {7 \theta_ {1} + 2 1 \theta_ {2}}{2 8} \\ \mathrm{L123} = \frac {7 \theta_ {1} + 2 1 \theta_ {2} + 7 2 \theta_ {3}}{1 0 0} \\ \mathrm{L1234} = \frac {7 \theta_ {1} + 2 1 \theta_ {2} + 7 2 \theta_ {3} + 1 8 9 \theta_ {4}}{2 8 9} \end{array}
$$

For each aggregate, the volumetric water content of each contributing layer was multiplied by its thickness, and the sum was divided by the total thickness of the combined profile. For example, the weights used for L123 were 0.07, 0.21, and 0.72. These variables retained volumetric water-content units and represented overlapping depth intervals rather than four independent soil layers or water-storage amounts.

Two temporal aggregation windows were defined within each year: January–December (ALL) and March–October (GS). For each depth aggregate, monthly values were averaged within the corresponding window. When all monthly values were available, these averages were calculated as

$$
\mathrm{SM} _ {\mathrm{d}, \mathrm{y}, \mathrm{ALL}} = \frac {1}{1 2} \sum_ {\mathrm{m} = 1} ^ {1 2} \mathrm{SM} _ {\mathrm{d}, \mathrm{y}, \mathrm{m}}
$$

$$
\mathrm{SM} _ {\mathrm{d}, \mathrm{y}, \mathrm{GS}} = \frac {1}{8} \sum_ {\mathrm{m} = 3} ^ {1 0} \mathrm{SM} _ {\mathrm{d}, \mathrm{y}, \mathrm{m}}
$$

here, d denotes the depth aggregate, y denotes the year, and m denotes the month. When monthly values were missing, only valid values were included in the sum, and the denominator was replaced by the number of valid months within the selected window. Monthly values received equal weight, without weighting by month length. GS was a fixed March–October analysis window applied consistently across the study area rather than a growing season identified separately for each pixel. These annual and seasonal aggregation windows were distinct from the 8-day intervals used in the event-composite analysis.

For each pixel, the resulting interannual SM series was paired with the WUE series for the same temporal window. Only years with valid values for both variables were retained, and Pearson correlations (Wilks, 2019) were calculated when at least 10 paired annua observations were available:

$$
\mathbf {r} = \frac {\sum_ {\mathrm{y} \in \mathrm{Y}} \left(\mathrm{SM} _ {\mathrm{y}} - \overline {{\mathrm{SM}}}\right) \left(\mathrm{WUE} _ {\mathrm{y}} - \overline {{\mathrm{WUE}}}\right)}{\sqrt {\sum_ {\mathrm{y} \in \mathrm{Y}} \left(\mathrm{SM} _ {\mathrm{y}} - \overline {{\mathrm{SM}}}\right) ^ {2} \sum_ {\mathrm{y} \in \mathrm{Y}} \left(\mathrm{WUE} _ {\mathrm{y}} - \overline {{\mathrm{WUE}}}\right) ^ {2}}}
$$

Here, Y denotes the set of common valid years, and the overbars denote means calculated over those years. The four depth aggregates and two temporal windows yielded eight analysis configurations.

For each configuration, the karst–non-karst contrast was summarized as:

$$
\Delta \mathrm{r} = \text { median } (\mathrm{r} _ {\mathrm{K}}) - \text { median } (\mathrm{r} _ {\mathrm{NK}})
$$

Here, rₖ and rₙₖ denote pixel-wise correlation coefficients in karst and non-karst areas, respectively. Positive Δr indicates a higher median correlation coefficient in karst areas. Comparisons were subsequently conducted within combinations of aridity classes and vegetation types. This stratification facilitated comparisons within broad environmental categories but did not fully control for terrain, soil conditions, or drought exposure.

An event-level composite analysis was also conducted to examine vegetation responses around drought onset. This event-centred perspective reflects the emphasis on rapid drought development in the flash-drought literature (Otkin et al., 2018). The analysis used 8-day intervals, distinct from the annual and seasonal aggregation windows described above. Soil moisture from the ERA5-Land hourly dataset (Munoz ˜ Sabater, 2019) was sampled every six hours. The first three native layers were combined using the L123 thickness weights, and the resulting values were averaged over the corresponding 8-day intervals to match GPP and ESI.

For each year, the primary flash-drought event was selected as the event with the greatest product of duration and average impacted area. For each selected event, 17 consecutive 8-day periods were extracted over the window $[ \mathrm { t } - 4 , \mathrm { t } + 1 2 ]$ , where t denotes the 8-day period containing drought onset. This window included four periods before onset, the onset period, and twelve subsequent periods. These event-selection and window settings were adopted for the present analysis

Pixel-level SM and WUE values were standardized into z-scores using their respective study-period means and standard deviations (Wilks, 2019):

$$
\mathbf {z} _ {\mathrm{X,i,t}} = \frac {\mathbf {X} _ {\mathrm{i,t}} - \mu_ {\mathrm{X,i}}}{\sigma_ {\mathrm{X,i}}}
$$

here, X denotes SM or WUE, i denotes the pixel, and t denotes the time step. The parameters μX,i and σX,i are the study-period mean and standard deviation of the corresponding variable at pixel i. The selected events were then combined to construct composite response trajectories, expressed as means with 95% confidence intervals.

Finally, paired t-tests were applied to contrast the event-minimum z-scores of SM and WUE between the two groups. The ratio of the absolute standardized changes in WUE and SM was calculated to summarize their relative response amplitudes:

$$
\mathbf {A} = \frac {| \Delta \mathbf {z} _ {\mathrm{WUE}} |}{| \Delta \mathbf {z} _ {\mathrm{SM}} |}
$$

here, A denotes the response-amplitude ratio, and Δz\_WUE and Δz\_SM denote the standardized response changes for the corresponding variables. This ratio was interpreted as a descriptive comparison between indicator responses rather than a direct measurement of physiological stress-transmission efficiency or subsurface hydrological buffering.

(a) Calendar of 17 Annual Main Flash Drought Events  
![](images/09df5b4f5311e8198c57f0f2dd014197e90cd40809967f327ed691eb7fdecb7a.jpg)

(b) Annual-minimum FSI percentile trend Blue: positive; red: negative slope  
![](images/760ee1b97a9d9de49eab7f523342bbb0793d602b12edc8cddffad352132d3840.jpg)

(c) Karst vs Non-Karst  
![](images/90b5b29133807b0d3dfb930db3c0616ac2b41f834f2237c85af8df3d863e712f.jpg)

(d) Aridity Classes  
![](images/f04c7823538e8119cbdb248b0a80e29dcfc16dcb43fe7766cc5ee7ebe6ce5d04.jpg)  
Fig. 2. Spatiotemporal patterns of flash droughts. (a) Timing of 17 principal events; rectangle width indicates duration, and color and labels indicate severity. (b) Sen’s slopes of pixel-wise annual minimum Evaporative Stress Index (ESI) percentiles; red and blue indicate negative and positive slopes, respectively. (c, d) Annual flash drought frequency by geomorphology and aridity class, respectively. Annotated slopes and p-values refer to the Theil Sen estimator and Mann Kendall test.

## 3. Results and analysis

## 3.1. Interannual trends of flash droughts and compounding vulnerabilities

Following the criteria proposed by Otkin et al. (2018), 17 principal regional flash drought events were identified over the 2000–2024 period. These events were predominantly concentrated in the summer months (June–August), with occasional extensions into late spring and early autumn. The most severe event occurred in the spring of 2011, followed by notable events in 2001 and 2004 (Fig. 2a).The spatial distribution of Sen’s slopes for the pixel-wise annual minimum ESI percentiles exhibits high heterogeneity (Fig. 2b). While the impacts of flash droughts tended to mitigate along the eastern margin of the Qinghai-Tibet Plateau and in southeastern Tibet, they intensified significantly across the southwestern Yunnan-Guizhou Plateau, the mountainous terrains of southwestern Yunnan, and the central highlands of the Indochina Peninsula. Negative Sen’s slopes indicate declining annual minimum ESI percentiles, whereas positive slopes indicate increasing annual minimum ESI percentiles. These trends describe changes in the drought indicator rather than changes in GPP-based vegetation resistance (Fig. 2b). Notably, the region spanning the southwestern Yunnan-Guizhou Plateau to southwestern Yunnan—characterized by a complex intertwining of Karst geology, monsoon margins, and steep topography—spatially coincides to a high degree with the threshold-vulnerable subgroups. Consequently, this intersection forms a critical zone of compounding flash drought risks. Annual flash drought frequency exhibited different temporal patterns between karst and non-karst areas during 2000–2024. The karst group showed a decreasing trend (Theil–Sen slope = −0.00361 per year, Mann–Kendall ${ \bf p } = 0 . 0 1 4 )$ , whereas the non-karst group showed no significant trend (slope = +0.00049 per year, $\begin{array} { r } { \mathbf { p } = 0 . 7 6 1 ; \mathrm { F i g } . } \end{array}$ . 2c). None of the five aridity classes exhibited a significant trend at the 0.05 level. The hyper-arid group showed a positive slope of + 0.00534 per year, but this trend was not statistically significant $\left( \mathbf { p } = 0 . 0 9 7 ; \mathrm { F i g . ~ 2 d } \right)$ . The regional mean annual flash drought frequency was approximately 0.0746 events pixel⁻¹ yr⁻¹, with substantial interannual variability. The highest value occurred in 2023 (0.1488), and the lowest in 2017 (0.0085). The regional frequency series showed no significant monotonic trend over the study period (Theil–Sen slope = +0.000054 per year, $\mathbf { p } = 0 . 9 8 1 )$

## 3.2. Multidimensional differentiation of ecological resilience under flash droughts

Leveraging a robust sample of 49,065 valid pixels across the study domain (comprising 13,759 Karst and 35,306 non-Karst pixels), this section systematically contrasts resistance, resilience, and recovery efficiency across three fundamental dimensions: geo morphology, vegetation functional type, and aridity gradient. Furthermore, a rigorous three-way cross-stratification framework (geomorphology × aridity class × vegetation type) is deployed to spatially delineate critical zones of compounding vulnerability.These three complementary metrics respectively characterize the ecosystem's capacity to sustain physiological functionality during the active flash drought disturbance, the absolute magnitude of functional rebound following the cessation of stress, and the overarching efficiency of the entire recovery process. Under the original grouping, mean GPP-based resistance was 0.945 in karst areas and 0.932 in non-karst areas (Fig. 3a), with a difference of approximately 0.0122 calculated from the unrounded means. A separate geographicall aligned comparison yielded a smaller mean difference of approximately 0.0064. For this aligned comparison, spatial block bootstrap analyses yielded 95% confidence intervals of [0.00287, 0.00988] and [0.00081, 0.01177] under the unshifted 20-km and 40-km block configurations, respectively. Intervals obtained with larger blocks included zero. The direction of the mean contrast was therefore consistent between the two grouping approaches, whereas its magnitude and statistical support were sensitive to spatial grouping and block size. Conversely, resilience in Karst environments is merely 0.036, drastically trailing the 0.062 observed in their non-Karst counterparts—a staggering relative decline of 41.9% $\left( p < 0 . 0 0 1 \right)$ ). Mean next-year relative productivity was approximately 0.981 in karst areas and 0.995 in non-karst areas (Fig. 3c).Mechanistically, these results indicate that while Karst ecosystems exhibit a marginally superior capacity to maintain physiological functions during the active stress phase, their post-stress functional rebound is profoundly hampered. This dynamic ultimately manifests as a quintessential "high-resistance/low-recovery" structural paradigm across the region (Fig. 3).

![](images/fc158ef273e874e08bd0b1ab9c9644de8832b003dd9e844451e26b5a32566b6b.jpg)

(b) Resilience  
![](images/73ecc605f294e2b66610288746e0078f66718813180c134cc358aa30f27c7bb4.jpg)

(c) Recovery Efficiency  
![](images/7d0894ab9e8e8126f4c5dee607e4c741f9c9ec155de9555a18ba3d0292b2f6e7.jpg)  
Fig. 3. Geomorphological disparities in flash drought resilience across the Asian Karst Concentration. Comparisons are shown for (a) resistance, (b) resilience, and (c) recovery efficiency between Karst and non-Karst ecosystems. Within the box-and-whisker plots, the boxes span the interquartile range (IQR), the solid horizontal black lines indicate the medians, and the red diamonds denote the mean values. The whiskers extend to 1.5 times the IQR. Statistical significance (p-values) was determined using the two-sided Mann–Whitney U test. The figure presents results under the original grouping; the geographically aligned comparison and its spatial block bootstrap confidence intervals are reported separately in the text.

Across vegetation functional types, evergreen forests exhibited the highest resistance (0.955) alongside the lowest resilience (0.037). In stark contrast, croplands displayed the exact inverse pattern, registering the lowest resistance (0.905) but the highest resilience (0.096). Deciduous forests occupied an intermediate functional niche, with a resistance of 0.916 and a resilience of 0.077. Consequently, resistance and resilience manifest a strictly inverse rank-order across these distinct vegetation functional groups. Furthermore, when evaluated along the aridity gradient, resistance increased monotonically toward drier regimes, whereas resilience exhibited a corresponding monotonic decline. Thus, these two functional dimensions diverge in completely opposite directions along the climatic continuum (Fig. 4). Synthesizing the evidence from these three isolated dimensions—geomorphology, vegetation functional type, and aridity gradient—it becomes unequivocally clear that a fundamental "high-resistance/low-recovery" tradeoff universally governs the ecological responses of this region to flash drought stress.

To compare karst and non-karst responses within broad environmental categories, the three response metrics were compared within combinations of aridity classes and vegetation types (Fig. 5). Differences were calculated as the karst mean minus the non-karst mean within each combination. This stratification improved comparability with respect to the selected categories but did not fully account for differences in terrain, soil conditions, drought exposure, or management. The direction and magnitude of the observed contrasts varied among combinations. For example, resistance was slightly lower in karst croplands under humid conditions, with a mean difference of −0.020. Within hyper-arid areas, evergreen forests showed slightly lower resistance and greater next-year productivity rebound in karst areas, whereas grasslands showed higher resistance and smaller rebound. Differences in next-year relative productivity were slightly positive for both available vegetation categories. Combinations with insufficient samples were excluded. These findings indicate that the regional mean contrast does not apply uniformly across aridity–vegetation settings.

(a) Resistance  
![](images/bf7e11670fea133ed132b62818c7944f1cc6e2b8fe5f808f5c9ea7362f7c4e58.jpg)

(b) Resilience  
![](images/1fcc16c1dd03ae9760a848bf3261013d5135993e924c8b30884700c021a341b7.jpg)

(c) Recovery Efficiency  
![](images/eba5e43a0ff7940eb9262b6e969a1f8c811379cfee8fa64db4b2927cbf4e4e23.jpg)

![](images/5127e52e2bc0b270e19299b2821416163cd50e980d880724a764b7552e7678ba.jpg)

![](images/8dede62846c7d2dab63ea2a22602677e7c191b2c04fe6857132d4d26a87dda0c.jpg)

(f) Recovery Efficiency  
![](images/bf3c794b1efd617342fe2283943a92a11bdbdd685540d46056dc62a3098b29ee.jpg)  
Fig. 4. GPP-based response metrics by vegetation type (a c) and aridity class (d f). Columns show resistance, next-year productivity rebound, and next-year relative productivity, respectively. Boxes show the interquartile range, horizontal lines the median, and red diamonds the mean; whiskers follow the 1.5 × IQR rule. Labels above the boxes give group means.

![](images/3a8c515d72fa8a108f11fce725b62309124a9828d88b11e767c9a3316b374bce.jpg)

![](images/c37007216481d0c69d024f79d4b210fab10d3261684d31e4d2b3604372cc4b73.jpg)

![](images/df69ce23971e32104b96309291f5b020f125d61bfa259801bde30b55f7dd378b.jpg)  
Fig. 5. Differences in group means (karst minus non-karst) within aridity–vegetation combinations: (a) resistance, (b) next-year productivity rebound, and (c) next-year relative productivity. Cell labels give the differences; red and blue indicate positive and negative values, respectively. NA denotes combinations excluded by the minimum sample-size criterion (<5 valid pixels).

## 3.3. Non-linear threshold detection of vegetation resistance in response to flash drought severity

Continuous piecewise linear regression was used to characterize the relationship between mean event-level cumulative drought severity and GPP-based resistance within each subgroup. The estimated breakpoint T indicates a change in the slope of the fitted relationship (Fig. 6). For the karst cohort $( \mathbf { n } = 1 1 , 8 0 1 )$ , the estimated breakpoint was T = 52.8, with the fitted slope changing from + 0.001156 below the breakpoint to −0.001147 above $\mathbf { i t } ,$ corresponding to a slope change of −0.002303. For the non-karst cohort $\mathbf { ( n = 3 3 , 2 2 3 ) }$ , the estimated breakpoint was $\mathrm { T } = 1 0 5 . 2 ;$ the fitted slope remained negative but became less steep, changing from −0.001179 to −0.000607. Thus, the karst group had a lower estimated breakpoint, while the two groups exhibited different forms of change in their resistance–severity relationships. Estimated breakpoints also varied among vegetation types and aridity classes (Fig. 6b). Among vegetation types, grasslands had the lowest estimate (T = 54.3), followed by evergreen forests (T = 109.7), croplands (T = 112.7), and deciduous forests (T = 129.7). Among aridity classes, the estimates were 71.4 for hyper-arid, 95.0 for humid, 104.8 for arid, 115.4 for semi-arid, and 121.3 for sub-humid areas. The direction of slope change differed among groups: the humid group changed from a negative to a positive fitted slope, whereas several other groups showed a less steep negative slope above their breakpoints. Model $\mathrm { R } ^ { 2 }$ values ranged from 0.024 to 0.099 (Fig. 6c), indicating that the fitted relationships explained a limited proportion of the variation in pixel-level resistance. These findings describe variation in the fitted resistance–severity relationships across landscape categories. The estimated breakpoints should therefore be interpreted as statistical changes in these relationships rather than directly observed physiological collapse thresholds.

## 3.4. Coupling mechanisms between water use efficiency and soil moisture

Water Use Efficiency (WUE), formulated as the ratio of Gross Primary Productivity to Evapotranspiration, characterizes the coupling efficiency between vegetation carbon assimilation and water consumption, with Soil Moisture (SM) acting as its fundamenta supply-side constraint. This section delineates the spatiotemporal dynamics of WUE and SM, and systematically contrasts their coupling mechanisms between Karst and non-Karst regions.

The multi-year regional mean WUE across the study domain was $2 . 2 7 \pm 0 . 3 0 ~ \mathrm { g C \cdot k g ^ { - 1 } H _ { 2 } O } ~ ( n = 6 3 , 5 0 2 )$ . Over the 25-year study period, WUE exhibited a robust ascending trend: 39.8% of pixels showed significant increases, whereas only 3.8% experienced significant declines. The regional Sen's slope reached +0.0061 $\mathbf { g } \mathbf { C } \cdot \mathbf { k } \mathbf { g } ^ { - 1 } \cdot \mathbf { y } \mathbf { r } ^ { - 1 } ~ ( p < 1 0 ^ { - 7 } , R ^ { 2 } = 0 . 7 3 )$ , culminating in a cumulative regional enhancement of approximately 6.5%. While the difference in annual regional means between Karst and non-Karst cohorts was statistically non-significant $( p = 0 . 4 3 0 )$ , pixel-level Mann-Whitney U tests unveiled that the Karst mean (2.296) was significantly higher than the non-Karst mean (2.262, $p < 1 0 ^ { - 1 5 } )$ . Furthermore, the coefficient of variation (CV) in Karst areas (3.5%) was roughl 30% greater than that in non-Karst areas (2.7%), underscoring a heightened degree of spatial heterogeneity.

Concurrently, growing-season SM demonstrated a pervasive declining trend, with 23.4% of the pixels experiencing significant reductions and yielding a cumulative depletion of 5.9%. This progressive soil desiccation structurally mirrors the concurrent enhancement in WUE, signifying an inverse macroscopic trajectory.

Crucially, pixel-wise temporal correlation analysis between SM and WUE revealed a markedly tighter coupling within Karst ecosystems (Fig. 7). Under the baseline scenario—utilizing main root-zone SM (L123) during the growing season—the median correlation coefficient (r) in Karst areas was + 0.068, substantially eclipsing the +0.018 observed in non-Karst areas $( \Delta r = \mathbf { \nabla } + 0 . 0 4 9$ $p < 1 0 ^ { - 2 0 } )$ . This amplified Karst coupling proved exceptionally robust, remaining consistently stable across eight distinct analytica configurations encompassing four soil depths and two temporal windows (with Δr ranging from +0.043 to + 0.059).

Stratification by aridity class corroborated that the median r values for all five Karst subgroups consistently surpassed their non-Karst counterparts, yielding strictly positive Δr values spanning from +0.012 to +0.115 (Fig. 7a, b). Intriguingly, the coupling

![](images/c0064fe9322b5c39c327f565e87b144aa25c1f5b6d1822fdbc7fe3777a9b49b4.jpg)

## (a) Piecewise resistance-severity relationships across groups

![](images/c50a8d24b90711f3529035300be9ca6a7fa37dd5b340a982200c7f24a72317b7.jpg)

![](images/06181491aba4207ea26db9c7eba28b4c419f24d9b55996dd3acc897b8b932823.jpg)

(b) Estimated breakpoints across groups  
![](images/f6ab219b5594dc7a936fd5f62ccae13b0271d996a6f16308848ee16d434d7ffe.jpg)

(c) Model goodness of fit across groups  
![](images/5fb364cd3fdf15304bc7d2c1e5a4ebdc1a73b9276868e1b7b06781cbe01b5ec9.jpg)  
Fig. 6. Piecewise linear relationships between flash-drought severity and resistance. (a) Fits by geomorphology, vegetation type, and aridity class; black lines show fitted relationships and red dashed lines mark estimated breakpoints. (b) Breakpoint estimates by subgroup. (c) Model goodness of fit (R²). Breakpoints are statistical descriptors of the fitted relationships.

![](images/e1b1670983ae998a37d06668a372c81856ee948ed628f2c2ae5d996766f13bbc.jpg)

(b) Differences in median correlations (karst minus non-karst)  
![](images/b97602fe52123bd016fb9ce8eff266fe137c91ee966162f890f0c0e5b1ec76a2.jpg)

(c) Karst: median correlations by aridity and vegetation type  
![](images/b86104bd874baa2c7578ff3469ebfba2fb58adc79a875eea534b2901dd69c2bd.jpg)

(d) Non-Karst: median correlations by aridity and vegetation type  
![](images/1e9ed8f23806b065112a5b792ff19da637865fc5b67b178a1c2dd083156e11bc.jpg)  
Fig. 7. Soil moisture (SM)–water-use efficiency (WUE) correlations for the 0–100 cm aggregate (L123), using March–October averages (GS). (a) Median pixel-wise Pearson r for karst (red) and non-karst (blue) areas by aridity class; background shading indicates hypothesized energy- and water-limited regimes. (b) Differences in median r (karst minus non-karst). (c, d) Median r by aridity–vegetation combination in karst and non-karst areas, respectively. Heatmap colors indicate correlation sign and magnitude; n/a denotes unavailable estimates.

coefficient itself exhibited a monotonic transition from negative to positive along the humid-to-arid gradient, perfectly reflecting Budyko's dichotomy: negative correlations in energy-limited humid zones and positive correlations in water-limited arid zones.

Furthermore, a two-dimensional cross-stratification framework (aridity class × vegetation type) demonstrated that the intensified coupling in Karst regions prevailed across the vast majority of climate–vegetation combinations $( \mathrm { F i g . } 7 \mathbf { c } , \mathbf { d } )$ . This conclusively proves that the amplified SM WUE coupling is an intrinsic hydrological attribute of the Karst critical zone, rather than an artifact driven by specific vegetation types or climatic sub-regions.

An event-level composite analysis of the 17 principal flash drought events spanning the 2000 2024 period (Fig. 8) further elu cidates this asymmetric stress transmission. During these extreme events, the median minimum z-score for SM in Karst ecosystems was − 1.12, representing a significantly less severe soil moisture deficit compared to the −1.26 observed in non-Karst regions (paired t-test, p = 0.004). Paradoxically, the median minimum z-score for WUE in Karst areas plunged to − 1.15, indicating a significantly more profound physiological deficit than the −0.83 recorded in their non-Karst counterparts $( p = 0 . 0 1 1 )$ . Consequently, in 13 out of the 17 events (76%), the Karst response trajectories fell conspicuously below the 1:1 isometric line.

The event-minimum comparisons showed contrasting standardized responses of SM and WUE: karst areas had less negative SM minima but more negative WUE minima than non-karst areas. These results indicate that the two indicators differed in their responses between landscape groups. Because SM and WUE were standardized separately, their anomaly magnitudes do not quantify the fraction of water stress buffered or transmitted. The event composites therefore provide comparative evidence of indicator responses rather than a direct measurement of subsurface hydrological buffering.

## 4. Discussion

## 4.1. Differentiation of ecological resilience under flash droughts in the Karst concentration area

Within the conceptual framework of ecological resilience, resistance (the maintenance of functionality during stress) and recovery (the subsequent rebound in functionality) represent distinct but interrelated components of ecosystem responses to disturbance (Hodgson et al., 2015; Ingrisch and Bahn, 2018). The isolated quantification of these components is a prerequisite for deciphering ecosystem responses to drought. This study reveals a profound asymmetric amplification effect during the transmission of water stress to vegetation physiology within Karst ecosystems. Our event-level composite analysis demonstrates that across the 17 flash drought events, the degradation of soil moisture (SM) in Karst regions was paradoxically less severe than in non-Karst regions (z = −1.12 vs. − 1.26, paired t-test p = 0.004). Conversely, the deterioration of vegetation water use efficiency (WUE) was significantly more profound $( z = - 1 . 1 5 \ \mathrm { v s . } \ \mathrm { ~ - ~ } 0 . 8 3 , p \ = 0 . 0 1 1 )$ , a pattern corroborated by 76% of the analyzed events.

(a) Composite SM and WUE response across 17 flash drought events (2000—2024) Solid: Karst | Dashed: Non-Karst | Shaded: 95% Cl  
![](images/f7752586e03ce6d54fe454634caf7c2fe54bfc6aa0ac856bb7bdf14511d144f0.jpg)

(b) SM and WUE minimum anomalies by karst type SM: K vs NK paired t = 3.41, p = 0.004\*\* | WUE: paired t = -2.89, p = 0.011\*  
![](images/b5725710293e6b94ebcdef7f5c83523cd1dae08167520e7b4d053e9be45b8b61.jpg)

(c) Per-event Karst vs Non-Karst WUE minimum Points below 1:1 line: Karst WUE drops MORE than Non-Karst Median Δ(K-NK) = -0.217, paired t-test p = 0.011  
![](images/a55c08e1a35395ac266a20404f70bffe163d83c4f79e5cc5eaf1431ce0a69ccd.jpg)  
Fig. 8. Event-level composite analysis of ecohydrological responses across the 17 principal flash drought events. (a) Composite temporal trajectories of standardized anomalies (z-scores) for SM (blue) and WUE (green) averaged across all events. The time series are anchored at the onset day of each flash drought event (t = 0). Solid lines represent Karst ecosystems, whereas dashed lines denote non-Karst ecosystems. Shaded envelopes indicate the 95% confidence intervals. (b) Box-and-whisker plots comparing the event-minimum z-scores of SM and WUE, stratified by Karst and non-Kars cohorts. Gray lines interconnect the paired values for each specific event, with p-values derived from paired t-tests explicitly annotated at the top. (c) A 1:1 isometric scatter plot contrasting the event-specific minimum WUE z-scores between Karst and non-Karst regions.

Consequently, the derived stress transmission amplification factor reached approximately 1.03 in Karst areas, contrasting sharply with merely 0.66 in non-Karst regimes. This quantitatively indicates that while non-Karst hydrological systems can absorb approximately one-third of the water stress shock, Karst environments transmit this stress to the functional level of vegetation at a near 1:1 ratio. This quantifiable outcome provides direct mechanistic evidence for the "high-resistance/low-recovery" tradeoff. During the active stress phase, the relatively milder drop in SM restricts immediate functional degradation, manifesting as high resistance; however, during the recovery phase, the already severely impaired WUE prolongs functional disruption, culminating in sluggish recovery. Drought legacy effects have also been documented in forest ecosystems, with reduced tree growth and incomplete recovery persisting for 1–4 years after severe drought (Anderegg et al., 2015).

The diametric imbalance between these two phases fundamentally constitutes the hydrological root of this ecological tradeoff.

These findings establish a highly meaningful dialogue with existing literature. The hydrological vulnerability induced by thin Karst soils, rapid epikarst leakage, and limited water retention capacity has been extensively documented (Hartmann et al., 2014; Jiang et al., 2014). However, current land surface models (such as HTESSEL, utilized in ERA5-Land) generally fail to adequately parameterize the characteristic dual-porosity media and preferential flow processes inherent to Karst systems. The event-level evidence presented in this study demonstrates that this structural hydrological buffering weakness is not merely conceptual; rather, it manifests quantifiably as an amplified stress transmission to vegetation functionality. This provides robust quantitative substantiation, at the regional observational scale, for the deficit in Karst water buffering capacity.

The relatively higher mean resistance observed in karst areas is not necessarily inconsistent with the vulnerability commonly associated with karst environments. Resistance here measures productivity maintenance during the identified drought period relative to the corresponding climatological baseline. Recent flux-tower observations demonstrate that drought resistance and recovery rate differ among ecosystem types and can be negatively related, supporting their separate consideration when evaluating ecosystem resilience (Shao et al., 2024). Thus, comparatively high productivity resistance during drought does not necessarily imply faster subsequent recovery or lower vulnerability across all response dimensions

Hydrological heterogeneity provides a plausible context for interpreting this pattern. Field monitoring in southwestern Chinese karst has shown that water stored in soil-filled rock fractures can help sustain tree transpiration and buffer its seasonal variability, depending on local soil–rock conditions (Liu et al., 2025). Stable-isotope research has also documented species-specific adjustments in water uptake during drought, with contrasting responses between trees and shrubs in restored karst vegetation (Cai et al., 2025). These findings suggest that plant-accessible subsurface water and flexible water-use strategies may help some karst vegetation maintain functioning when near-surface water becomes limited. However, these processes were not directly measured in the present study, and the published evidence does not establish their contribution to the regional resistance contrast. Vegetation composition, terrain, soi conditions, and drought exposure may also influence the observed difference (Chen et al., 2024a; Wang et al., 2025; Xiao et al., 2024).

Ecosystem age may also contribute to variation in drought responses, but its role could not be evaluated because comparable ecosystem-age information was unavailable for the two groups. The present analysis therefore cannot determine whether the sampled karst ecosystems were systematically younger or whether age contributed to their relatively higher resistance. The observed contrast is interpreted as an association with the sampled landscape settings, while the contributions of subsurface water access and ecosystem age require further investigation.

## 4.2. The asymmetric amplification effect and its broad implications

Median SM–WUE correlations shifted from negative values in humid areas toward positive values in drier areas, indicating variation in the direction of the interannual association across the aridity gradient (Fig. 7). Karst areas had higher signed median correlations within each aridity class, but this did not consistently imply larger absolute correlations or a uniform contrast within aridity–vegetation combinations. Heterogeneous recharge, storage, and flow processes in karst systems provide a hydrological context for interpreting landscape-dependent responses (Hartmann et al., 2014). However, stratification improved comparability within broad environmental categories without controlling for all differences in terrain, soil conditions, drought exposure, or management. The observed contrasts should therefore be interpreted as associations with landscape settings rather than an isolated lithological effect. Previous research has documented nonlinear changes in ecosystem attributes along climatic aridity gradients (Berdugo et al., 2020). However, climatic aridity and event-level cumulative drought severity are distinct variables. The breakpoints estimated here consequently describe changes in the fitted resistance–severity relationships and should not be equated with those aridity thresholds or interpreted as universal physiological limits.

The overarching trend of flash droughts further accentuates the urgency of this vulnerability. Over recent decades, flash drought risks have generally escalated both within China and globally (Christian et al., 2021; Yuan et al., 2019, 2023), although specific subtypes, such as heatwave-driven flash droughts, have mitigated in certain regions (Mo and Lettenmaier, 2015). In the 2000–2024 frequency analysis, the hyper-arid group showed a positive but statistically non-significant trend. This result alone does not establish an increase in flash drought frequency in hyper-arid karst landscapes, which would require a separate analysis of that specific aridity–geomorphology combination.

These regional comparisons can inform the assessment of drought sensitivity across different landscape settings. Among the aridity classes, the hyper-arid group had the lowest estimated breakpoint in the resistance–severity relationship (T = 71.4). In a separate comparison by geomorphology, the estimated breakpoint was lower in karst than in non-karst areas. These results suggest that hyperarid karst landscapes warrant further assessment, but the breakpoint for this specific aridity–geomorphology combination was not estimated. Their relative vulnerability and conservation priority therefore require evaluation using evidence specific to this landscape setting. Furthermore, the amplification of water stress sensitivity driven by the tight Karst coupling suggests that upstream and downstream ecological responses to drought within transboundary basins spanning from the Indochina Peninsula to the Yunnan-Guizhou Plateau—may exhibit pronounced asymmetry. Water resource allocation and cross-border ecological compensation mechanisms must critically account for these structural disparities. In vegetation restoration practices, priority should be directed toward deep-rooted, evergreen native tree species to strategically enhance hydrological buffering capacity. This recommendation spatially and temporally aligns with the positive regional WUE enhancements driven by the "Grain for Green" program and rocky desertification control engineering (Tong et al., 2018). Ultimately, given the vast global distribution of carbonate rocks (Goldscheider et al., 2020), the conclusions drawn from this Asian Karst concentration offer profound theoretical and practical reference value for other Karst-dominated landscapes worldwide.

## 4.3. Limitations and future directions

Published field experiments and observational studies indicate that access to subsurface water and adjustments in water-use strategies can influence drought responses in karst vegetation (Cai et al., 2025; Ding et al., 2021; Liu et al., 2025). These findings provide process-based support for considering plant water access when interpreting the patterns observed here. However, this study lacks independent field observations matched to the locations and periods of the regional analysis. SM–WUE associations alone cannot identify plant water sources or quantify subsurface buffering. The proposed hydrological explanation therefore remains a plausible interpretation requiring further validation.

Uncertainty remains in the representation of plant-available water. ERA5-Land provides model-based soil-moisture estimates for prescribed layers (Munoz-Sabater ˜ et al., 2021), which may not adequately represent heterogeneous soil pockets, rock fractures, and root access to stored water in karst terrain. Future evaluations should combine field measurements with satellite products matched to the relevant depths, spatial scales, and observation periods. SMAP/SMOS surface retrievals can help assess near-surface moisture dynamics, but should not be treated as direct validation of deeper soil or fracture water. Data assimilation and downscaling may improve spatial characterization, although their accuracy would still require independent evaluation.

The regional comparisons do not fully account for terrain, soil conditions, drought exposure, or human management. Stratification by aridity and vegetation type facilitates comparisons within broad environmental categories but does not isolate the effect of karst lithology. Recent research on social–ecological resilience in South China Karst also supports considering interactions between social and ecological processes (Li et al., 2025). Future studies should incorporate spatially consistent information on irrigation, land management, and ecological restoration, alongside environmental covariates, to assess their contributions without presuming a uniform difference between southwestern China and the Indochinese Peninsula. Spatial dependence should also be considered when estimating uncertainty in regional contrasts

The geographical transferability and causal interpretation of the observed relationships remain uncertain. Applying the analytica framework to other karst regions, including the Mediterranean, Yucatan ´ Peninsula, and Dinaric Karst, could test whether similar response patterns occur under different climatic, geological, and management conditions. Such comparisons should distinguish associations among indicators from independently verified mechanisms. Following further validation, integration with process-based models and CMIP6 climate projections could help explore future drought-response scenarios while accounting for uncertainty in climate forcing, hydrological representation, and vegetation responses.

## 4.4. The role of socio-economic and cultural factors in regulating ecosystem resilience

Although this study primarily examines biophysical responses to flash drought, the observed patterns should also be considered within a broader social–ecological context. Resource governance, livelihood activities, and ecological processes interact in shaping environmental outcomes (Ostrom, 2009). Recent research in South China Karst has further examined the evolving relationships between social development and ecological resilience, supporting the inclusion of human–environment interactions in regional assessments (Li et al., 2025). Land management, water infrastructure, and restoration practices may therefore contribute to variation in drought responses, although their effects were not quantified in the present study.

Ecological restoration provides an example of how management can alter these interactions. A recent meta-analysis documented improvements in biodiversity and ecosystem services following restoration in South China Karst, while also showing that outcomes depended on environmental and restoration contexts (Chen et al., 2024b). These benefits, however, should not automatically be interpreted as increased drought buffering. Regional research has associated revegetation with reductions in soil moisture and groundwater storage in humid karst areas, despite no corresponding reduction in water yield (Zeng et al., 2025). Together, these findings suggest that the implications of restoration for drought resilience depend on the balance between vegetation recovery, water consumption, and locally available water resources

![](images/56f7291524f4ac7f19197f9e1518b371d876afec56412bf59d1a7ee7ad33c2e5.jpg)  
Fig. 9. Contrasting vegetation responses to flash drought in karst and non-karst landscapes. The lower panels summarize observed differences in GPP resistance, next-year productivity rebound, and seasonal soil moisture–water-use efficiency (SM–WUE) correlations. The upper profiles illus trate potential hydrological explanations that require independent validation.

Cultural practices and local institutions may also influence adaptation through ecological knowledge, collective learning, and community-based resource management (Berkes et al., 2000; Ostrom, 2009). These potential influences warrant consideration across both southwestern China and the Indochinese Peninsula, without assuming that traditional practices or economic development have a uniform effect on drought vulnerability. Because comparable management and cultural information was not incorporated into this analysis, these factors remain contextual hypotheses rather than demonstrated explanations of the observed resistance and recovery contrasts. Integrating spatial management records, socio-economic indicators, and household or community surveys would help evaluate their contributions and inform locally appropriate adaptation strategies.

## 5. Conclusion

This study compared vegetation responses to flash drought in karst and non-karst landscapes of southwestern China and the Indochinese Peninsula, within the Asian Karst Concentration. The available GPP-resistance comparisons indicate a modest positive karst–non-karst contrast, whose magnitude and statistical support depend on spatial grouping and uncertainty settings. The seasona SM–WUE comparison also indicates a higher median pixel-wise correlation in karst areas. These findings describe landscape-associated response differences and do not establish an isolated lithological effect. The fitted resistance–severity relationships describe changes in statistical response patterns, while productivity maintenance and next-year rebound capture related aspects of the productivity trajectory. Neither an estimated breakpoint nor a smaller rebound directly establishes physiological failure or a longer recovery duration. Hydrological constraints provide a possible interpretation of the observed contrasts, but subsurface buffering and causal stress transmission were not directly measured. The findings support evaluating multiple response dimensions when assessing drought vulnerability in the study domain. Their interpretation should account for terrain and soil heterogeneity, shared indicator inputs, and spatial uncertainty. The proposed hydrological interpretation is summarized in Fig. 9 and requires independent observations of water availability and vegetation responses for validation

## CRediT authorship contribution statement

Haoze Ding: Writing – original draft, Visualization, Software, Methodology, Investigation, Formal analysis, Data curation. Qi Guo: Writing – review & editing, Funding acquisition, Formal analysis, Data curation. Yuan Li: Writing – review & editing, Visualization Investigation, Funding acquisition, Formal analysis, Data curation. Zhengshan Chen: Writing – review & editing, Visualization Investigation. Qiuwen Zhou: Writing – review & editing, Visualization, Formal analysis. Shunfu Yang: Visualization, Formal analysis Yuluan Zhao: Writing – review & editing, Validation, Project administration, Funding acquisition, Conceptualization.

## Declaration of Competing Interest

The authors declare that they have no known competing financial interests or personal relationships that could have influenced the work reported in this article.

## Acknowledgements

This research was funded by the Key Project of the Natural Science Foundation of Guizhou Province, China (No. QiankeheJichu-ZK [2023] Zhongdian 027), the Guizhou Provincial Department of Science and Technology Project (No. QiankeheJichu-MS [2026] 420), the National Natural Science Foundation of China (No. 42561007), and the Guizhou Provincial Department of Science and Technology Talent Project (No. QiankeheRencai-XKBF [2025] 033).

## Data availability

Data will be made available on request.

## References

Anderegg, W.R.L., Schwalm, C., Biondi, F., Camarero, J.J., Koch, G., Litvak, M., Ogle, K., Shaw, J.D., Shevliakova, E., Williams, A.P., Wolf, A., Ziaco, E., Pacala, S.W., 2015. Pervasive drought legacies in forest ecosystems and their implications for carbon cycle models. Science 349 (6247), 528–532. https://doi.org/10.1126 science.aab1833.

Beer, C., Ciais, P., Reichstein, M., Baldocchi, D., Law, B.E., Papale, D., 2009. Temporal and among-site variability of inherent water use efficiency at the ecosystem level. Glob. Biogeochem. Cycles 23 (2), GB2018. https://doi.org/10.1029/2008GB003233.

Berdugo, M., Delgado-Baquerizo, M., Soliveres, S., 2020. Global ecosystem thresholds driven by aridity. Science 367 (6479), 787–790. https://doi.org/10.1126 science.aay5958.

Berkes, F., Colding, J., Folke, C., 2000. Rediscovery of traditional ecological knowledge as adaptive management. Ecol. Appl. 10 (5), 1251–1262. https://doi.org 10.1890/1051-0761(2000)010[1251:ROTEKA]2.0.CO;2.

Budyko, M.I., 1974. Climate and Life. Academic Press, New York.

Cai, L., Xiong, K., Li, Y., Liu, Z., Zhu, D., Liang, H., Mu, Y., Chen, Y., 2025. Coexisting plants restored in karst desertification areas cope with drought by changing water uptake patterns and improving water use efficiency. J. Hydrol. 654, 132813. https://doi.org/10.1016/j.jhydrol.2025.132813.

Cai, L., Xiong, K., Liu, Z., Li, Y., Fan, B., 2023. Seasonal variations of plant water use in the karst desertification control. Sci. Total Environ. 885, 163778. https://doi org/10.1016/j.scitotenv.2023.163778.

Chen, S., Stark, S.C., Nobre, A.D., Cuartas, L.A., de Jesus Amore, D., Restrepo-Coupe, N., Smith, M.N., Chitra-Tarak, R., Ko, H., Nelson, B.W., Saleska, S.R., 2024a. Amazon forest biogeography predicts resilience and vulnerability to drought. Nature 631 (8019), 111–117. https://doi.org/10.1038/s41586-024-07568-w.

Chen, Y., Cheng, C., Xiong, K., Rong, L., Zhang, S., 2024b. Quantifying the biodiversity and ecosystem service outcomes of karst ecological restoration: a meta-analysis of South China Karst. CATENA 245, 108278. https://doi.org/10.1016/j.catena.2024.108278.

Chen, Z., Auler, A.S., Bakalowicz, M., Drew, D., Griger, F., Hartmann, J., Jiang, G., Moosdorf, N., Richts, A., Stevanovic, Z., Veni, G., Goldscheider, N., 2017. The World Karst Aquifer Mapping project: concept, mapping procedure and map of Europe. Hydrogeol. J. 25 (3), 771–785. https://doi.org/10.1007/s10040-016- 1519-3.

Christian, J.I., Basara, J.B., Hunt, E.D., 2021. Global distribution, trends, and drivers of flash drought occurrence. Nat. Commun. 12, 6330. https://doi.org/10.1038/ s41467-021-26692-z.

Christian, J.I., Basara, J.B., Otkin, J.A., 2019. A methodology for flash drought identification: application of flash drought frequency across the United States. J. Hydrometeorol. 20 (5), 833–846. https://doi.org/10.1175/JHM-D-18-0198.1.

De Keersmaecker, W., Lhermitte, S., Tits, L., 2015. A model quantifying global vegetation resistance and resilience to short-term climate anomalies. Glob. Ecol. Biogeogr. 24 (5), 539–548. https://doi.org/10.1111/geb.12279.

Ding, Y., Nie, Y., Chen, H., Wang, K., Querejeta, J.I., 2021. Water uptake depth is coordinated with leaf water potential, water-use efficiency and drought vulnerability in karst vegetation. New Phytol. 229 (3), 1339 1353. https://doi.org/10.1111/nph.16971.

Friedl, M., Sulla-Menashe, D., 2022. MODIS/Terra+Aqua Land Cover Type Yearly L3 Global 500m SIN Grid V061. NASA EOSDIS Land Processes Distributed Active Archive Center. https://doi.org/10.5067/MODIS/MCD12Q1.061.

Funk, C., Peterson, P., Landsfeld, M., Pedreros, D., Verdin, J., Shukla, S., Husak, G., Rowland, J., Harrison, L., Hoell, A., Michaelsen, J., 2015. The climate hazards infrared precipitation with stations—a new environmental record for monitoring extremes. Sci. Data 2, 150066. https://doi.org/10.1038/sdata.2015.66.

Goldscheider, N., Chen, Z., Auler, A.S., 2020. Global distribution of carbonate rocks and karst water resources. Hydrogeol. J. 28 (5), 1661–1677. https://doi.org 10.1007/s10040-020-02139-5.

Hartmann, A., Goldscheider, N., Wagener, T., Lange, J., Weiler, M., 2014. Karst water resources in a changing world: review of hydrological modeling approaches. Rev. Geophys. 52 (3), 218–242. https://doi.org/10.1002/2013RG000443.

Hartmann, J., Moosdorf, N., 2012. The new global lithological map database GLiM: a representation of rock properties at the Earth surface. Geochem. Geophys. Geosyst. 13 (12), Q12004. https://doi.org/10.1029/2012GC004370.

Hodgson, D., McDonald, J.L., Hosken, D.J., 2015. What do you mean, 'resilient'? Trends Ecol. Evol. 30 (9), 503–506. https://doi.org/10.1016/j.tree.2015.06.010

Holling, C.S., 1973. Resilience and stability of ecological systems. Annu. Rev. Ecol. Syst. 4, 1–23. https://doi.org/10.1146/annurev.es.04.110173.000245.

Ingrisch, J., Bahn, M., 2018. Towards a comparable quantification of resilience. Trends Ecol. Evol. 33 (4), 251–259. https://doi.org/10.1016/j.tree.2018.01.013.

Jiang, Z., Lian, Y., Qin, X., 2014. Rocky desertification in Southwest China: impacts, causes, and restoration. Earth-Sci. Rev. 132, 1–12. https://doi.org/10.1016/j. earscirev.2014.01.005.

Keenan, T.F., Hollinger, D.Y., Bohrer, G., 2013. Increase in forest water-use efficiency as atmospheric carbon dioxide concentrations rise. Nature 499 (7458), 324–327. https://doi.org/10.1038/nature12291.

Kendall, M.G., 1975. Rank Correlation Methods. Griffin, London.

Kong, Z., Ling, H., Deng, M., Long, A., Guo, B., Huang, S., Zhang, G., 2026. Intensifying drought risk weakens vegetation resilience in global drylands. Commun. Earth Environ. 7, 279. https://doi.org/10.1038/s43247-026-03303-7.

Li, X., Xiao, J., 2019. Mapping photosynthesis solely from solar-induced chlorophyll fluorescence: a global, fine-resolution dataset of gross primary production derived from OCO-2. Remote Sens. 11 (21), 2563. https://doi.org/10.3390/rs11212563.

Li, Y., Peng, L., Li, S., Yue, Y., Wang, K., 2025. Integrating transfer entropy and network analysis to explore social-ecological resilience evolution: a case study in South China Karst. J. Clean. Prod. 518, 145926. https://doi.org/10.1016/j.jclepro.2025.145926.

Liu, Y., Lian, J., Nie, Y., Wang, K., Chen, H., 2025. The role of root-zone soil moisture in delaying vegetation responses to drought: comparative insights from karst and non-karst areas. J. Hydrol. 663, 134216. https://doi.org/10.1016/j.jhydrol.2025.134216.

Mann, H.B., 1945. Nonparametric tests against trend. Econometrica 13 (3), 245–259. https://doi.org/10.2307/1907187.

Mo, K.C., Lettenmaier, D.P., 2015. Heat wave flash droughts in decline. Geophys. Res. Lett. 42 (8), 2823–2829. https://doi.org/10.1002/2015GL064018

Mu, Q., Zhao, M., Running, S.W., 2011. Improvements to a MODIS global terrestrial evapotranspiration algorithm. Remote Sens. Environ. 115 (8), 1781 1800. https://doi.org/10.1016/j.rse.2011.02.019.

Munoz ˜ Sabater, J., 2019. ERA5-Land Monthly Averaged Data from 1950 to Present. Copernicus Climate Change Service (C3S) Climate Data Store (CDS). https://doi. org/10.24381/cds.68d2bb30.

Munoz-Sabater, ˜ J., Dutra, E., Agustí-Panareda, A., 2021. ERA5-land: a state-of-the-art global reanalysis dataset for land applications. Earth Syst. Sci. Data 13 (9), 4349–4383. https://doi.org/10.5194/essd-13-4349-2021.

Nelson, J.A., Carvalhais, N., Cuntz, M., 2018. Coupling water and carbon fluxes to constrain estimates of transpiration: the TEA algorithm. J. Geophys. Res. Biogeosci. 123 (12), 3617–3632. https://doi.org/10.1029/2018JG004727.

Ostrom, E., 2009. A general framework for analyzing sustainability of social-ecological systems. Science 325 (5939), 419–422. https://doi.org/10.1126/ science.1172133.

Otkin, J.A., Svoboda, M., Hunt, E.D., 2018. Flash droughts: a review and assessment of the challenges imposed by rapid-onset droughts in the United States. Bull. Am. Meteorol. Soc. 99 (5), 911–919. https://doi.org/10.1175/BAMS-D-17-0149.1.

Running, S., Mu, Q., Zhao, M., Moreno, A., 2021. MODIS/Terra Net Evapotranspiration Gap-Filled 8-Day L4 Global 500m SIN Grid V061. NASA EOSDIS Land Processes Distributed Active Archive Center. https://doi.org/10.5067/MODIS/MOD16A2GF.061.

Sen, P.K., 1968. Estimates of the regression coefficient based on Kendall's tau. J. Am. Stat. Assoc. 63 (324), 1379–1389. https://doi.org/10.1080 01621459.1968.10480934.

Shao, X., Zhang, Y., Ma, N., Zhang, X., Tian, J., Xu, Z., Liu, C., 2024. Drought-induced ecosystem resistance and recovery observed at 118 flux tower stations across the globe. Agric. For. Meteorol. 356, 110170. https://doi.org/10.1016/j.agrformet.2024.110170.

Sreeparvathy, V., Debdut, S., Mishra, A., 2025. A review of advances in flash drought research: challenges and future directions. Earth's Future 13 (8), e2025EF006603. https://doi.org/10.1029/2025EF006603.

Stocker, B.D., Zscheischler, J., Keenan, T.F., 2018. Quantifying soil moisture impacts on light use efficiency across biomes. New Phytol. 218 (4), 1430–1449. https:// doi.org/10.1111/nph.15123.

Tong, X., Brandt, M., Yue, Y., 2018. Increased vegetation growth and carbon stock in China karst via ecological engineering. Nat. Sustain. 1 (1), 44–50. https://doi. org/10.1038/s41893-017-0004-x.

Wang, J., Wang, B., Wang, D., Dong, Y., Li, J., Lu, F., Tao, W., Guo, Y., Xiang, W., Wen, M., Li, X., 2025. Trade-off strategies between drought resistance and growth rate of dominant tree species in karst forests within heterogeneous habitats. Sci. Rep. 15, 26381. https://doi.org/10.1038/s41598-025-97550-x.

Wilks, D.S., 2019. Statistical Methods in the Atmospheric Sciences. Elsevier. https://doi.org/10.1016/C2017-0-03921-6

Xiao, L., Wu, X., Zhao, S., Zhou, J., 2024. Memory effects of vegetation after extreme weather events under various geological conditions in a typical karst watershed in southwestern China. Agric. For. Meteorol. 345, 109840. https://doi.org/10.1016/j.agrformet.2023.109840.

Yang, S., Zhao, Y., Yang, D., Lan, A., 2024. Analysis of vegetation NDVI changes and driving factors in the karst concentration distribution area of Asia. Forests 15 (3), 398. https://doi.org/10.3390/f15030398.

Yao, Y., Liu, Y., Song, J., Tao, S., Li, Y., Wu, T., Wang, Y., Wang, S., Fu, B., 2024. Declining tradeoff between resistance and resilience of ecosystems to drought. Earth's Future 12 (5), e2024EF004665. https://doi.org/10.1029/2024EF004665.

Yevjevich, V., 1967. An Objective Approach to Definitions and Investigations of Continental Hydrologic Droughts. Colorado State University, Fort Collins, CO

Yuan, X., Wang, L., Wu, P., 2019. Anthropogenic shift towards higher risk of flash drought over China. Nat. Commun. 10, 4661. https://doi.org/10.1038/s41467-019- 12692-7.

Yuan, X., Wang, Y., Ji, P., 2023. A global transition to flash droughts under climate change. Science 380 (6641), 187 191. https://doi.org/10.1126/science.abn6301

Zeng, S., Jiang, Y., Liu, Z., Pu, J., Nerantzis, K., He, Q., Wu, Z., Tian, X., 2025. Revegetation reduces soil moisture and groundwater but not water yield in humid kars areas. Water Resour. Res. 61 (9), e2024WR038758. https://doi.org/10.1029/2024WR038758.

Zhang, M., Yuan, X., 2020. Rapid reduction in ecosystem productivity caused by flash droughts based on decade-long FLUXNET observations. Hydrol. Earth Syst. Sci. 24, 5579–5593. https://doi.org/10.5194/hess-24-5579-2020.

Zhang, M., Yuan, X., Zeng, Z., Pan, M., Wu, P., Xiao, J., Keenan, T.F., 2025. A pronounced decline in northern vegetation resistance to flash droughts from 2001 to 2022. Nat. Commun. 16, 2984. https://doi.org/10.1038/s41467-025-58253-z.

Zheng, X., Li, Y., Zhou, Q., Zhao, Y., Cai, L., Shi, C., Chen, Y., 2026. Rock fissure water dominates the water utilization strategies of woody plants in karst epikarst. J. Hydrol. 674, 135570. https://doi.org/10.1016/j.jhydrol.2026.135570.

Zomer, R.J., Xu, J., Trabucco, A., 2022. Version 3 of the global aridity index and potential evapotranspiration database. Sci. Data 9, 409. https://doi.org/10.1038/ s41597-022-01493-1.