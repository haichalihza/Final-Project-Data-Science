# Comparison of Performance and Dashboard Visualization of High Dimensional Clustering Methods Against Outliers in East Java SDG Data

## Project Background
This study aims to analyze Sustainable Development Goals (SDG) data in East Java Province which has high dimensions and contains outliers using various robust clustering methods. SDG is a global sustainable development agenda which is also the main focus in East Java as a large province with complex social, economic and health challenges. 

SDGs dataset consisting of 40 dimensional reduced variables into 4 main components using the principal component analysis (PCA) to facilitate analysis. Five clustering methods are tested, namely DBSCAN, Fuzzy C-Means (FCM), Possibilistic C-Means (PCM), Fuzzy Possibilistic C-Means (FPCM), and Modified Fuzzy Possibilistic C-Means (MFPCM).

This research is expected to make an important contribution in the management of complex SDGs data and support the achievement of sustainable development targets at the provincial level. 

## Problem Statement
The main problems in this research are:
1. The SDG's data used has the potential to have a lot of noise or outlier data so it really influences the clustering method used.
2. SDG data grouping that has outlier data has the potential to produce cluster quality that has low performance
3. Data analysis from results that have not yet carried out comprehensive data exploration, visualization and evaluation tests that cannot help in making strategic planning decisions
4. Find out the variables that are representative of the information that will be explored in the East Java Province SDG data using the data dimension reduction method.

## Knowing the Dataset
The dataset used comes from the official [BPS East Java website](https://jatim.bps.go.id/id)

- X<sub>1</sub>   : Human Development Index (%)
- X<sub>2</sub>   : Per Capita Expenditure (IDR)
- X<sub>3</sub>   : Expected Years of Schooling based on number of years
- X<sub>4</sub>   : The economic inequality ratio is based on income distribution per city/district
- X<sub>5</sub>   : Number of Poor Population per city/district
- X<sub>6</sub>   : Percentage of Poor Population (%)
- X<sub>7</sub>   : Poverty Severity Index (%)
- X<sub>8</sub>   : Poverty Depth Index (%)
- X<sub>9</sub>   : Number of kindergarten students per city/district
- X<sub>10</sub>  : Number of elementary school students per city/district
- X<sub>11</sub>  : Number of middle school students per city/district
- X<sub>12</sub>  : Number of high school students per city/district
- X<sub>13</sub>  : Number of vocational high school students per city/district
- X<sub>14</sub>  : Number of kindergarten teachers per city/district
- X<sub>15</sub>  : Number of elementary school teachers per city/district
- X<sub>16</sub>  : Number of middle school teachers per city/district
- X<sub>17</sub>  : Number of high school teachers per city/district
- X<sub>18</sub>  : Number of vocational high school teachers per city/district
- X<sub>19</sub>  : Number of kindergarten schools per city/district
- X<sub>20</sub>  : Number of elementary schools per city/district
- X<sub>21</sub>  : Number of middle schools per city/district
- X<sub>22</sub>  : Number of high schools per city/district
- X<sub>23</sub>  : Number of vicational high schools per city/district
- X<sub>24</sub>  : Open Unemployment Rate (%)
- X<sub>25</sub>  : Labor Force Participation Rate (%)
- X<sub>26</sub>  : Toddlers receive complete immunization (%)
- X<sub>27</sub>  : Gender Equality Index (IKG) (%)
- X<sub>28</sub>  : Poverty Line (IDR)
- X<sub>29</sub>  : Life Expectancy (%)
- X<sub>30</sub>  : Economic Growth (%)
- X<sub>31</sub>  : Per Capita Expenditure for food (%)
- X<sub>32</sub>  : Per Capita Expenditure for non-food (%)
- X<sub>33</sub>  : Citizens have not completed eleementary school (%)
- X<sub>34</sub>  : Citizens have completed eleementary school (%)
- X<sub>35</sub>  : Citizens have completed middle school (%)
- X<sub>36</sub>  : Citizens have completed high school (%)
- X<sub>37</sub>  : Citizens have completed vocational high school (%)
- X<sub>38</sub>  : Citizens have completed certificate degree(D1/D2)/associate degree(D3) (%)
- X<sub>39</sub>  : Citizens have completed Bachelor Degree(D4/S1)/Master Degree(S2) (%)
- X<sub>40</sub>  : Regional Gross Domestic Product (%)
