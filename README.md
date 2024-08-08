# Climate_Change_Data_Analysis

## Introduction 
Climate Change 
Climate change is the long-term alteration of temperature and typical weather patterns in a place. Climate change could refer to a particular location or the planet as a whole. Climate change may cause weather patterns to be less predictable. Climate change represents one of the most pressing issues facing our planet today. Its impacts are wide-ranging and profound, affecting ecosystems, weather patterns, sea levels, and human societies. Understanding the trends, causes, and effects of climate change is crucial for developing effective strategies to mitigate its impact and adapt to its inevitable consequences. This project aims to analyse climate change data to uncover significant trends, patterns, and anomalies. Through this project, we aim to contribute to the scientific understanding of climate change and provide valuable insights that can inform policy decisions, public awareness, and future research. The findings will be presented in a comprehensive report, supported by visualizations and interactive tools to facilitate a deeper understanding of the data and its implications. By systematically analysing climate change data, we hope to underscore the urgency of addressing this global challenge and highlight the areas where intervention is most needed. Our goal is to support efforts in combating climate change by providing robust, data-driven evidence of its current state and potential future trajectories.
Libraries Used
•	Pandas :  An open-source software library built on top of Python specifically for data manipulation and analysis, Pandas offers data structure and operations for powerful, flexible, and easy-to-use data analysis and manipulation.
•	Numpy :  NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices.
•	Matplotlib :  Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible. Create publication quality plots. Make interactive figures that can zoom, pan, update.
•	Seaborn : Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures. Seaborn helps in exploring and understanding our data.

## Literature Survey
The Dataset Chosen for this Project is from Berkeley Earth.
Berkeley Earth supplies comprehensive open-source world air pollution data and highly user-accessible global temperature data that is timely, impartial, and verified.
Given this complexity, there are a range of organizations that collate climate trends data. The three most cited land and ocean temperature data sets are NOAA’s MLOST, NASA’s GISTEMP and the UK’s HadCrut.
The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 16 pre-existing archives. It is nicely packaged and allows for slicing into interesting subsets (for example by country). They publish the source data and the code for the transformations they applied. They also use methods that allow weather observations from shorter time series to be included, meaning fewer observations need to be thrown away.

The Dataset contain several attributes/fields, such as:
Date: starts in 1750 for average land temperature and 1850 for max and min land temperatures and global ocean and land temperatures
LandAverageTemperature: global average land temperature in celsius
LandAverageTemperatureUncertainty: the 95% confidence interval around the average
LandMaxTemperature: global average maximum land temperature in celsius
LandMaxTemperatureUncertainty: the 95% confidence interval around the maximum land temperature
LandMinTemperature: global average minimum land temperature in celsius
LandMinTemperatureUncertainty: the 95% confidence interval around the minimum land temperature
LandAndOceanAverageTemperature: global average land and ocean temperature in celsius
LandAndOceanAverageTemperatureUncertainty: the 95% confidence interval around the global average land and ocean temperature
The raw data comes from the Berkeley Earth data page.


