---
title: "Terrestrial fluxes in major Indian agroecosystems: A numerical study using the Community Land Model (CLM5)"
authors:
- admin
author_notes:
date: "2025-08-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent;  9 = Dataset;
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "*Indian Institute of Technology Delhi*(2025)"
publication_short: "IIT Delhi"

abstract: 'Agroecosystems cover nearly 50% of the land in India, with wheat and rice accounting for 
approximately 80% of the farmlands. Several site-scale investigations explored terrestrial carbon,
water, and energy fluxes (terrestrial fluxes – from now in the thesis) within Indian agroecosystems 
(Patel et al., 2011 and 2021; Bhattacharya et al., 2013). However, these do not accurately
reflect the extensive and climatically varied farming environments present in India. Consequently, 
the primary aim of this study is to quantitatively understand the long-term trends
and regional variations in yield, growth parameters, and terrestrial fluxes of Indian agroecosystems. 
Land surface models (LSMs) are valuable tools for such studies because they can be
used to conduct numerical experiments to examine the effects of natural and human drivers
on agroecosystems across regional and global scales. The Community Land Model version 5.0
(CLM5) is a state-of-the-art LSM that has been widely used to study agroecosystems. However, 
the depiction of Indian agroecosystems in CLM5 is not realistic, leading to biases in the
simulation of yield and irrigation compared to observed data (Lombardozzi et al., 2020; Mathur
and AchuthaRao, 2020). The primary challenge in improving the representation of Indian crops
is the scarcity of publicly accessible crop data necessary for model calibration and evaluation
(Gahlot et al., 2020).

This thesis aims to investigate the spatio-temporal variability in crop phenology and
terrestrial fluxes across Indian agroecosystems and the role of natural and anthropogenic drivers
in the observed variability. The specific objectives are outlined as follows: (1) to understand
the crop phenology of Indian agroecosystems from site-scale observational data, (2) to improve
the CLM5 model using site-scale observations, (3) to evaluate the improved CLM5 model
at a regional scale, (4) to estimate the regional and inter-annual variability of crop growth
parameters and terrestrial fluxes within Indian agroecosystems and the role of various drivers
using CLM5 model, and finally (5) to evaluate the improved CLM5 model against the state-ofthe-art 
LSM representing Indian agroecosystems.

First, Chapter 2 addresses the objective 1 that attempts to solve the main bottleneck
in accurately simulating Indian agroecosystems, specifically the absence of publicly accessible
crop datasets that hinders our ability to quantitatively understand and model agroecosystems.
This thesis compiled a novel crop dataset focusing on two significant crops in India: rice and
wheat. This was done by digitizing the archived masters and doctoral thesis from agricultural
universities across India. The crop dataset spans from 1970 to 2020, encompassing site-scale
observations across 47 sites and 147 growing seasons. This dataset served as the foundation
for calibrating the CLM5 model. The LAI data from the site-scale observations shows that
the major growing season for rice is June to October and for wheat it is November to April.
Major observations from the data analysis are that rice and wheat have a statistically significant 
increasing trend in yield (38 kg/ha/yr– 97.4% increase, for rice and 34 kg/ha/yr– 83%
increase, for wheat) over the 1970-2020 period. However, there is no considerable difference
or trend observed in the growing season length of the crops during this period. Interestingly,
a statistically significant increasing trend in harvest dates of wheat crop is observed from the
dataset; harvest dates extended by ∼14 days over the 50-year period (p<0.1).

Chapter 3 addresses objective 2, where the CLM5 model is improved and evaluated
against site-scale observations. The default version of the CLM5 model failed to replicate the
crop phenology and growth seen in the site-scale observations. To address this drawback, the
crop module in CLM5 is calibrated and validated at a point scale using the novel Indian crop
dataset compiled in this thesis. The representation of crops in CLM5 is improved through a
two-step approach: (1) calibrating the growing season and crop parameters specific to crop
growth; (2) integrating regional variations in crop growth parameters, which is crucial for a
country like India with its diverse climate conditions. The calibration of the growing season
and crop parameters involved 30 sensitivity simulations. I evaluated the base temperature
used in calculating the growing degree days for the crop at each site to account for the regional
variability in crop growth. One hundred fifty sensitivity experiments are carried out to establish
a relationship between latitude and base temperature for a crop. The calibration of the model
significantly improved the simulation of the growing season, crop physiological parameters, crop
phenology, and yield compared to site-scale observations. RMSE for Leaf Area Index (LAI) in
wheat and rice reduced by ∼50%. The RMSE in yield estimations for wheat and rice reduced
by ∼40% and ∼60%, respectively. The RMSE of the growing season length for the wheat crop
reduced by ∼75%.

