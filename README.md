<h1>Python Visualisation</h1>

<h2>Business Problem</h2>
Hass Avocado, a company based in Mexico, produces a variety of avocados sold in the United States. They have been very successful in recent years and want to expand. Therefore, they evaluate the current business and consider expanding their existing Avocado farms to grow avocados in other regions.
<br />

<h2>Data Understanding</h2>
- Data is taken directly from retailers’ cash registers based on actual retail sales of Hass avocados </br>
- Data represents weekly retail scanner data for National retail volume-units and avocado prices from April 2015 to March 2018 </br>
- Average Price in the table reflects the price per unit (per avocado), even if multiple units (avocados) are sold in bags </br>
- Product Lookup codes (PLU’s) in the table are for Hass avocados only, not for other products </br>

<h2> Data description </h2>
<p align="center">
<img src="https://i.imgur.com/LpJCzUD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Correlation between bag sizes, types with the volume:</br>
- Observation 1: there is a positive correlation between PLUs, of which the correlation between 4046 & 4225 is the strongest (0.93)<br/>
- Observation 2: there is a positive correlation between the 3 packaging types (bags), of which small & large are the strongest (0.90)<br/>
<img src="https://i.imgur.com/rfNhk4a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Data Visualisation</h2>
<p align="center">
Average price: </br>
<img src="https://i.imgur.com/zHpWOAv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Average price of top 10 regions  <br/>
<img src="https://i.imgur.com/IRkjFWk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Total volume: <br/>
<img src="https://i.imgur.com/pw7UzYZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sales volume by region and type:  <br/>
<img src="https://i.imgur.com/A4tfmH2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Heatmap showing relationship of bag sizes and type:  <br/>
<img src="https://i.imgur.com/Nl0SMjV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2> Business Recommendations </h2>

- Focus on Organic Avocados<br/>

  - They have a higher average selling price across all markets <br/>
  - Even in lower-priced regions, organic maintains a premium <br/>

- Target High-Price Regions <br/>

  - Examples: Albany, Baltimore/Washington, Boston, Hartford/Springfield — all show organic prices above $1.70 </br>
  - These regions can yield better margins </br>

- Consider Seasonal Pricing Strategy </br>
    - Use Month and DayOfYear to identify high-demand months where prices peak for organic avocados, then ramp up supply in those months </br>
<!--

 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
