# Radar STATS

[![Report Update](https://github.com/pvieito/Radar-STATS/workflows/Report%20Update/badge.svg?event=schedule)](https://github.com/pvieito/Radar-STATS/blob/master/Notebooks/RadarCOVID-Report/Current/RadarCOVID-Report.ipynb)

**Radar STATS** (_née RadarCOVID-STATS_) is an open-source project developed to monitor and report hourly statistics about Spain’s “Radar COVID” Exposure Notification app – Created by [@pvieito](https://twitter.com/pvieito)

## Links

- [Last Results](#last-results)
- [Documentation](#documentation)
- [Contributions](#contributions)
- [Press References](#press-references)
- [Related Links](#related-links)
- [Archived Reports](https://github.com/pvieito/Radar-STATS/tree/master/Notebooks/RadarCOVID-Report)
- [TEK Dumps](https://github.com/pvieito/Radar-STATS/tree/master/Data/TEKs)
- [JSON Results](https://raw.githubusercontent.com/pvieito/RadarCOVID-STATS/master/Data/Resources/Current/RadarCOVID-Report-Summary-Results.json)
- [Twitter Bot](https://twitter.com/radarcovidstats)

## Last Results

- [Report 2021-07-07@03](https://github.com/pvieito/Radar-STATS/blob/master/Notebooks/RadarCOVID-Report/Current/RadarCOVID-Report.ipynb)

### Daily Summary Plots

![RadarCOVID-Report-Summary-Plot](https://github.com/pvieito/Radar-STATS/raw/master/Data/Resources/Current/RadarCOVID-Report-Summary-Plots.png)

### Daily Summary Table

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>COVID-19 Cases (Source Countries)</th>
      <th>Shared TEKs by Generation Date (Source Countries)</th>
      <th>Shared TEKs by Upload Date (Source Countries)</th>
      <th>Shared TEKs Uploaded on Generation Date (Source Countries)</th>
      <th>Shared Diagnoses (Source Countries – Estimation)</th>
      <th>TEKs Uploaded per Shared Diagnosis (Source Countries)</th>
      <th>Usage Ratio (Source Countries)</th>
      <th>COVID-19 Cases (Spain)</th>
      <th>App Downloads (Spain – Official)</th>
      <th>Shared Diagnoses (Spain – Official)</th>
      <th>Usage Ratio (Spain)</th>
    </tr>
    <tr>
      <th>Sample Date (UTC)</th>
      <th>Source Countries</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2021-07-07</th>
      <th>ES</th>
      <td>32607</td>
      <td></td>
      <td>30</td>
      <td></td>
      <td>22</td>
      <td>1.36</td>
      <td>0.07%</td>
      <td>32607</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-06</th>
      <th>ES</th>
      <td>32607</td>
      <td>252</td>
      <td>694</td>
      <td>230</td>
      <td>230</td>
      <td>3.02</td>
      <td>0.71%</td>
      <td>32607</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-05</th>
      <th>ES</th>
      <td>10548</td>
      <td>250</td>
      <td>435</td>
      <td>143</td>
      <td>143</td>
      <td>3.04</td>
      <td>1.36%</td>
      <td>10548</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-04</th>
      <th>ES</th>
      <td>7344</td>
      <td>273</td>
      <td>347</td>
      <td>108</td>
      <td>108</td>
      <td>3.21</td>
      <td>1.47%</td>
      <td>7344</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-03</th>
      <th>ES</th>
      <td>7344</td>
      <td>293</td>
      <td>295</td>
      <td>96</td>
      <td>96</td>
      <td>3.07</td>
      <td>1.31%</td>
      <td>7344</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-02</th>
      <th>ES</th>
      <td>7344</td>
      <td>314</td>
      <td>304</td>
      <td>103</td>
      <td>103</td>
      <td>2.95</td>
      <td>1.40%</td>
      <td>7344</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-07-01</th>
      <th>ES</th>
      <td>6252</td>
      <td>326</td>
      <td>336</td>
      <td>108</td>
      <td>108</td>
      <td>3.11</td>
      <td>1.73%</td>
      <td>6252</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-06-30</th>
      <th>ES</th>
      <td>5133</td>
      <td>338</td>
      <td>376</td>
      <td>104</td>
      <td>104</td>
      <td>3.62</td>
      <td>2.03%</td>
      <td>5133</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-06-29</th>
      <th>ES</th>
      <td>4435</td>
      <td>288</td>
      <td>123</td>
      <td>44</td>
      <td>44</td>
      <td>2.80</td>
      <td>0.99%</td>
      <td>4435</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-06-28</th>
      <th>ES</th>
      <td>3999</td>
      <td>241</td>
      <td>108</td>
      <td>37</td>
      <td>37</td>
      <td>2.92</td>
      <td>0.93%</td>
      <td>3999</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2021-06-27</th>
      <th>ES</th>
      <td>3574</td>
      <td>173</td>
      <td>38</td>
      <td>9</td>
      <td>10</td>
      <td>3.80</td>
      <td>0.28%</td>
      <td>3574</td>
      <td>3335</td>
      <td>37</td>
      <td>1.04%</td>
    </tr>
    <tr>
      <th>2021-06-26</th>
      <th>ES</th>
      <td>3574</td>
      <td>122</td>
      <td>129</td>
      <td>31</td>
      <td>31</td>
      <td>4.16</td>
      <td>0.87%</td>
      <td>3574</td>
      <td>3335</td>
      <td>37</td>
      <td>1.04%</td>
    </tr>
    <tr>
      <th>2021-06-25</th>
      <th>ES</th>
      <td>3574</td>
      <td>85</td>
      <td>179</td>
      <td>44</td>
      <td>44</td>
      <td>4.07</td>
      <td>1.23%</td>
      <td>3574</td>
      <td>3335</td>
      <td>37</td>
      <td>1.04%</td>
    </tr>
    <tr>
      <th>2021-06-24</th>
      <th>ES</th>
      <td>3473</td>
      <td>53</td>
      <td>188</td>
      <td>52</td>
      <td>52</td>
      <td>3.62</td>
      <td>1.50%</td>
      <td>3473</td>
      <td>3335</td>
      <td>37</td>
      <td>1.07%</td>
    </tr>
    <tr>
      <th>2021-06-23</th>
      <th>ES</th>
      <td>3429</td>
      <td>29</td>
      <td>112</td>
      <td>35</td>
      <td>35</td>
      <td>3.20</td>
      <td>1.02%</td>
      <td>3429</td>
      <td>3335</td>
      <td>37</td>
      <td>1.08%</td>
    </tr>
    <tr>
      <th>2021-06-22</th>
      <th>ES</th>
      <td>3356</td>
      <td>34</td>
      <td>117</td>
      <td>25</td>
      <td>25</td>
      <td>4.68</td>
      <td>0.74%</td>
      <td>3356</td>
      <td>3335</td>
      <td>37</td>
      <td>1.10%</td>
    </tr>
    <tr>
      <th>2021-06-21</th>
      <th>ES</th>
      <td>3269</td>
      <td>41</td>
      <td>147</td>
      <td>37</td>
      <td>37</td>
      <td>3.97</td>
      <td>1.13%</td>
      <td>3269</td>
      <td>3335</td>
      <td>37</td>
      <td>1.13%</td>
    </tr>
    <tr>
      <th>2021-06-20</th>
      <th>ES</th>
      <td>3406</td>
      <td>47</td>
      <td>75</td>
      <td>17</td>
      <td>17</td>
      <td>4.41</td>
      <td>0.50%</td>
      <td>3406</td>
      <td>3275</td>
      <td>33</td>
      <td>0.97%</td>
    </tr>
    <tr>
      <th>2021-06-19</th>
      <th>ES</th>
      <td>3406</td>
      <td>34</td>
      <td>95</td>
      <td>22</td>
      <td>22</td>
      <td>4.32</td>
      <td>0.65%</td>
      <td>3406</td>
      <td>3275</td>
      <td>33</td>
      <td>0.97%</td>
    </tr>
    <tr>
      <th>2021-06-18</th>
      <th>ES</th>
      <td>3406</td>
      <td>37</td>
      <td>99</td>
      <td>35</td>
      <td>35</td>
      <td>2.83</td>
      <td>1.03%</td>
      <td>3406</td>
      <td>3275</td>
      <td>33</td>
      <td>0.97%</td>
    </tr>
    <tr>
      <th>2021-06-17</th>
      <th>ES</th>
      <td>3396</td>
      <td>44</td>
      <td>118</td>
      <td>43</td>
      <td>43</td>
      <td>2.74</td>
      <td>1.27%</td>
      <td>3396</td>
      <td>3275</td>
      <td>33</td>
      <td>0.97%</td>
    </tr>
    <tr>
      <th>2021-06-16</th>
      <th>ES</th>
      <td>4797</td>
      <td>41</td>
      <td>165</td>
      <td>43</td>
      <td>43</td>
      <td>3.84</td>
      <td>0.90%</td>
      <td>4797</td>
      <td>3275</td>
      <td>33</td>
      <td>0.69%</td>
    </tr>
    <tr>
      <th>2021-06-15</th>
      <th>ES</th>
      <td>4882</td>
      <td>32</td>
      <td>100</td>
      <td>26</td>
      <td>26</td>
      <td>3.85</td>
      <td>0.53%</td>
      <td>4882</td>
      <td>3275</td>
      <td>33</td>
      <td>0.68%</td>
    </tr>
    <tr>
      <th>2021-06-14</th>
      <th>ES</th>
      <td>4892</td>
      <td>36</td>
      <td>94</td>
      <td>30</td>
      <td>30</td>
      <td>3.13</td>
      <td>0.61%</td>
      <td>4892</td>
      <td>3275</td>
      <td>33</td>
      <td>0.67%</td>
    </tr>
    <tr>
      <th>2021-06-13</th>
      <th>ES</th>
      <td>5088</td>
      <td>29</td>
      <td>47</td>
      <td>18</td>
      <td>18</td>
      <td>2.61</td>
      <td>0.35%</td>
      <td>5088</td>
      <td>2983</td>
      <td>44</td>
      <td>0.86%</td>
    </tr>
    <tr>
      <th>2021-06-12</th>
      <th>ES</th>
      <td>5088</td>
      <td>39</td>
      <td>126</td>
      <td>35</td>
      <td>35</td>
      <td>3.60</td>
      <td>0.69%</td>
      <td>5088</td>
      <td>2983</td>
      <td>44</td>
      <td>0.86%</td>
    </tr>
    <tr>
      <th>2021-06-11</th>
      <th>ES</th>
      <td>5088</td>
      <td>36</td>
      <td>199</td>
      <td>58</td>
      <td>58</td>
      <td>3.43</td>
      <td>1.14%</td>
      <td>5088</td>
      <td>2983</td>
      <td>44</td>
      <td>0.86%</td>
    </tr>
    <tr>
      <th>2021-06-10</th>
      <th>ES</th>
      <td>5207</td>
      <td>37</td>
      <td>189</td>
      <td>83</td>
      <td>83</td>
      <td>2.28</td>
      <td>1.59%</td>
      <td>5207</td>
      <td>2983</td>
      <td>44</td>
      <td>0.85%</td>
    </tr>
  </tbody>
</table>

- [Summary Table File](https://github.com/pvieito/Radar-STATS/blob/master/Data/Resources/Current/RadarCOVID-Report-Summary-Table.csv)

### Daily Generation to Upload Period Table

![RadarCOVID-Report-Generation-Upload-Period-Table](https://github.com/pvieito/Radar-STATS/raw/master/Data/Resources/Current/RadarCOVID-Report-Generation-Upload-Period-Table.png)

- [Daily Generation to Upload Period Table File](https://github.com/pvieito/Radar-STATS/blob/master/Data/Resources/Current/RadarCOVID-Report-Generation-Upload-Period-Table.csv)

### Multi-Backend Results

_**NOTE:** These tables include data extracted from different Exposure Notification backends (eg. the `CH` backend data is extracted from the SwissCovid server). You can find the exact backend definitions in the [`exposure_notification_io` module](https://github.com/pvieito/Radar-STATS/blob/master/Modules/ExposureNotification/exposure_notification_io.py)._ 

#### Multi-Backend Summary Table

<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="8" halign="left">Shared TEKs by Generation Date (Source Countries)</th>
    </tr>
    <tr>
      <th>Backend</th>
      <th>CH</th>
      <th>DE</th>
      <th>DE@ES</th>
      <th>EE</th>
      <th>ES</th>
      <th>EU@ES</th>
      <th>IT@ES</th>
      <th>MT</th>
    </tr>
    <tr>
      <th>Sample Date (UTC)</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2021-07-06</th>
      <td>15</td>
      <td>303</td>
      <td>74</td>
      <td>0</td>
      <td>252</td>
      <td>348</td>
      <td>0</td>
      <td>522</td>
    </tr>
    <tr>
      <th>2021-07-05</th>
      <td>26</td>
      <td>973</td>
      <td>134</td>
      <td>1</td>
      <td>250</td>
      <td>1140</td>
      <td>2</td>
      <td>1482</td>
    </tr>
    <tr>
      <th>2021-07-04</th>
      <td>29</td>
      <td>1141</td>
      <td>120</td>
      <td>2</td>
      <td>273</td>
      <td>1462</td>
      <td>4</td>
      <td>1780</td>
    </tr>
    <tr>
      <th>2021-07-03</th>
      <td>30</td>
      <td>1365</td>
      <td>187</td>
      <td>2</td>
      <td>293</td>
      <td>1787</td>
      <td>9</td>
      <td>2105</td>
    </tr>
    <tr>
      <th>2021-07-02</th>
      <td>37</td>
      <td>1540</td>
      <td>258</td>
      <td>3</td>
      <td>314</td>
      <td>2056</td>
      <td>12</td>
      <td>2367</td>
    </tr>
    <tr>
      <th>2021-07-01</th>
      <td>37</td>
      <td>1560</td>
      <td>307</td>
      <td>1</td>
      <td>326</td>
      <td>2261</td>
      <td>17</td>
      <td>2567</td>
    </tr>
    <tr>
      <th>2021-06-30</th>
      <td>33</td>
      <td>1578</td>
      <td>367</td>
      <td>2</td>
      <td>338</td>
      <td>2455</td>
      <td>20</td>
      <td>2749</td>
    </tr>
    <tr>
      <th>2021-06-29</th>
      <td>29</td>
      <td>1573</td>
      <td>430</td>
      <td>2</td>
      <td>288</td>
      <td>2595</td>
      <td>20</td>
      <td>2897</td>
    </tr>
    <tr>
      <th>2021-06-28</th>
      <td>17</td>
      <td>1486</td>
      <td>449</td>
      <td>0</td>
      <td>241</td>
      <td>2677</td>
      <td>27</td>
      <td>2983</td>
    </tr>
    <tr>
      <th>2021-06-27</th>
      <td>17</td>
      <td>1332</td>
      <td>419</td>
      <td>0</td>
      <td>173</td>
      <td>2601</td>
      <td>21</td>
      <td>2910</td>
    </tr>
    <tr>
      <th>2021-06-26</th>
      <td>12</td>
      <td>1350</td>
      <td>442</td>
      <td>0</td>
      <td>122</td>
      <td>2553</td>
      <td>21</td>
      <td>3018</td>
    </tr>
    <tr>
      <th>2021-06-25</th>
      <td>5</td>
      <td>1416</td>
      <td>411</td>
      <td>0</td>
      <td>85</td>
      <td>2384</td>
      <td>17</td>
      <td>3192</td>
    </tr>
    <tr>
      <th>2021-06-24</th>
      <td>5</td>
      <td>1475</td>
      <td>391</td>
      <td>0</td>
      <td>53</td>
      <td>2254</td>
      <td>16</td>
      <td>3377</td>
    </tr>
  </tbody>
</table>

- [Multi-Backend Summary Table File](https://github.com/pvieito/Radar-STATS/blob/master/Data/Resources/Current/RadarCOVID-Report-Multi-Backend-Summary-Table.csv)

#### Multi-Backend Cross-Sharing Summary Table

<table border="1" class="dataframe table-center">
  <thead>
    <tr style="text-align: center;">
      <th></th>
      <th colspan="8" halign="left">Fraction of TEKs in Backend (A) Available in Backend (B)</th>
    </tr>
    <tr style="text-align: center;">
      <th>Backend (A)</th>
      <th>CH</th>
      <th>DE</th>
      <th>DE@ES</th>
      <th>EE</th>
      <th>ES</th>
      <th>EU@ES</th>
      <th>IT@ES</th>
      <th>MT</th>
    </tr>
    <tr style="text-align: center;">
      <th>Backend (B)</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr style="text-align: center;">
      <th>CH</th>
      <td>-</td>
      <td>1.7%</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr style="text-align: center;">
      <th>DE</th>
      <td>99.7%</td>
      <td>-</td>
      <td>100.0%</td>
      <td></td>
      <td>85.0%</td>
      <td>54.3%</td>
      <td></td>
      <td>50.0%</td>
    </tr>
    <tr style="text-align: center;">
      <th>DE@ES</th>
      <td></td>
      <td>23.3%</td>
      <td>-</td>
      <td></td>
      <td></td>
      <td>15.0%</td>
      <td></td>
      <td>12.5%</td>
    </tr>
    <tr style="text-align: center;">
      <th>EE</th>
      <td></td>
      <td></td>
      <td></td>
      <td>-</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr style="text-align: center;">
      <th>ES</th>
      <td></td>
      <td>15.0%</td>
      <td></td>
      <td></td>
      <td>-</td>
      <td>11.3%</td>
      <td></td>
      <td>8.0%</td>
    </tr>
    <tr style="text-align: center;">
      <th>EU@ES</th>
      <td></td>
      <td>84.5%</td>
      <td>100.0%</td>
      <td></td>
      <td>100.0%</td>
      <td>-</td>
      <td>100.0%</td>
      <td>81.7%</td>
    </tr>
    <tr style="text-align: center;">
      <th>IT@ES</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>0.7%</td>
      <td>-</td>
      <td>0.6%</td>
    </tr>
    <tr style="text-align: center;">
      <th>MT</th>
      <td></td>
      <td>93.5%</td>
      <td>100.0%</td>
      <td></td>
      <td>85.0%</td>
      <td>98.3%</td>
      <td>100.0%</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

- [Multi-Backend Cross-Sharing Summary Table File](https://github.com/pvieito/Radar-STATS/blob/master/Data/Resources/Current/RadarCOVID-Report-Multi-Backend-Cross-Sharing-Summary-Table.csv)

## Documentation

### Definitions

- **TEK** (Temporary Exposure Key): A random identifier generated on-device each day used by [Exposure Notification](https://developer.apple.com/documentation/exposurenotification) apps like Radar COVID to detect exposures and share positive diagnoses. When a user has a confirmed case of COVID-19, he can share the TEKs generated on-device from the last 14 days through an Exposure Notification app which will be published on a server like the Radar COVID server. Other devices then download the infected TEKs from the server and check if they have detected them nearby via Bluetooth on the previous 14 days.
- **Source Countries**: Countries with an Exposure Notification app that can share TEKs with the Radar COVID server directly or through the EFGS (see the notes below for more information). Currently the following countries are considered source countries: ES.

### Metrics

- **COVID-19 Cases in Source Countries** (`covid_cases`): Confirmed new COVID-19 cases in applicable source countries estimated with a 7-day rolling average (see the notes below for more information).
- **Shared TEKs by Generation Date** (`shared_teks_by_generation_date`): TEKs published on the Radar COVID server by the date they were generated on-device.
- **Shared TEKs by Upload Date** (`shared_teks_by_upload_date`): TEKs published on the Radar COVID server by the date they were added to the server. Typically this is the date when the user shares the positive diagnosis using the app with the one-time code sent by the Health Authorities or when TEKs from other countries backends are loaded from the EFGS.
- **Shared TEKs Uploaded on Generation Date** (`shared_teks_uploaded_on_generation_date`): TEKs uploaded to the Radar COVID server on the same date they were generated on-device. This metric measures the number of diagnoses shared by devices which already support the new Exposure Notification API version with early TEK release (ie. the current date TEK is released along previous days TEKs), see the notes below for more information.
- **Shared Diagnoses** (`shared_diagnoses`): Estimation of the number of diagnoses shared via Exposure Notification apps published on the Radar COVID server. The estimation is inferred from the maximum number of TEKs uploaded each date that were generated on-device on a unique date, as each device can only upload 1 TEK per generation date.
- **TEKs Uploaded per Shared Diagnosis** (`teks_per_shared_diagnosis`): Estimation of the average number of TEKs uploaded with each shared diagnosis. This number should ideally be around 14 TEKs uploaded per shared diagnosis.
- **Usage Ratio** (`shared_diagnoses_per_covid_case`): Estimation of the fraction of COVID-19 cases in applicable source countries which shared their diagnosis via an Exposure Notification app (see the notes below for more information). Ideally it should be 100% (ie. all confirmed cases sharing their TEKs with an Exposure Notification app).

#### Important Notes

- As Radar COVID is [integrated](https://twitter.com/eu_commission/status/1318152800887558144?s=21) with the [EU Federation Gateway Service (EFGS)](https://github.com/eu-federation-gateway-service/efgs-federation-gateway) project, the server may publish TEKs from multiple source countries. Those EU-wide TEKs are published merged with TEKs shared directly from the Radar COVID app and they cannot be distinguished. To compute a valid usage ratio, we take in account COVID-19 cases from all applicable source countries [integrated with the EFGS](https://ec.europa.eu/info/live-work-travel-eu/health/coronavirus-response/travel-during-coronavirus-pandemic/mobile-contact-tracing-apps-eu-member-states_en), currently the following countries are considered source countries: ES.
- TEKs on the Radar COVID server may also be padded with artificial random TEKs to increase anonymization. Currently there is no known technique to detect such alterations, so metrics dependent on the number of uploaded TEKs (eg. shared diagnoses or usage ratio) may be lower than the estimated.
- Some devices use the [Exposure Notification API version 1](https://developer.apple.com/documentation/bundleresources/information_property_list/enapiversion), which shares the last TEK (ie. the TEK generated the day the diagnosis is shared) a day after it was generated, so two uploads (one with the previous TEKs and another with the last TEK) will take place on different days. This will lead to a duplication on the shared diagnoses metric. This duplication effect will disappear once all devices are using the [new Exposure Notification API version](https://developer.apple.com/documentation/exposurenotification/enmanager/3583725-getdiagnosiskeys) which shares all 14 TEKs at once.

### Data Sources

- **COVID-19 Cases**: [Our World in Data](https://ourworldindata.org/coronavirus)
- **Official Statistics & TEKs**: [Radar COVID API](https://radarcovid.gob.es/)

## Contributions

Contributions to the **Radar STATS** project are welcome, both as [Pull Requests](https://github.com/pvieito/Radar-STATS/pulls) or [Issues](https://github.com/pvieito/Radar-STATS/issues).

Only files on the following directories should be modified as other files are generated automatically by the [Report Update GitHub Action](https://github.com/pvieito/Radar-STATS/blob/master/.github/workflows/report-update.yml):

- `Data/Templates/`
- `Modules/`
- `Notebooks/*/Source/`

The project _entry point_ is a Python notebook located at [`Notebooks/RadarCOVID-Report/Source/RadarCOVID-Report.ipynb`](https://github.com/pvieito/Radar-STATS/blob/master/Notebooks/RadarCOVID-Report/Source/RadarCOVID-Report.ipynb).

## Press References

The **Radar STATS** project has been referenced and featured on multiple news articles:

- [El País](https://elpais.com/tecnologia/2020-09-27/por-que-la-app-radar-covid-apenas-manda-avisos-de-contagio-a-sus-usuarios.html?ssm=TW_CM)
- [Xataka](https://www.xataka.com/aplicaciones/nadie-supo-darme-codigo-caos-radar-covid-codigos-que-no-llegan-notificaciones-retraso-mucho-trabajo-hacer)
- [Genbeta](https://www.genbeta.com/actualidad/bot-publica-estadisticas-nivel-uso-radarcovid-estima-que-casi-1-positivos-sube-sus-datos-a-app)
- [El Independiente](https://www.elindependiente.com/futuro/gadget/2020/09/25/radar-covid-rastrea-menos-del-1-de-los-contagios-que-se-detectan-en-espana/?utm_source=share_buttons&utm_medium=twitter&utm_campaign=social_share2)
- [Business Insider](https://www.businessinsider.es/crean-herramienta-medir-uso-radarcovid-espana-728625?utm_medium=Social&utm_campaign=BI&utm_source=Twitter#Echobox=1601638989)

## Related Links

- [Radar COVID – Website](https://radarcovid.gob.es/)
- [Radar COVID – Project](https://github.com/RadarCOVID)
- [Radar COVID – Statistics](https://radarcovid.gob.es/estadisticas/codigos-introducidos-a-casos-confirmados)
- [DP3T Project](https://github.com/DP-3T)
- [SwissCovid App Monitoring - Swiss Federal Statistical Office](https://www.experimental.bfs.admin.ch/expstat/en/home/innovative-methods/swisscovid-app-monitoring.html)
- [Diagnosis Key Analysis for Corona-Warn-App](https://github.com/micb25/dka/blob/master/README.en.md)
- [Testing Apps for COVID-19 Tracing (TACT) - TEK Survey](https://down.dsg.cs.tcd.ie/tact/tek-counts/)
- [EU Federation Gateway Service (EFGS) Project](https://github.com/eu-federation-gateway-service/efgs-federation-gateway)
- [Mobile Contact Tracing Apps in EU Member States - European Commission](https://ec.europa.eu/info/live-work-travel-eu/health/coronavirus-response/travel-during-coronavirus-pandemic/mobile-contact-tracing-apps-eu-member-states_en)
- [Corona-Warn-App – FAQ – Interoperability Countries](https://www.coronawarn.app/en/faq/#interoperability_countries)
