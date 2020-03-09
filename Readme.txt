**Environment Setup**

1. The environment setup and package installation codes are in the fist chunck in rmd file. 
	I tested in different machines and the setcode runs fine, but in case there is an error in the 
	setup process, please double check whether below packages are installed.

-data cleaning and mungling: tidyverse, dplyr (contained within tidyverse), plyr, 
	stringr (contained within tidyverse), lubridate, naniar

-visualization: ggmap, ggplot2 (contained within tidyverse), leaflet, leaflet.extras, sp, ggrepel

-formating and final presentation: grid, gridExtra, magrittr, rmarkdown, knitr


2. I used ggmap and leaflet packages to make interactive maps. Both packages require 
   internet access when re-run and re-knit the document because they need to connect with google map. 
   The knitting process takes about 3 min to generate html file.

**Graph**

1. png documents: I stored all visualizations except the interactive one into png file and saved them as png files
	in viz_png folder. 

2. For the airbnb_missing graph, part of the codes come from Jens Laufer online posting at 
	https://jenslaufer.com/data/analysis/visualize_missing_values_with_ggplot.html

**Report**

1. I used rmarkdown to knit the report as html format, and it was named as DataChallenge_YW. 
	The report needs to be opened in browser.

2. The code was folded in the report but can be expanded when clicking the "code" sign in the document.
	There is also a "show all code" option on the top right corner under the "code" sign to show all codes.

3. I stored the data quality report along with the metadata word document as well as in the rmarkdown file.
