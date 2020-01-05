# Coursera Capstone
A repository for the capstone project for the IBM Data Science Certificate course

Introduction / Business Problem
--

Melbourne (Australia) is a large, cosmopolitan city in the southeast of Australia. It is home to many people from different cultures, and the city has a thriving restaurant scene.

An Iranian restaurateur is planning to open a new Persian restaurant. The restaurant is intended to be traditional, yet appeal to non-Persians too. He is trying to decide which suburb of Melbourne would be the best one to locate this restaurant.

The restaurateur is concerned that there is a limited market for fine Persian cuisine. Thus, if he chooses a location close to another Persian restaurant, it will attract only a small number of patrons. Nonetheless, he would like to locate his restaurant in a multicultural restaurant hub. He believes that a busy and diverse restaurant district will attract many customers, and that he will have a competitive advantage in being the only Persian restaurant in the area. He wants the restaurant to be located no further than 25 kilometres (15.5343 miles) from the city centre.

The aim of the data science project is to rank each suburb in terms of its suitability according to the above criteria.

Data
--
The problem will be addressed using two datasets:
* The first dataset is a collection of latitude/longitude coordinates for each Melbourne suburb (obtained from: https://gist.github.com/randomecho/5020859). Suburbs located more than 25km from the city will be filtered out.
* The second dataset is the Foursquare data. This will be used to obtain information about each location, including restaurants in each area. The data will be used to calculate: (1) the Euclidean distance from each suburb to the nearest Persian restaurant, (2) the number of restaurants in each district, (3) the diversity of restaurants in each area (using the Simpson-Gini coefficient: https://en.wikipedia.org/wiki/Diversity_index#Gini%E2%80%93Simpson_index).