Chapter 4 addresses objective 3, where the improved CLM5 is evaluated at regional
scale by conducting numerical simulations for the 2000–2014 period. For this purpose, the
values of yield, irrigation amounts and patterns, and terrestrial fluxes simulated by the default
and improved models are compared against multiple data sources. The results show that the
CLM5 improvements reduce the RMSE in rice yield by 25% and the RMSE in GPP by about
50%. Major improvements are also observed in water and energy fluxes at the regional scale
after improvements to the crop module. The irrigation pattern and amount irrigated saw a
considerable improvement and are now closer to observations. The findings from the site-scale
and regional-scale assessment of the improved model underscore the importance of employing
region-specific crop parameters to accurately simulate agroecosystems and regional land surface
processes.

Chapter 5 addresses objective 4. The chapter examines the regional and inter-annual
variability in crop yield and terrestrial fluxes within Indian agroecosystems, utilizing multidecadal 
simulations that cover the period from 1970 to 2014. Furthermore, numerical experiments are conducted 
to investigate the impact of two natural and two agricultural management
factors on the observed trends in crop physiology and terrestrial fluxes throughout the simulation period. 
The LAI, yield, total dry matter of wheat and rice, and the carbon fluxes associated
with the crops in their respective growing regions demonstrated statistically significant increasing trends 
(p<0.05) from 1970 to 2014. The numerical experiments revealed that management
practices predominantly drive the upward trend, while the rise in CO2 is also a significant
driver. The application of nitrogen fertilization had a significant impact on rice yield, which
is cultivated in warm and wet seasons. Irrigation primarily influenced wheat yield, which is
grown in dry and cold seasons. Even with the detrimental effects of climate on crop growth
and terrestrial fluxes, higher CO2 levels and increased human activities, like fertilization and
irrigation, alleviated these challenges, leading to a rise in crop yields over the study period.

Chapter 6 of the thesis performs a comparative analysis of the CLM5 model and the
Integrated Science Assessment Model (ISAM), which is the only other land surface model
calibrated and assessed (Gahlot et al., 2020) to simulate the Indian crops to the best of my
knowledge. This thesis has two advantages over the Gahlot et al. (2020). First, the CLM
model is calibrated using data from 14 sites covering 33 growing seasons. Second, this study
investigates both rice and wheat as opposed to Gahlot et al. (2020), who look at only spring
wheat. Numerical experiments conducted in Chapter 5 with CLM5 were repeated using the
ISAM model. The findings demonstrate that CLM5 simulates the observed variation in growing
season length more precisely with an RMSE of 14 days, in contrast to the ISAM model, which
has an RMSE of 28 days. The wheat yield in CLM5 shows a strong sensitivity to nitrogen
fertilization, while in ISAM, the yield demonstrates a significant sensitivity to irrigation. The
AR/GPP ratio exhibits variability in CLM5, while it remains constant in ISAM. The ratio
in ISAM is comparatively low when evaluated against the values reported in multiple studies.
Examining climate and human management impacts on carbon fluxes reveals that although
net primary productivity (NPP) trends in CLM5 and ISAM are similar, the effects of human
management practices on carbon fluxes vary considerably. Nitrogen fertilization has a significant 
impact in CLM5, while irrigation shows a more substantial effect in ISAM. Comparing
the current state-of-the-art representation of Indian agroecosystems in LSMs, i.e., CLM5 and
ISAM, major conclusions are drawn. Both models have a lot of scope for improvement. CLM5
can incorporate the precipitation variability to simulate regional variability in sowing dates.
ISAM can incorporate an improved carbon-nitrogen cycle so that the simulated carbon fluxes
over agroecosystems are closer to observations.

This is the first study to address the long-term spatial and inter-annual variability of
agroecosystem physiological parameters and their terrestrial fluxes in India using a robustly
calibrated LSM. One of the primary contributions of this work is making the Indian crop data
accessible to all model developers to enhance Indian crop simulation in models, which is a
long-lasting bottleneck in the accurate representation of Indian crops.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Publication page'
  focal_point: "smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
