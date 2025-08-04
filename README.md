# Radar vegetation Index Anlaysis using Sentinel-1
# Products used: 
Sentinel-1 Synthetic Aperature Radar (SAR) Satelite Imagery, Vegetation Index (RVI)

# Background
Radar Vegetation Index (RVI) is a powerful tool for monitoring vegetation structure and crop health using radar satellite data. 
Unlike optical vegetation indices, RVI relies on radar backscatter—particularly from cross-polarized signals—which is sensitive to the density and orientation of plant material such as leaves and stems. 
This makes RVI especially useful in detecting changes in vegetation cover, such as defoliation, over time.

In tropical island nations, agriculture is central to food security and livelihoods. 
However, persistent cloud cover, particularly during the wet season, often limits the effectiveness of optical satellites (e.g. Sentinel-2 or Landsat) in capturing key stages of the crop growth cycle. 
This leads to gaps in monitoring data, especially during critical points in the growing season when detecting stress or decline is most important.

The Sentinel-1 radar satellite, which uses Synthetic Aperture Radar (SAR), can collect data regardless of cloud cover or lighting conditions. 
This capability makes it ideal for monitoring crop phenology and health trends throughout the year, even during cyclone season or overcast periods. 
By analyzing multi-temporal Sentinel-1 data, we can compute the Radar Vegetation Index to detect patterns of vegetation growth, senescence, and potential defoliation events in near real-time.

# Description
This study explores how RVI, derived from Sentinel-1 data, can be applied to monitor agricultural vegetation dynamics and detect changes in plant life in Vanuatu. 
Through time series analysis, we aim to detect signs of vegetation stress or loss, which may be linked to climatic events, pests, or land-use pressures—providing a more reliable method of crop surveillance in environments where optical sensors fall short.

The outputs of this study can be used to assess spatio-temporal differences in the growing seasons of agriculture vegetation.

# Radar Vegetation Index Formular
<img width="406" alt="RVI" src="https://github.com/user-attachments/assets/cd565ac7-49ca-4a87-ad05-fa77c3b194d5" />


The Radar Vegetation Index (RVI) is calculated using backscatter data from Sentinel-1 Synthetic Aperture Radar (SAR) and is designed to estimate vegetation structure and density. 

The formula is expressed as RVI = (4σ⁰₍VH₎) / (σ⁰₍VV₎ + σ⁰₍VH₎), where σ⁰ represents the radar backscatter coefficient. σ⁰₍VH₎ is the cross-polarized backscatter (vertical transmit, horizontal receive), which is highly sensitive to vegetation volume, such as leaves and branches, while σ⁰₍VV₎ is the co-polarized backscatter (vertical transmit and receive), which mainly responds to surface features like soil roughness and moisture. 

The numerator multiplies the VH signal by four to enhance the vegetation signal, while the denominator normalizes the result by combining both VH and VV contributions. 

A high RVI value (closer to 1) indicates dense, healthy vegetation, whereas a low value (closer to 0) suggests sparse vegetation, defoliation, or bare soil. 

This makes RVI a reliable tool for monitoring crop health and vegetation changes over time, especially in cloudy or rainy regions where optical data is often unavailable. 

<img width="560" alt="Products" src="https://github.com/user-attachments/assets/65d4e0ac-ab99-4785-b814-385dd9c4ef96" />


[Radar vegetation phenology using Sentinel-](url)](url)
[ https://planetarycomputer.microsoft.com/docs/tutorials/customizable-rtc-sentinel1](url)

# Monthly Phenology

# Annual Variance

# Annual Phenology

# Disaster Impact


