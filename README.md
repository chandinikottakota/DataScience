[Spotify_2024_Global_Streaming_Data.csv](https://github.com/user-attachments/files/19703608/Spotify_2024_Global_Streaming_Data.csv)# 🎧 Spotify Global Streaming Data 2024 - Exploratory Data Analysis (EDA)

This project performs a comprehensive Exploratory Data Analysis (EDA) on the **Spotify Global Streaming Data (2024)** dataset. The goal is to uncover patterns, trends, and actionable insights related to user behavior, streaming preferences, and artist performance across countries and platform types.

---

## 📂 Dataset Overview

The dataset includes information such as:
- 🎤 Artist & Album details
- 🌍 Country-wise streaming data
- ⏱️ Total and average stream duration
- 💳 Platform type (Free or Premium)
- ⛔ Skip rate
- 📈 Monthly Listeners & Streams (Last 30 Days)

---

## 🎯 Objectives

This analysis aims to answer the following questions:

1. How has listener growth changed based on **album release year**?
2. In **which month** do users stream music the most?
3. How many **hours** are streamed by **Free vs. Premium** users?
4. What is the **skip rate** difference between Free and Premium users?
5. Who is the **most favorite artist** per country?
6. How many **total minutes/hours** are consumed by platform type?
7. Which **artist’s album** has the most usage?
8. Other key streaming **trends and outliers**

---

## 📊 Tools & Libraries Used

- **Python**
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn`, `plotly` – Visualizations
- `scipy.stats` – Statistical insights
- `jupyter notebook` – Development environment

---

## 🧠 Analysis Workflow

1. **Introduction & Agenda**
2. **Data Loading & Cleaning**
3. **Univariate Analysis**
   - Distribution of release years, skip rates, stream durations
4. **Bivariate Analysis**
   - Correlations between listeners, streams, and hours
   - Free vs Premium behavior comparison
   - Heatmaps and scatter plots for deep dives
5. **Group-wise Aggregations**
   - By `Country`, `Platform Type`, `Artist`, `Genre`, and `Release Year`
6. **Visual Insights**
   - Histograms, bar charts, box plots, heatmaps, interactive charts
7. **Observations & Insights**
   - Each plot is followed by a detailed interpretation
8. **Final Summary & Recommendations**

---

## 📌 Key Insights

- Premium users stream significantly more hours than Free users.
- Certain countries contribute heavily to the total stream count.
- Skip rates are higher among Free users.
- Recent album releases tend to have higher monthly listeners.
- A few artists dominate global streaming trends across many countries.

---

## ✅ Conclusion

This project highlights how deep EDA can help stakeholders and music platforms:
- Optimize recommendation engines
- Identify market trends
- Improve user engagement strategies
- Target new users based on listening behavior

---

## 📎 Files


[Uploading Spotify_2024_GCountry,Artist,Album,Genre,Release Year,Monthly Listeners (Millions),Total Streams (Millions),Total Hours Streamed (Millions),Avg Stream Duration (Min),Platform Type,Streams Last 30 Days (Millions),Skip Rate (%)
Germany,Taylor Swift,1989 (Taylor's Version),K-pop,2019,23.1,3695.53,14240.35,4.28,Free,118.51,2.24
Brazil,The Weeknd,After Hours,R&B,2022,60.6,2828.16,11120.44,3.9,Premium,44.87,23.98
United States,Post Malone,Austin,Reggaeton,2023,42.84,1425.46,4177.49,4.03,Free,19.46,4.77
Italy,Ed Sheeran,Autumn Variations,K-pop,2018,73.24,2704.33,12024.08,3.26,Premium,166.05,25.12
Italy,Ed Sheeran,Autumn Variations,R&B,2023,7.89,3323.25,13446.32,4.47,Free,173.43,15.82
Sweden,Billie Eilish,Happier Than Ever,Indie,2019,37.65,1087.06,3298.09,4.37,Free,122.22,7.67
France,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Rock,2021,27.72,4630.69,17950.05,2.94,Premium,168.73,31.26
France,Doja Cat,Scarlet,Pop,2020,40.72,377.63,1633.73,3.63,Premium,43.31,20.47
Sweden,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,K-pop,2019,25.42,2828.77,8558.4,3.67,Premium,73.04,39.9
United Kingdom,Ariana Grande,Eternal Sunshine,Rock,2018,75.82,4312.46,12099.39,2.82,Premium,119.69,16.01
Argentina,Dua Lipa,Future Nostalgia,Jazz,2020,97.14,4310.86,10876.14,3.94,Premium,153.95,14.27
South Korea,BLACKPINK,BORN PINK,Reggaeton,2021,1.32,3624.36,14277.66,4.44,Free,102.03,5.15
South Korea,Doja Cat,Scarlet,Jazz,2022,20.69,1900.87,5366.34,4.41,Free,120.19,20.06
Germany,SZA,SOS,Indie,2020,24.71,1242.31,4515.44,2.66,Premium,163.39,39.14
South Africa,Post Malone,Austin,Reggaeton,2019,66.32,4736.9,13406.63,3.56,Premium,192.91,37.23
Australia,Karol G,MAÑANA SERÁ BONITO,K-pop,2021,99.52,3266.9,11029.71,3.54,Free,50.33,3.5
United States,Ed Sheeran,Autumn Variations,Jazz,2019,59.26,85.59,335.14,2.62,Free,181.18,34.53
Brazil,Ariana Grande,Eternal Sunshine,R&B,2020,67.23,1110.47,3070.03,4.37,Premium,49.36,19.45
Netherlands,The Weeknd,After Hours,Hip Hop,2018,66.24,1803.77,5992.49,4.23,Free,135.0,39.38
Germany,Taylor Swift,1989 (Taylor's Version),EDM,2023,34.59,4315.28,12934.24,2.88,Premium,28.9,8.16
Sweden,The Weeknd,After Hours,Hip Hop,2021,80.99,4287.04,11557.08,3.8,Free,193.83,37.13
France,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,EDM,2021,48.65,4330.02,18640.24,2.83,Free,197.08,11.34
Sweden,BTS,Proof,EDM,2023,95.77,4977.34,17975.85,3.94,Free,38.79,9.49
India,Ed Sheeran,Autumn Variations,Jazz,2018,75.05,332.97,1221.45,3.51,Free,12.32,20.81
Canada,Drake,For All The Dogs,Classical,2018,67.85,1214.26,3326.8,4.28,Free,116.2,2.55
Brazil,BLACKPINK,BORN PINK,Classical,2022,52.76,4676.8,13602.56,3.93,Free,53.86,6.1
South Korea,Dua Lipa,Future Nostalgia,Indie,2018,1.92,3124.74,11330.27,2.7,Free,101.67,6.17
Italy,SZA,SOS,Hip Hop,2019,37.58,830.85,3462.56,3.91,Free,133.9,22.63
Germany,SZA,SOS,Reggaeton,2020,12.43,579.83,2091.13,3.04,Free,143.8,8.94
Mexico,Ariana Grande,Eternal Sunshine,Rock,2020,90.63,4238.21,11377.89,3.35,Premium,9.77,14.01
United Kingdom,Billie Eilish,Happier Than Ever,K-pop,2019,74.38,2780.82,9330.69,2.52,Free,189.07,27.95
United Kingdom,Ariana Grande,Eternal Sunshine,Pop,2020,58.67,783.06,2157.24,3.12,Free,179.89,9.19
France,Billie Eilish,Happier Than Ever,Hip Hop,2020,78.23,4426.47,14663.81,3.74,Free,185.23,10.23
Canada,Post Malone,Austin,Reggaeton,2021,3.45,3695.99,11695.48,4.36,Free,54.09,31.71
Germany,BLACKPINK,BORN PINK,Pop,2021,23.02,4092.1,13997.46,3.11,Free,45.36,26.74
Spain,Olivia Rodrigo,Guts,K-pop,2018,96.72,1431.67,5415.96,3.3,Premium,187.91,5.5
Mexico,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2020,4.79,3003.03,9583.79,4.07,Premium,121.64,20.95
Spain,SZA,SOS,Classical,2019,26.22,3558.49,8908.26,4.35,Free,73.48,3.73
Japan,Ed Sheeran,Autumn Variations,Indie,2023,84.95,3612.78,11201.95,3.12,Premium,65.91,28.19
South Africa,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,R&B,2021,66.83,1926.77,7699.89,2.85,Premium,81.81,33.52
South Korea,BTS,Proof,R&B,2021,78.79,3052.97,9600.06,3.38,Free,102.72,31.96
Canada,Billie Eilish,Happier Than Ever,Hip Hop,2020,52.03,3183.06,10091.5,4.14,Free,134.89,9.76
Australia,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Pop,2018,25.24,2401.92,10086.8,2.65,Premium,177.34,23.45
Spain,Dua Lipa,Future Nostalgia,EDM,2019,15.61,3453.73,14800.34,4.22,Free,155.91,9.53
Indonesia,Dua Lipa,Future Nostalgia,Pop,2022,25.67,4249.26,14502.4,4.1,Premium,190.06,35.77
Argentina,Doja Cat,Scarlet,Jazz,2021,83.23,2761.97,11861.05,3.99,Premium,90.56,30.32
Mexico,Post Malone,Austin,Jazz,2021,63.05,1409.26,3741.54,3.07,Premium,67.83,35.83
Brazil,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Reggaeton,2019,38.92,806.39,2361.03,3.33,Premium,108.98,17.22
Australia,Doja Cat,Scarlet,EDM,2021,90.58,2941.19,11444.31,4.21,Premium,95.92,37.77
South Korea,Post Malone,Austin,EDM,2021,54.28,3686.44,15113.43,4.3,Premium,44.66,18.0
United States,BLACKPINK,BORN PINK,Indie,2023,68.24,2051.37,5805.56,3.43,Free,196.16,21.83
Spain,Ed Sheeran,Autumn Variations,Classical,2023,3.68,3231.61,8956.08,3.42,Free,52.77,13.77
Sweden,Olivia Rodrigo,Guts,Indie,2021,28.55,4758.46,15908.15,4.17,Premium,4.86,22.04
Italy,The Weeknd,After Hours,Hip Hop,2023,4.99,203.6,609.69,4.18,Free,48.47,19.47
Germany,Ed Sheeran,Autumn Variations,R&B,2021,70.25,3846.15,10906.06,3.71,Free,155.78,7.39
South Korea,Drake,For All The Dogs,Classical,2018,92.96,2900.19,12517.37,3.25,Free,16.12,27.93
France,Drake,For All The Dogs,K-pop,2023,60.44,649.22,2900.51,4.07,Premium,107.02,26.8
Brazil,Ariana Grande,Eternal Sunshine,Indie,2018,85.11,4120.54,11171.1,4.42,Premium,141.75,17.98
Indonesia,Billie Eilish,Happier Than Ever,K-pop,2022,81.01,2713.96,9409.29,3.37,Premium,65.14,10.57
Brazil,BTS,Proof,Rock,2019,75.3,2870.76,11013.32,3.17,Premium,170.34,8.09
Australia,Olivia Rodrigo,Guts,K-pop,2020,28.69,3000.97,12784.78,3.61,Free,18.04,29.08
Russia,Ariana Grande,Eternal Sunshine,R&B,2023,48.13,3573.62,12137.26,2.53,Premium,45.1,27.98
South Korea,Billie Eilish,Happier Than Ever,Classical,2020,47.85,2678.06,8974.2,3.99,Premium,71.01,18.7
South Korea,BTS,Proof,R&B,2018,72.41,1611.96,6424.89,4.4,Free,39.12,29.81
Mexico,Karol G,MAÑANA SERÁ BONITO,Classical,2022,60.08,4903.53,20424.46,3.09,Premium,36.71,1.55
South Africa,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,K-pop,2018,97.46,2789.13,10863.2,2.75,Premium,21.41,1.48
South Korea,Dua Lipa,Future Nostalgia,Rock,2021,34.73,4829.21,14511.57,4.22,Free,164.6,16.63
Brazil,Ed Sheeran,Autumn Variations,Pop,2019,15.77,2836.06,8813.54,4.49,Free,112.06,17.23
Argentina,Post Malone,Austin,Classical,2019,77.79,1932.87,8344.22,3.09,Premium,61.77,25.22
Argentina,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2019,62.93,1360.0,3620.83,2.98,Free,32.15,16.93
Argentina,Dua Lipa,Future Nostalgia,K-pop,2018,23.92,3549.43,13863.99,3.41,Free,184.86,31.73
Turkey,Billie Eilish,Happier Than Ever,R&B,2021,12.36,1162.81,3253.52,3.03,Free,15.21,7.47
South Korea,Ed Sheeran,Autumn Variations,Classical,2020,44.48,2370.05,7366.55,3.31,Premium,100.59,20.26
Brazil,Ed Sheeran,Autumn Variations,Pop,2021,73.72,3038.38,7753.12,2.96,Free,199.91,27.22
Mexico,Ed Sheeran,Autumn Variations,Pop,2019,47.58,3274.97,14187.65,2.86,Premium,127.32,20.18
Brazil,Dua Lipa,Future Nostalgia,Indie,2021,34.0,3367.16,14194.15,3.16,Premium,58.36,37.86
South Africa,Taylor Swift,1989 (Taylor's Version),Rock,2018,32.14,1650.21,7327.54,3.31,Free,131.87,22.16
Netherlands,Taylor Swift,1989 (Taylor's Version),R&B,2022,36.82,3794.39,14232.06,4.02,Free,54.14,6.11
South Korea,Dua Lipa,Future Nostalgia,Rock,2018,3.86,3168.61,12986.95,3.92,Premium,110.62,22.54
Brazil,The Weeknd,After Hours,Hip Hop,2021,94.76,3256.16,9143.11,4.37,Premium,102.27,11.66
Russia,Dua Lipa,Future Nostalgia,R&B,2021,55.58,1948.75,8464.86,3.52,Free,172.94,11.77
Netherlands,Olivia Rodrigo,Guts,Jazz,2020,82.23,1450.05,4490.97,3.67,Premium,173.19,18.42
Russia,Olivia Rodrigo,Guts,Indie,2022,76.52,1917.19,8369.89,4.24,Free,114.79,10.11
Netherlands,Taylor Swift,1989 (Taylor's Version),Indie,2023,47.82,4571.48,14914.28,4.48,Free,99.57,2.44
Indonesia,Ed Sheeran,Autumn Variations,Indie,2018,87.54,2229.52,7919.04,3.41,Free,82.59,26.54
United Kingdom,Drake,For All The Dogs,Rock,2020,34.52,3478.89,13218.65,4.2,Premium,190.87,25.45
Russia,Doja Cat,Scarlet,Jazz,2018,62.13,1212.11,4689.41,3.07,Free,149.61,17.92
Germany,Post Malone,Austin,Hip Hop,2021,17.47,1532.36,3919.62,3.15,Free,59.38,15.62
United Kingdom,The Weeknd,After Hours,Jazz,2021,57.03,3972.97,11283.1,2.66,Premium,124.32,10.39
Turkey,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,R&B,2021,64.15,2324.87,8912.81,4.3,Premium,180.34,27.43
Canada,Drake,For All The Dogs,Rock,2020,98.78,1530.81,6772.39,3.88,Premium,169.22,8.77
Spain,Doja Cat,Scarlet,Rock,2018,24.48,2881.02,10514.64,4.49,Premium,5.37,33.37
Spain,BTS,Proof,Pop,2022,86.64,3902.64,17355.84,4.32,Premium,166.73,36.21
France,Ed Sheeran,Autumn Variations,Indie,2019,64.03,3123.41,12042.4,3.94,Free,126.02,36.23
India,BTS,Proof,Rock,2018,58.38,3675.18,9850.46,3.09,Premium,35.95,6.15
South Africa,SZA,SOS,Indie,2022,50.68,1399.01,3957.92,4.33,Premium,193.51,12.51
Japan,Post Malone,Austin,Hip Hop,2021,96.33,746.75,3310.34,4.22,Premium,193.49,32.38
Italy,Drake,For All The Dogs,EDM,2018,27.18,661.76,2142.23,4.0,Premium,117.33,33.07
Italy,Drake,For All The Dogs,R&B,2021,3.48,4426.96,16038.06,4.33,Free,129.88,25.78
Sweden,SZA,SOS,K-pop,2023,41.42,741.9,3258.81,3.11,Premium,24.11,10.16
South Africa,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,EDM,2021,37.73,4749.43,18489.38,3.58,Free,177.2,26.54
Russia,Ed Sheeran,Autumn Variations,EDM,2020,4.24,1884.12,6381.07,4.4,Premium,20.77,27.74
South Africa,SZA,SOS,Indie,2018,40.42,989.55,2715.64,4.2,Premium,19.24,9.27
Argentina,Taylor Swift,1989 (Taylor's Version),Pop,2020,25.11,673.32,2443.58,2.64,Free,117.69,32.71
France,Olivia Rodrigo,Guts,Reggaeton,2022,1.28,4299.11,11991.83,2.76,Premium,159.9,5.29
United States,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Pop,2020,79.21,1227.76,3864.43,2.85,Free,26.22,17.42
Germany,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2021,45.38,1842.09,6792.4,3.4,Free,189.14,2.69
Indonesia,BTS,Proof,Rock,2023,96.44,351.09,1214.06,3.3,Free,98.56,36.48
Brazil,SZA,SOS,Hip Hop,2020,61.22,375.13,1144.16,3.77,Premium,76.8,24.3
South Korea,Dua Lipa,Future Nostalgia,Jazz,2022,43.59,3975.83,10849.36,3.81,Free,86.58,35.64
Netherlands,Olivia Rodrigo,Guts,Rock,2021,42.18,520.67,1746.08,3.83,Premium,190.76,27.79
Russia,Drake,For All The Dogs,Hip Hop,2018,10.23,527.99,2100.13,4.12,Free,117.71,22.9
Japan,Billie Eilish,Happier Than Ever,Hip Hop,2021,36.01,3343.44,13375.66,4.24,Free,193.71,24.42
Italy,Drake,For All The Dogs,Classical,2022,22.06,3300.84,9732.49,2.72,Premium,23.86,11.86
France,Post Malone,Austin,EDM,2022,97.48,4101.21,15285.81,3.79,Free,122.19,26.66
Mexico,Taylor Swift,1989 (Taylor's Version),Reggaeton,2020,70.57,1579.47,5022.16,2.51,Free,113.7,16.63
United Kingdom,Karol G,MAÑANA SERÁ BONITO,Pop,2018,74.87,1114.91,3723.43,3.18,Premium,63.02,13.65
Turkey,Ed Sheeran,Autumn Variations,Hip Hop,2018,16.4,3784.46,9837.8,2.66,Premium,132.73,19.94
Sweden,BLACKPINK,BORN PINK,K-pop,2019,75.74,613.4,2060.92,3.07,Premium,105.86,13.03
France,BLACKPINK,BORN PINK,Classical,2018,1.76,1542.03,4506.53,2.77,Premium,58.6,5.68
Russia,Karol G,MAÑANA SERÁ BONITO,EDM,2019,13.79,2686.28,7951.98,3.62,Premium,15.34,34.61
India,BLACKPINK,BORN PINK,Pop,2021,92.2,4317.44,15765.21,3.65,Premium,58.61,16.8
Japan,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2021,83.37,4602.86,12318.45,4.19,Free,87.7,16.62
Brazil,BLACKPINK,BORN PINK,K-pop,2023,34.61,1698.69,4817.94,3.52,Free,106.59,8.56
Italy,Olivia Rodrigo,Guts,Reggaeton,2019,11.18,1317.04,3749.61,2.81,Free,36.25,31.14
Russia,Dua Lipa,Future Nostalgia,Classical,2022,45.44,4624.56,16782.45,3.77,Premium,172.99,25.46
United Kingdom,Dua Lipa,Future Nostalgia,Hip Hop,2021,44.78,1548.96,4723.32,2.61,Free,62.77,18.62
India,Olivia Rodrigo,Guts,K-pop,2018,64.82,4887.97,13102.66,3.69,Premium,93.08,22.62
India,Dua Lipa,Future Nostalgia,Classical,2023,19.64,3044.78,10665.06,4.42,Premium,21.6,36.07
Japan,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2022,64.97,243.75,954.34,4.48,Free,73.42,36.8
Spain,BLACKPINK,BORN PINK,Indie,2023,60.19,3956.67,15014.02,2.63,Free,112.03,16.08
Mexico,Karol G,MAÑANA SERÁ BONITO,Classical,2019,34.0,2934.56,8166.46,3.2,Premium,26.66,28.64
Brazil,BTS,Proof,Jazz,2021,64.71,1675.96,4618.25,3.91,Free,129.56,17.51
Italy,Taylor Swift,1989 (Taylor's Version),Indie,2020,18.85,1110.25,4879.92,3.47,Free,200.0,7.04
South Korea,Doja Cat,Scarlet,Hip Hop,2022,77.32,4183.84,17853.97,2.58,Premium,175.4,25.1
Argentina,BLACKPINK,BORN PINK,Reggaeton,2019,18.9,3479.59,13046.66,4.31,Premium,9.69,15.21
France,Dua Lipa,Future Nostalgia,Classical,2020,75.49,3929.81,11663.7,2.98,Premium,180.89,8.57
Turkey,Dua Lipa,Future Nostalgia,Rock,2020,78.03,2539.39,8474.76,2.82,Free,160.45,6.4
Mexico,Taylor Swift,1989 (Taylor's Version),Rock,2020,55.9,557.82,2338.26,4.2,Premium,17.69,7.25
Sweden,SZA,SOS,Jazz,2019,83.27,503.98,2177.7,4.13,Premium,186.16,17.18
Spain,Ariana Grande,Eternal Sunshine,Indie,2019,39.23,453.95,1338.73,3.14,Free,168.0,26.35
United Kingdom,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Pop,2020,91.82,2388.65,9942.09,4.02,Premium,90.27,1.2
Brazil,Taylor Swift,1989 (Taylor's Version),K-pop,2019,83.66,2766.58,10940.36,3.56,Free,155.46,10.27
Germany,Taylor Swift,1989 (Taylor's Version),R&B,2021,64.26,3132.91,8225.81,4.17,Premium,119.75,1.64
Indonesia,Ed Sheeran,Autumn Variations,R&B,2023,15.21,2174.73,8110.91,2.98,Premium,38.28,27.06
Indonesia,Olivia Rodrigo,Guts,Hip Hop,2022,54.86,3942.74,13859.7,2.54,Premium,9.66,16.09
Italy,BTS,Proof,Pop,2020,79.06,1756.77,6967.14,3.76,Premium,27.55,14.74
Japan,Doja Cat,Scarlet,Reggaeton,2023,47.0,3492.18,13142.72,4.12,Free,143.49,37.8
India,BTS,Proof,R&B,2018,79.32,4434.66,13885.77,3.12,Premium,197.84,22.18
Mexico,Taylor Swift,1989 (Taylor's Version),R&B,2020,36.34,3915.17,16567.42,3.16,Free,160.07,18.04
Spain,Karol G,MAÑANA SERÁ BONITO,Rock,2021,34.56,974.75,3786.06,3.23,Premium,160.43,29.36
Brazil,BLACKPINK,BORN PINK,Classical,2019,55.0,1640.0,4362.63,3.82,Premium,89.74,28.99
Canada,Karol G,MAÑANA SERÁ BONITO,Rock,2020,45.27,3647.73,15769.92,3.73,Premium,55.64,39.22
India,Drake,For All The Dogs,EDM,2020,51.8,3762.0,10608.74,2.56,Premium,7.92,3.62
Italy,Olivia Rodrigo,Guts,EDM,2022,4.21,809.52,2752.24,3.24,Premium,152.85,23.38
Indonesia,Olivia Rodrigo,Guts,EDM,2020,65.31,1285.58,3505.64,3.97,Premium,104.03,36.63
Germany,BTS,Proof,K-pop,2023,45.18,4982.01,15300.52,4.33,Premium,40.84,6.29
Brazil,Dua Lipa,Future Nostalgia,Reggaeton,2023,45.07,484.56,1872.27,4.19,Premium,133.9,28.67
South Africa,Ariana Grande,Eternal Sunshine,K-pop,2020,85.28,3573.46,15561.16,3.78,Premium,102.24,5.73
Australia,Post Malone,Austin,Reggaeton,2019,79.25,180.11,649.84,3.24,Free,122.78,4.36
South Korea,BLACKPINK,BORN PINK,Rock,2022,41.67,2076.7,7579.54,2.75,Premium,128.83,18.55
Indonesia,Olivia Rodrigo,Guts,Reggaeton,2022,64.34,950.72,4214.09,3.37,Free,166.45,21.21
South Korea,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Reggaeton,2020,93.54,1166.08,5124.88,3.54,Premium,169.34,10.77
South Africa,BTS,Proof,Reggaeton,2023,30.98,2690.72,9431.37,2.84,Free,35.07,25.35
Argentina,Olivia Rodrigo,Guts,Classical,2018,82.7,190.45,493.44,3.78,Premium,130.57,30.91
Netherlands,Ed Sheeran,Autumn Variations,Pop,2021,89.01,2750.61,10407.8,3.1,Free,161.13,27.71
South Korea,Dua Lipa,Future Nostalgia,Hip Hop,2023,6.93,2226.05,7721.06,2.91,Free,63.2,29.02
Italy,BLACKPINK,BORN PINK,Reggaeton,2020,51.98,575.61,1717.32,2.75,Premium,50.34,4.78
South Korea,BLACKPINK,BORN PINK,Classical,2021,25.58,4333.27,12217.22,3.15,Premium,38.78,7.21
Indonesia,Dua Lipa,Future Nostalgia,Rock,2020,50.24,495.74,1629.24,3.41,Free,43.81,14.76
India,BTS,Proof,Rock,2022,88.35,3288.59,11316.61,3.57,Free,86.75,35.42
Italy,Post Malone,Austin,EDM,2020,5.48,303.23,1098.79,3.23,Premium,15.63,20.67
South Africa,BTS,Proof,Classical,2023,61.49,686.88,1850.02,3.25,Premium,112.01,15.26
United Kingdom,The Weeknd,After Hours,Classical,2022,40.74,249.26,642.55,3.93,Premium,104.35,6.81
Indonesia,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Indie,2022,32.53,1995.13,7447.82,4.19,Premium,101.96,20.88
Russia,Karol G,MAÑANA SERÁ BONITO,Classical,2020,48.01,132.35,418.55,2.72,Premium,117.16,32.07
United States,Ed Sheeran,Autumn Variations,Rock,2020,96.74,3925.37,15906.87,3.66,Free,117.12,7.65
Argentina,Post Malone,Austin,EDM,2019,82.34,1248.87,4552.31,3.9,Free,4.77,13.23
United Kingdom,BLACKPINK,BORN PINK,R&B,2021,50.68,3076.82,10594.14,4.2,Free,141.45,21.23
South Africa,Olivia Rodrigo,Guts,Rock,2022,38.31,4785.59,16363.5,3.57,Premium,135.5,34.84
Mexico,Ed Sheeran,Autumn Variations,Rock,2019,95.78,1431.08,4432.05,4.38,Premium,154.46,28.49
Russia,Olivia Rodrigo,Guts,Rock,2020,56.49,4675.7,18437.82,3.08,Premium,179.26,16.39
Italy,Post Malone,Austin,Reggaeton,2020,5.16,4778.8,12702.33,4.35,Premium,149.72,9.35
South Africa,BTS,Proof,Jazz,2023,27.89,590.67,2351.92,2.98,Free,134.3,21.71
France,Taylor Swift,1989 (Taylor's Version),Hip Hop,2021,33.7,2388.4,9224.92,2.77,Free,81.97,37.47
Russia,Dua Lipa,Future Nostalgia,R&B,2020,32.8,3247.19,14014.46,2.68,Free,107.5,29.2
India,SZA,SOS,Reggaeton,2021,88.34,920.15,3992.78,4.49,Premium,157.8,8.27
South Korea,SZA,SOS,Pop,2018,30.54,3033.78,13217.91,3.17,Premium,197.83,22.19
Russia,SZA,SOS,Reggaeton,2022,47.33,1004.42,2737.34,2.82,Premium,130.01,29.03
United States,Karol G,MAÑANA SERÁ BONITO,Indie,2020,57.21,3798.55,10829.63,4.21,Premium,165.57,21.1
Brazil,BLACKPINK,BORN PINK,Hip Hop,2019,98.19,2413.4,10550.54,2.51,Premium,47.87,30.4
Japan,BTS,Proof,Classical,2023,57.71,1344.69,4328.7,2.97,Free,93.61,7.23
Indonesia,SZA,SOS,K-pop,2023,12.62,4584.85,14167.53,3.73,Free,191.51,19.65
Sweden,Karol G,MAÑANA SERÁ BONITO,Classical,2020,42.17,2768.71,9528.95,3.58,Free,152.61,27.53
Argentina,Doja Cat,Scarlet,Hip Hop,2022,45.23,3533.64,9386.07,3.63,Free,165.93,36.21
Australia,Ed Sheeran,Autumn Variations,Jazz,2019,17.29,4279.71,14481.17,3.86,Premium,19.1,20.9
India,Dua Lipa,Future Nostalgia,Reggaeton,2022,42.13,2841.36,10278.89,3.85,Premium,144.93,16.44
United States,Karol G,MAÑANA SERÁ BONITO,R&B,2022,8.23,2147.3,8376.12,3.58,Free,186.98,3.69
Russia,Taylor Swift,1989 (Taylor's Version),K-pop,2021,18.82,720.37,2725.2,3.96,Premium,75.52,35.76
Sweden,Doja Cat,Scarlet,EDM,2021,8.94,4822.51,20491.36,2.77,Premium,24.61,39.72
Spain,Ariana Grande,Eternal Sunshine,Reggaeton,2023,97.89,4182.37,16781.17,4.46,Premium,135.03,22.23
South Africa,BLACKPINK,BORN PINK,R&B,2019,46.6,817.85,2352.92,4.25,Free,7.41,26.75
Argentina,Post Malone,Austin,Pop,2019,21.4,549.44,1410.5,3.7,Free,49.7,2.73
Sweden,The Weeknd,After Hours,Jazz,2019,75.68,3891.51,10819.45,4.49,Free,163.34,29.53
Japan,Ed Sheeran,Autumn Variations,Classical,2023,82.02,1222.67,5199.42,4.47,Free,83.3,11.73
South Africa,Ed Sheeran,Autumn Variations,Reggaeton,2023,68.2,2801.46,7266.34,3.19,Premium,157.38,13.43
Netherlands,BLACKPINK,BORN PINK,Reggaeton,2020,38.27,3784.36,13044.83,4.2,Premium,171.65,6.63
Sweden,SZA,SOS,Pop,2022,41.86,2111.71,7517.65,3.28,Premium,41.46,26.22
Sweden,Doja Cat,Scarlet,Indie,2018,54.03,4155.56,10817.23,3.25,Free,174.85,8.34
Turkey,Karol G,MAÑANA SERÁ BONITO,Jazz,2019,48.46,4353.9,13784.14,4.41,Free,43.15,8.41
Germany,Karol G,MAÑANA SERÁ BONITO,Rock,2019,69.87,3533.65,11637.24,2.98,Premium,155.33,15.85
South Africa,Billie Eilish,Happier Than Ever,Indie,2020,26.89,2588.44,9045.44,2.7,Premium,152.56,13.49
Australia,Olivia Rodrigo,Guts,Indie,2021,5.53,4327.22,17233.17,2.53,Premium,59.74,8.65
France,BLACKPINK,BORN PINK,Classical,2019,50.43,3290.31,12732.49,3.01,Premium,193.34,26.03
Russia,Dua Lipa,Future Nostalgia,Reggaeton,2023,79.7,887.87,3498.76,3.48,Free,105.26,33.72
Brazil,Doja Cat,Scarlet,Pop,2018,41.83,4220.6,12505.08,3.91,Free,44.53,18.78
India,Ed Sheeran,Autumn Variations,Classical,2021,66.27,127.87,455.78,3.32,Free,106.35,11.71
South Korea,Taylor Swift,1989 (Taylor's Version),Jazz,2023,67.73,4040.53,17453.26,2.71,Free,105.35,10.4
Argentina,Ariana Grande,Eternal Sunshine,K-pop,2020,27.47,2014.64,6539.73,3.31,Free,198.06,9.81
Brazil,Billie Eilish,Happier Than Ever,Pop,2018,41.12,1916.99,6617.47,3.77,Free,17.45,33.97
Japan,Ed Sheeran,Autumn Variations,Hip Hop,2022,92.0,1187.34,5108.58,3.88,Premium,54.95,37.04
Mexico,SZA,SOS,Jazz,2022,66.15,937.8,3939.56,2.53,Free,117.82,30.34
Spain,SZA,SOS,Hip Hop,2020,17.08,1240.34,5171.35,3.28,Premium,77.39,29.85
Brazil,Ariana Grande,Eternal Sunshine,Indie,2018,10.67,1199.11,3180.08,3.71,Premium,193.82,13.73
Mexico,Post Malone,Austin,Rock,2021,23.59,2787.54,9061.89,2.87,Premium,18.05,25.13
France,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2018,27.53,1931.0,7854.88,2.81,Premium,64.02,5.16
United States,BTS,Proof,Rock,2020,76.37,556.05,1487.21,3.36,Premium,21.56,4.5
South Africa,Drake,For All The Dogs,Classical,2022,78.66,4325.4,10920.26,3.33,Free,145.24,22.82
France,Ed Sheeran,Autumn Variations,Jazz,2019,68.85,889.03,2700.73,3.04,Free,13.59,17.95
Netherlands,BTS,Proof,Rock,2018,36.75,4723.9,18620.66,3.49,Free,92.11,6.28
United States,BLACKPINK,BORN PINK,Indie,2022,38.61,4317.88,14596.36,3.36,Free,60.79,24.53
Australia,Dua Lipa,Future Nostalgia,Indie,2019,96.49,4845.19,14937.22,3.89,Premium,193.58,31.5
Japan,BLACKPINK,BORN PINK,K-pop,2021,37.14,4663.73,13522.95,4.49,Free,136.66,22.45
Sweden,Karol G,MAÑANA SERÁ BONITO,R&B,2021,79.97,4164.84,10988.17,4.2,Premium,134.92,6.43
South Korea,The Weeknd,After Hours,K-pop,2023,16.26,2144.48,6978.1,3.4,Premium,116.87,21.84
Netherlands,Ariana Grande,Eternal Sunshine,Pop,2020,70.46,4070.87,15011.9,4.33,Free,154.02,26.65
Italy,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2018,56.76,3242.9,12301.9,4.43,Premium,193.18,17.79
United States,Drake,For All The Dogs,K-pop,2019,51.56,2618.05,9584.78,3.65,Premium,75.45,19.06
Turkey,Karol G,MAÑANA SERÁ BONITO,Jazz,2019,35.15,171.59,464.85,3.33,Free,24.1,37.69
United Kingdom,Olivia Rodrigo,Guts,K-pop,2020,46.08,1073.99,3722.29,3.45,Premium,144.68,18.65
Brazil,BTS,Proof,Pop,2023,12.39,4253.44,16145.8,3.85,Free,186.05,29.88
Indonesia,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Jazz,2019,33.77,2160.53,7397.89,4.1,Free,38.09,26.64
Spain,Taylor Swift,1989 (Taylor's Version),Classical,2019,45.51,2176.29,5460.09,2.93,Premium,150.71,32.54
Brazil,Ed Sheeran,Autumn Variations,Hip Hop,2022,19.51,1663.63,5681.46,3.02,Premium,106.02,25.93
Argentina,BLACKPINK,BORN PINK,Classical,2021,59.11,1772.23,7427.48,3.73,Premium,183.82,24.02
United Kingdom,Olivia Rodrigo,Guts,Hip Hop,2019,31.23,956.07,3716.12,3.52,Premium,119.69,23.42
Netherlands,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Rock,2023,54.2,4599.85,20061.74,2.85,Free,98.44,6.47
Japan,Doja Cat,Scarlet,Rock,2022,6.31,1827.24,4603.12,2.77,Premium,192.8,20.71
Russia,BLACKPINK,BORN PINK,Rock,2021,71.3,2247.07,6369.34,3.63,Free,59.13,11.72
South Africa,BTS,Proof,Reggaeton,2021,57.0,3874.11,13523.07,3.52,Free,54.31,22.18
Italy,Ariana Grande,Eternal Sunshine,Pop,2023,44.7,1131.78,3791.81,3.97,Free,60.24,39.97
Sweden,BTS,Proof,Indie,2018,44.47,4970.09,20135.14,2.97,Premium,172.35,24.8
Netherlands,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2019,78.7,4076.97,16759.94,3.64,Premium,119.77,7.57
South Korea,BTS,Proof,Classical,2020,95.29,2596.35,11165.11,4.13,Free,192.59,31.64
India,BTS,Proof,Reggaeton,2023,86.74,1285.9,5044.32,4.16,Premium,98.4,23.52
Mexico,Billie Eilish,Happier Than Ever,EDM,2021,45.75,3186.46,13575.12,2.69,Premium,139.25,35.22
Sweden,Dua Lipa,Future Nostalgia,Indie,2022,1.24,3881.97,15393.75,3.96,Premium,127.33,28.19
Brazil,Post Malone,Austin,Jazz,2021,22.57,2176.73,6364.11,3.04,Premium,68.21,23.54
Turkey,Doja Cat,Scarlet,Rock,2020,89.52,3823.16,9909.19,3.75,Premium,4.24,37.25
Canada,Dua Lipa,Future Nostalgia,Rock,2018,99.19,2167.61,9735.58,4.32,Premium,32.64,37.38
Mexico,Drake,For All The Dogs,Indie,2020,9.16,3339.32,12682.14,2.6,Premium,145.47,30.45
Netherlands,Billie Eilish,Happier Than Ever,Hip Hop,2023,10.42,1106.43,2938.54,3.69,Premium,2.85,28.13
Germany,Doja Cat,Scarlet,EDM,2023,14.09,400.6,1308.42,3.96,Free,21.54,15.33
South Korea,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,EDM,2019,64.52,3401.83,8970.02,3.63,Free,88.58,29.17
United Kingdom,SZA,SOS,EDM,2022,68.97,4306.81,11513.72,2.7,Free,118.33,15.98
Netherlands,Olivia Rodrigo,Guts,Reggaeton,2019,28.42,467.03,1684.48,3.7,Premium,156.01,27.93
South Korea,The Weeknd,After Hours,Jazz,2022,51.44,3751.83,11597.22,2.61,Free,99.48,5.4
Russia,Billie Eilish,Happier Than Ever,Classical,2018,53.3,4889.6,21874.92,4.37,Free,77.98,33.72
Netherlands,Olivia Rodrigo,Guts,Jazz,2023,18.1,2381.52,10656.67,2.65,Free,3.74,9.41
India,Post Malone,Austin,EDM,2022,29.36,3577.51,14432.46,3.35,Premium,17.4,21.93
Argentina,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,K-pop,2018,31.68,2580.96,7501.29,4.12,Premium,78.76,25.74
Brazil,BTS,Proof,EDM,2023,95.39,1231.26,3680.19,4.35,Free,91.22,24.74
South Korea,Billie Eilish,Happier Than Ever,Reggaeton,2018,2.25,729.2,1839.55,3.49,Premium,105.08,31.54
Mexico,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Indie,2019,75.23,4373.63,17345.26,2.74,Free,67.67,17.74
Indonesia,Drake,For All The Dogs,K-pop,2023,97.53,3156.29,11022.7,3.52,Free,100.42,23.11
Italy,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,K-pop,2018,89.53,3386.9,9248.5,3.98,Free,9.76,34.65
France,Taylor Swift,1989 (Taylor's Version),Rock,2020,38.91,792.92,3458.97,4.21,Premium,45.68,10.68
Japan,BTS,Proof,Hip Hop,2022,37.91,2535.1,10910.77,2.86,Free,190.86,3.69
Sweden,Doja Cat,Scarlet,K-pop,2020,33.4,2787.8,7013.93,2.9,Premium,148.18,10.46
Italy,Ed Sheeran,Autumn Variations,Rock,2019,73.51,2755.47,11275.24,2.8,Premium,5.76,22.12
United States,Olivia Rodrigo,Guts,Pop,2023,38.25,3703.51,11536.51,2.91,Free,84.54,38.49
United Kingdom,Karol G,MAÑANA SERÁ BONITO,K-pop,2018,5.35,1195.79,5011.57,3.33,Premium,92.23,30.17
Turkey,Drake,For All The Dogs,Jazz,2019,64.08,2002.04,7375.1,2.62,Free,48.12,11.18
Japan,SZA,SOS,EDM,2023,83.36,1664.95,5670.01,2.97,Free,28.09,31.04
Germany,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Hip Hop,2019,45.51,1604.46,4398.58,3.22,Free,90.93,19.07
Germany,Drake,For All The Dogs,Reggaeton,2023,31.12,3538.29,13115.04,2.93,Premium,30.52,28.74
Italy,BLACKPINK,BORN PINK,Jazz,2018,68.04,1337.83,5995.29,2.56,Premium,171.07,22.68
South Africa,The Weeknd,After Hours,Hip Hop,2021,11.09,3979.36,10915.01,2.62,Free,27.01,33.12
Italy,Billie Eilish,Happier Than Ever,Hip Hop,2022,59.03,4591.27,12166.75,4.49,Free,180.6,18.29
United Kingdom,Drake,For All The Dogs,Indie,2018,5.23,2331.92,6613.27,3.65,Premium,99.73,15.93
Netherlands,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Indie,2019,90.92,1411.16,4786.69,2.8,Free,129.81,20.46
South Africa,Dua Lipa,Future Nostalgia,Pop,2018,28.7,729.32,2114.24,4.27,Free,126.52,32.28
United States,BLACKPINK,BORN PINK,Indie,2021,54.91,2449.16,10593.48,3.5,Premium,54.82,2.02
Argentina,The Weeknd,After Hours,Pop,2020,6.8,4958.08,17645.14,4.03,Free,194.82,4.91
France,BTS,Proof,Jazz,2023,6.53,4982.14,14641.63,4.19,Premium,71.61,33.73
Canada,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,R&B,2022,32.48,3703.62,11916.64,3.68,Premium,189.56,22.98
Turkey,The Weeknd,After Hours,Rock,2022,31.6,2477.66,6641.4,2.97,Free,4.97,19.64
Japan,SZA,SOS,Classical,2019,80.84,1736.76,4958.31,4.1,Premium,12.85,6.76
United Kingdom,Post Malone,Austin,Hip Hop,2022,86.21,4804.77,15601.96,4.38,Premium,117.62,14.13
Japan,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Reggaeton,2023,94.92,3969.62,17550.98,3.8,Free,141.73,22.92
Argentina,Post Malone,Austin,Indie,2019,66.89,4081.55,13292.66,3.97,Premium,26.34,29.42
Turkey,BLACKPINK,BORN PINK,Classical,2018,19.03,1625.17,6691.82,3.72,Free,187.4,6.49
Brazil,The Weeknd,After Hours,Indie,2020,17.62,4432.34,11867.38,3.92,Premium,89.88,11.34
France,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2020,26.41,584.77,1463.42,3.27,Premium,193.85,35.5
Russia,SZA,SOS,EDM,2020,55.06,552.07,1909.6,4.23,Free,33.37,3.87
India,BTS,Proof,Pop,2020,26.85,568.39,1809.54,4.28,Free,146.67,22.33
Brazil,Olivia Rodrigo,Guts,Classical,2022,89.43,3537.3,11894.69,3.81,Premium,32.26,4.95
Australia,The Weeknd,After Hours,EDM,2023,55.86,4631.59,16582.25,3.82,Premium,48.27,2.94
Turkey,Ariana Grande,Eternal Sunshine,Rock,2019,6.4,68.89,184.3,4.15,Premium,40.74,2.0
Canada,Billie Eilish,Happier Than Ever,K-pop,2018,47.88,621.77,2530.45,3.44,Premium,19.14,22.22
Canada,Olivia Rodrigo,Guts,EDM,2020,19.47,270.85,915.33,3.03,Premium,113.29,6.89
Germany,Drake,For All The Dogs,Indie,2022,41.98,3794.46,11212.73,2.62,Premium,163.86,17.33
South Africa,Billie Eilish,Happier Than Ever,Rock,2022,88.28,2407.5,6398.92,4.31,Free,100.92,36.12
Turkey,Billie Eilish,Happier Than Ever,Classical,2019,12.91,3798.08,10808.42,4.47,Free,161.88,5.92
Netherlands,Drake,For All The Dogs,EDM,2019,99.73,3154.77,13149.76,3.02,Free,18.32,22.7
South Africa,Olivia Rodrigo,Guts,K-pop,2022,46.36,4373.66,17814.36,3.75,Premium,23.39,6.84
Turkey,Ed Sheeran,Autumn Variations,Classical,2018,92.57,2835.28,7660.87,3.07,Premium,175.7,11.3
Russia,Ed Sheeran,Autumn Variations,Classical,2021,4.71,1413.3,3939.86,3.72,Premium,8.72,35.69
Japan,Karol G,MAÑANA SERÁ BONITO,R&B,2018,74.83,4608.13,19787.6,2.54,Premium,62.88,33.87
Germany,Doja Cat,Scarlet,R&B,2019,30.75,3731.43,15105.06,3.14,Premium,121.39,4.48
Sweden,The Weeknd,After Hours,EDM,2023,48.96,2606.68,8466.03,2.61,Free,14.06,28.67
Spain,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Jazz,2022,3.87,1004.18,4183.27,4.17,Free,7.58,2.97
Italy,Karol G,MAÑANA SERÁ BONITO,R&B,2020,37.47,2347.88,7733.65,4.35,Free,49.15,20.06
Sweden,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Rock,2022,55.58,1754.03,7323.61,3.02,Free,57.73,16.08
Canada,Doja Cat,Scarlet,Classical,2019,85.85,3254.53,12547.48,3.04,Premium,103.14,34.72
United States,Dua Lipa,Future Nostalgia,Reggaeton,2023,18.15,4014.28,11832.25,3.72,Premium,142.84,28.67
Mexico,BLACKPINK,BORN PINK,EDM,2020,46.44,1130.13,3508.25,3.54,Premium,117.31,1.29
Italy,Ariana Grande,Eternal Sunshine,Classical,2022,28.99,3437.85,11906.91,3.17,Premium,128.48,34.6
Mexico,Billie Eilish,Happier Than Ever,K-pop,2019,15.84,3839.1,16505.73,4.11,Premium,132.45,27.55
United States,Billie Eilish,Happier Than Ever,Rock,2020,26.68,2121.9,6952.51,2.57,Free,69.29,28.82
South Africa,Billie Eilish,Happier Than Ever,Rock,2023,36.49,1535.96,4362.09,3.82,Free,59.46,19.36
Mexico,Karol G,MAÑANA SERÁ BONITO,Jazz,2019,94.75,4502.98,17151.26,2.94,Free,149.1,12.98
Japan,Olivia Rodrigo,Guts,K-pop,2022,30.11,4263.51,14671.05,4.23,Free,94.97,8.59
Germany,Doja Cat,Scarlet,EDM,2022,30.54,317.61,1336.66,2.77,Free,69.19,39.5
Sweden,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Indie,2023,18.86,450.02,1424.43,4.47,Premium,127.27,1.18
Mexico,The Weeknd,After Hours,Reggaeton,2022,76.68,2473.41,9960.76,2.68,Premium,127.06,16.73
Russia,BLACKPINK,BORN PINK,Pop,2018,53.84,3666.76,16134.25,4.28,Free,4.57,1.16
France,The Weeknd,After Hours,Indie,2020,13.76,1948.57,7165.56,2.83,Free,60.34,12.34
Indonesia,Ed Sheeran,Autumn Variations,Jazz,2020,43.93,3449.56,9546.93,4.49,Premium,72.49,8.35
Spain,Taylor Swift,1989 (Taylor's Version),R&B,2019,72.99,699.47,2775.6,3.68,Free,25.51,28.73
India,BLACKPINK,BORN PINK,K-pop,2022,62.69,2989.92,7761.6,2.72,Free,10.6,5.52
Sweden,BLACKPINK,BORN PINK,Hip Hop,2022,26.02,3524.25,10259.06,3.87,Free,60.92,26.8
Indonesia,BTS,Proof,Classical,2022,70.37,2123.19,9123.87,3.52,Free,57.26,31.61
Russia,The Weeknd,After Hours,Classical,2019,78.02,4165.92,18522.68,3.22,Premium,59.77,2.54
Russia,SZA,SOS,R&B,2023,93.38,1686.49,4225.46,3.84,Free,167.21,27.09
United Kingdom,Drake,For All The Dogs,Jazz,2018,72.63,551.39,1660.67,2.96,Premium,53.56,2.95
Canada,Doja Cat,Scarlet,Pop,2020,36.66,3399.99,11396.73,2.73,Free,2.92,6.4
Canada,Olivia Rodrigo,Guts,Indie,2021,95.55,1378.13,5465.85,3.25,Premium,37.39,16.63
Sweden,BTS,Proof,EDM,2023,85.22,4009.5,15226.85,4.09,Free,27.37,29.33
Canada,Drake,For All The Dogs,EDM,2022,48.78,2866.27,9677.46,3.72,Premium,122.66,34.64
United Kingdom,Dua Lipa,Future Nostalgia,Rock,2018,88.87,2231.41,5861.18,3.81,Free,141.21,27.44
Turkey,Karol G,MAÑANA SERÁ BONITO,Classical,2019,97.81,3365.73,10691.58,3.55,Free,87.14,29.34
Russia,Olivia Rodrigo,Guts,EDM,2019,84.06,2813.8,12593.4,2.61,Free,101.61,19.3
Russia,Doja Cat,Scarlet,Reggaeton,2018,75.39,1637.14,5176.29,3.06,Free,110.55,15.77
France,Drake,For All The Dogs,Rock,2021,80.32,2268.09,9555.87,3.39,Free,196.15,30.06
United States,Drake,For All The Dogs,EDM,2021,4.55,2768.04,11492.4,4.08,Premium,178.13,22.93
Sweden,Olivia Rodrigo,Guts,Indie,2018,81.84,4229.37,13381.5,4.03,Premium,143.61,15.17
Sweden,Drake,For All The Dogs,Hip Hop,2023,22.95,1739.72,7236.83,4.43,Premium,109.99,15.58
Germany,Taylor Swift,1989 (Taylor's Version),Reggaeton,2021,14.9,3598.44,14189.07,2.71,Free,38.32,37.28
Spain,The Weeknd,After Hours,Rock,2019,71.96,583.44,1942.24,4.35,Free,154.66,18.57
Turkey,Ariana Grande,Eternal Sunshine,Reggaeton,2021,1.43,3694.26,13323.17,3.37,Premium,184.95,31.46
Canada,Karol G,MAÑANA SERÁ BONITO,Classical,2019,73.32,685.49,2244.85,3.7,Premium,101.32,16.0
Argentina,SZA,SOS,R&B,2020,40.39,1747.15,5395.81,4.11,Free,83.14,28.3
Indonesia,BTS,Proof,Jazz,2020,71.48,4680.78,17623.92,2.9,Premium,137.64,36.93
United Kingdom,Karol G,MAÑANA SERÁ BONITO,Reggaeton,2022,54.71,3202.54,12556.22,4.02,Premium,116.98,37.76
Netherlands,Billie Eilish,Happier Than Ever,Jazz,2020,87.87,2140.81,5406.7,2.71,Premium,29.92,27.14
Australia,BTS,Proof,Reggaeton,2020,68.66,774.82,2033.18,4.07,Free,150.97,2.26
Sweden,Drake,For All The Dogs,Classical,2023,74.21,4330.97,17258.16,3.62,Free,102.67,32.08
South Korea,Karol G,MAÑANA SERÁ BONITO,Pop,2021,39.37,4785.67,21304.11,3.13,Free,3.58,10.8
Argentina,Doja Cat,Scarlet,Rock,2019,91.24,3537.91,13427.31,4.01,Free,155.45,38.61
South Korea,Dua Lipa,Future Nostalgia,Reggaeton,2023,8.37,4814.25,19113.34,2.74,Free,86.27,22.71
United Kingdom,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2020,1.56,2358.34,10317.71,2.58,Premium,119.78,31.17
Argentina,Doja Cat,Scarlet,K-pop,2021,79.2,2773.29,7337.46,3.92,Free,191.44,21.3
Indonesia,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,EDM,2022,54.17,505.13,1486.29,2.93,Premium,66.88,12.45
Argentina,Ariana Grande,Eternal Sunshine,Rock,2022,82.55,4906.61,12352.92,3.84,Premium,48.83,26.05
Argentina,The Weeknd,After Hours,Pop,2023,88.68,1937.79,7930.24,2.73,Premium,108.51,12.03
Indonesia,Doja Cat,Scarlet,Indie,2022,80.48,2255.51,5836.59,4.3,Free,64.74,4.21
Germany,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Jazz,2022,1.73,374.09,1436.76,4.05,Premium,167.3,9.02
Netherlands,Billie Eilish,Happier Than Ever,Hip Hop,2023,68.92,167.58,659.22,2.58,Free,11.8,31.97
South Africa,Drake,For All The Dogs,Classical,2019,91.19,2067.78,7035.11,3.31,Premium,4.36,27.26
South Africa,Taylor Swift,1989 (Taylor's Version),Classical,2018,75.84,2948.76,11505.37,2.65,Free,58.68,27.75
Argentina,Drake,For All The Dogs,K-pop,2021,38.76,4119.51,10552.69,2.81,Free,28.14,16.25
South Africa,BTS,Proof,Reggaeton,2020,68.05,4575.14,18712.48,3.96,Premium,191.52,1.43
South Africa,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Hip Hop,2018,1.5,3003.44,10735.21,4.39,Premium,42.8,29.92
Italy,The Weeknd,After Hours,EDM,2023,85.29,755.15,2165.76,3.73,Premium,39.67,8.07
Turkey,Doja Cat,Scarlet,Pop,2022,46.67,2770.84,8537.8,2.63,Free,40.29,23.64
Japan,Olivia Rodrigo,Guts,Reggaeton,2023,65.89,545.22,2038.59,4.3,Premium,97.69,13.81
South Korea,Karol G,MAÑANA SERÁ BONITO,Classical,2019,56.99,1854.24,5808.72,3.36,Free,63.33,31.64
Netherlands,BTS,Proof,Indie,2019,68.28,1691.24,5851.53,3.39,Premium,97.91,5.24
Argentina,Drake,For All The Dogs,K-pop,2019,89.24,1022.34,4055.71,3.75,Free,178.53,34.13
United States,Doja Cat,Scarlet,Classical,2022,41.11,2970.68,12811.38,3.6,Premium,131.13,6.8
Spain,The Weeknd,After Hours,Classical,2023,85.86,712.71,2496.09,2.68,Premium,100.93,26.84
Argentina,Billie Eilish,Happier Than Ever,Reggaeton,2022,14.9,838.15,3044.76,3.63,Free,147.45,19.86
Italy,Taylor Swift,1989 (Taylor's Version),R&B,2021,23.94,1358.57,4032.29,3.84,Premium,78.23,36.8
India,Taylor Swift,1989 (Taylor's Version),Indie,2018,70.67,2630.8,10942.27,4.17,Premium,116.15,23.24
Spain,Billie Eilish,Happier Than Ever,EDM,2020,59.18,4496.22,11940.5,3.0,Free,103.76,14.76
Italy,Dua Lipa,Future Nostalgia,Rock,2022,1.65,4416.07,14925.42,2.96,Premium,43.09,8.29
Italy,Ed Sheeran,Autumn Variations,Hip Hop,2023,23.8,4065.3,16019.36,3.46,Premium,96.33,24.04
Netherlands,Taylor Swift,1989 (Taylor's Version),R&B,2018,13.66,2982.12,8258.83,3.53,Free,12.13,11.07
Canada,Ariana Grande,Eternal Sunshine,EDM,2022,96.96,3206.23,13648.98,3.96,Premium,189.5,9.45
Argentina,Dua Lipa,Future Nostalgia,Rock,2019,22.72,2083.3,5802.87,3.67,Free,125.02,20.92
Canada,Karol G,MAÑANA SERÁ BONITO,Indie,2021,60.06,390.77,1272.51,2.76,Free,41.27,34.52
Indonesia,Billie Eilish,Happier Than Ever,EDM,2019,60.95,928.24,3994.42,3.7,Free,19.54,26.72
Argentina,Ariana Grande,Eternal Sunshine,Pop,2023,65.27,2634.12,8536.54,2.59,Premium,46.67,32.29
Spain,Olivia Rodrigo,Guts,Classical,2023,90.88,4194.09,15317.83,3.35,Premium,95.95,10.07
Brazil,BTS,Proof,Classical,2022,41.46,985.65,3862.07,4.08,Free,104.43,15.63
Australia,Karol G,MAÑANA SERÁ BONITO,Indie,2021,36.86,816.15,3103.94,3.01,Premium,113.37,24.86
Spain,Post Malone,Austin,R&B,2021,55.66,2809.94,8029.23,3.62,Premium,51.5,12.96
Italy,Post Malone,Austin,EDM,2023,14.67,4325.96,11845.22,2.96,Free,20.96,20.83
Japan,Post Malone,Austin,Jazz,2022,70.01,3548.61,10012.32,4.43,Free,161.07,33.11
Russia,SZA,SOS,Classical,2021,9.73,1352.31,4383.74,3.72,Premium,186.21,16.63
Indonesia,BTS,Proof,Classical,2018,94.63,4110.13,15538.69,3.38,Free,170.26,37.3
Indonesia,BTS,Proof,R&B,2018,78.61,2577.21,10043.13,3.73,Free,72.59,26.55
Canada,Drake,For All The Dogs,K-pop,2021,35.96,2005.96,7366.21,3.54,Free,183.92,22.43
South Africa,SZA,SOS,Classical,2020,35.4,4086.8,12066.65,4.43,Premium,186.01,23.42
Mexico,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,EDM,2022,11.54,408.31,1261.07,4.39,Premium,175.35,32.71
Turkey,BTS,Proof,Rock,2021,56.75,3861.34,15503.07,4.42,Premium,136.64,35.96
United States,Dua Lipa,Future Nostalgia,Hip Hop,2020,7.69,3186.63,14302.86,3.85,Free,160.23,17.08
Italy,Ariana Grande,Eternal Sunshine,Jazz,2018,70.38,1353.58,4161.69,3.3,Premium,16.13,37.32
Russia,Olivia Rodrigo,Guts,Indie,2019,89.54,1381.93,6072.53,3.87,Free,100.3,8.79
France,Doja Cat,Scarlet,K-pop,2019,23.69,4182.96,17454.11,3.21,Free,24.86,4.06
Russia,Ed Sheeran,Autumn Variations,Pop,2022,95.84,4247.65,13772.55,3.13,Premium,98.67,39.39
Indonesia,BTS,Proof,EDM,2019,75.27,684.82,2432.12,3.35,Free,100.99,16.35
Canada,Dua Lipa,Future Nostalgia,Hip Hop,2023,52.3,1612.47,4058.32,3.85,Premium,116.62,13.69
Argentina,Doja Cat,Scarlet,K-pop,2019,55.31,1223.84,4213.3,3.73,Premium,37.6,17.53
Netherlands,Karol G,MAÑANA SERÁ BONITO,Indie,2020,85.58,1434.17,4101.41,2.76,Free,163.02,29.11
France,Ariana Grande,Eternal Sunshine,EDM,2021,20.41,4010.19,15948.86,3.45,Free,36.14,20.48
Indonesia,Ariana Grande,Eternal Sunshine,Indie,2021,30.7,2832.59,10298.36,3.3,Free,12.95,32.74
Russia,Doja Cat,Scarlet,Hip Hop,2021,74.71,1335.86,4302.29,3.61,Premium,69.48,17.06
Italy,Doja Cat,Scarlet,Classical,2019,58.11,3266.83,11685.05,4.46,Premium,71.67,27.25
Russia,Post Malone,Austin,Rock,2018,38.73,1468.29,5525.8,2.79,Free,128.48,37.21
Netherlands,Billie Eilish,Happier Than Ever,Classical,2022,41.07,4540.01,12068.36,3.19,Premium,64.06,12.36
Mexico,Ed Sheeran,Autumn Variations,EDM,2020,88.88,3915.82,17141.66,4.0,Premium,83.38,8.17
United States,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,R&B,2023,25.91,3732.18,14926.78,2.92,Premium,21.5,3.49
Russia,Ariana Grande,Eternal Sunshine,Pop,2018,77.32,2643.71,11875.62,2.71,Free,17.78,37.33
Spain,BTS,Proof,R&B,2019,74.02,2243.64,6176.34,3.55,Free,6.69,26.88
Japan,Doja Cat,Scarlet,Rock,2021,97.52,2725.89,8299.87,3.39,Free,118.58,18.81
Turkey,BLACKPINK,BORN PINK,Jazz,2023,64.31,1582.82,5056.06,3.58,Free,88.93,15.27
Mexico,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,K-pop,2018,1.01,4086.13,17144.96,3.19,Premium,107.48,27.82
Russia,Post Malone,Austin,Rock,2020,1.9,2180.65,6729.15,2.96,Free,110.09,8.35
South Africa,BLACKPINK,BORN PINK,EDM,2019,17.16,3698.73,12129.79,3.26,Premium,16.76,25.39
Indonesia,Post Malone,Austin,Classical,2023,68.78,1459.15,5815.96,4.12,Premium,38.41,3.67
United Kingdom,BTS,Proof,Hip Hop,2023,46.08,2291.2,8937.85,3.48,Premium,4.86,2.94
South Africa,Taylor Swift,1989 (Taylor's Version),Reggaeton,2018,28.93,668.94,2258.9,2.52,Free,30.99,20.25
Japan,BLACKPINK,BORN PINK,K-pop,2021,99.8,2345.24,9575.26,3.16,Free,12.15,31.25
Brazil,Ariana Grande,Eternal Sunshine,Rock,2019,20.03,4215.62,17429.49,4.16,Free,194.95,28.87
Spain,Post Malone,Austin,Rock,2019,74.02,215.88,738.67,4.04,Free,95.09,27.58
South Korea,SZA,SOS,Indie,2019,63.29,258.82,1132.3,3.54,Premium,96.76,12.65
Italy,SZA,SOS,Pop,2023,22.56,609.0,2293.38,3.15,Free,159.08,23.8
Spain,Post Malone,Austin,R&B,2018,96.91,2926.33,11358.56,3.88,Free,74.91,4.49
Canada,Dua Lipa,Future Nostalgia,Hip Hop,2023,62.25,4657.7,20931.45,3.75,Free,71.75,7.0
South Africa,Post Malone,Austin,Hip Hop,2019,49.3,1617.86,5851.32,3.79,Premium,161.3,18.11
Australia,Taylor Swift,1989 (Taylor's Version),EDM,2020,72.72,1290.95,3329.33,3.91,Premium,109.0,20.11
Turkey,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Jazz,2020,33.04,2368.55,10031.58,3.7,Free,14.71,7.05
South Korea,Doja Cat,Scarlet,K-pop,2022,37.34,53.56,202.25,3.26,Free,176.7,25.17
Italy,Post Malone,Austin,Classical,2019,32.75,363.54,1612.05,4.14,Free,105.29,20.4
South Africa,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Classical,2020,32.94,3222.47,8768.11,3.55,Free,9.71,37.57
Canada,Doja Cat,Scarlet,Pop,2019,11.6,998.5,2559.79,3.78,Premium,131.93,21.51
Turkey,BTS,Proof,Pop,2020,22.85,3603.33,9102.63,4.34,Premium,185.75,33.45
Sweden,Post Malone,Austin,Pop,2020,56.24,4694.31,15641.0,3.24,Free,164.9,11.37
India,Karol G,MAÑANA SERÁ BONITO,Hip Hop,2020,8.72,1118.71,3959.08,2.7,Free,106.8,8.39
Indonesia,Billie Eilish,Happier Than Ever,R&B,2022,62.91,935.54,3740.65,3.33,Free,153.49,23.49
Sweden,Karol G,MAÑANA SERÁ BONITO,EDM,2018,17.51,942.96,3114.7,3.18,Free,107.25,24.4
Italy,SZA,SOS,Indie,2022,99.15,1657.04,5374.51,4.03,Premium,165.4,13.61
France,Ed Sheeran,Autumn Variations,Jazz,2019,38.13,2773.68,11064.64,3.22,Premium,90.05,16.49
India,BTS,Proof,Classical,2018,52.24,4967.39,15417.21,3.1,Free,43.75,13.28
Mexico,SZA,SOS,Jazz,2022,56.08,4633.32,13016.99,2.58,Premium,32.07,11.33
Turkey,The Weeknd,After Hours,R&B,2020,81.3,504.93,1666.07,4.34,Free,144.99,31.92
Canada,Dua Lipa,Future Nostalgia,Classical,2018,59.93,1536.95,6088.75,3.65,Free,156.24,36.95
Japan,Olivia Rodrigo,Guts,EDM,2021,93.09,646.68,2613.09,4.0,Free,127.14,25.66
India,BTS,Proof,Jazz,2018,32.61,2846.32,8976.33,3.9,Free,11.05,29.53
Spain,Dua Lipa,Future Nostalgia,Classical,2022,50.97,1149.32,3539.41,3.29,Free,67.9,19.56
India,Ariana Grande,Eternal Sunshine,EDM,2020,9.42,2534.02,10256.83,2.76,Free,96.7,8.73
Spain,Billie Eilish,Happier Than Ever,Classical,2019,56.56,4985.54,17691.17,2.98,Premium,155.58,13.61
Turkey,Drake,For All The Dogs,Hip Hop,2023,41.94,1858.07,5353.06,3.19,Free,154.17,7.6
Italy,Ed Sheeran,Autumn Variations,Rock,2022,15.44,272.14,1125.66,2.9,Premium,32.04,29.41
Brazil,Drake,For All The Dogs,Pop,2019,94.95,4637.31,19650.62,4.14,Free,69.31,32.37
South Korea,Dua Lipa,Future Nostalgia,Rock,2018,33.86,3713.06,10856.06,3.59,Premium,110.21,25.3
United Kingdom,Karol G,MAÑANA SERÁ BONITO,Pop,2021,58.72,3334.47,8626.15,2.84,Premium,40.94,28.16
Mexico,Taylor Swift,1989 (Taylor's Version),Rock,2023,94.57,379.66,1450.58,3.83,Premium,172.99,1.74
Spain,The Weeknd,After Hours,EDM,2022,97.68,543.04,1700.21,4.23,Free,38.1,20.53
Sweden,Ariana Grande,Eternal Sunshine,Pop,2018,25.49,2670.61,8458.19,3.29,Free,4.66,27.69
Italy,Billie Eilish,Happier Than Ever,K-pop,2019,99.6,4894.01,14935.33,2.62,Premium,175.86,35.73
United States,Ariana Grande,Eternal Sunshine,K-pop,2019,16.02,4491.02,17128.14,2.68,Premium,104.62,27.44
France,BLACKPINK,BORN PINK,R&B,2022,16.12,4854.16,20967.4,3.16,Free,42.14,6.4
South Africa,Billie Eilish,Happier Than Ever,R&B,2019,31.59,3540.43,12560.07,2.77,Free,131.59,23.03
Canada,Olivia Rodrigo,Guts,Hip Hop,2022,53.76,3611.23,10357.98,4.18,Free,145.69,30.85
Netherlands,BLACKPINK,BORN PINK,K-pop,2021,74.82,4117.41,15537.85,3.98,Free,156.04,5.16
Canada,Taylor Swift,1989 (Taylor's Version),Classical,2022,27.42,2856.86,8461.51,2.96,Free,72.49,27.84
Russia,Bad Bunny,Nadie Sabe Lo Que Va a Pasar Mañana,Jazz,2022,47.41,3265.36,9364.9,3.27,Premium,28.37,8.54
India,BLACKPINK,BORN PINK,Pop,2020,95.07,1151.64,4425.38,2.91,Free,14.16,37.16
Sweden,Doja Cat,Scarlet,Classical,2021,69.1,4340.54,18556.56,3.36,Free,121.98,33.15
Japan,BLACKPINK,BORN PINK,Classical,2023,57.62,2703.99,10228.62,3.91,Free,104.61,18.61
India,SZA,SOS,R&B,2022,54.25,4919.96,12686.13,3.27,Free,38.78,18.14
South Korea,Post Malone,Austin,K-pop,2021,17.48,1507.38,6539.11,3.88,Free,93.25,26.2
Brazil,Karol G,MAÑANA SERÁ BONITO,Jazz,2018,18.8,2947.97,12642.83,3.59,Premium,83.3,18.58
Canada,Dua Lipa,Future Nostalgia,Classical,2023,89.68,4418.61,11843.46,3.15,Free,143.96,5.82
Germany,Karol G,MAÑANA SERÁ BONITO,Rock,2023,36.93,2642.9,8637.46,4.08,Free,76.36,15.84
Canada,SZA,SOS,Indie,2022,87.26,4320.23,12201.4,2.79,Free,84.5,13.07
Sweden,BTS,Proof,Reggaeton,2018,89.96,4804.15,12044.32,4.03,Free,92.27,34.36
lobal_Streaming_Data.csv…]()

