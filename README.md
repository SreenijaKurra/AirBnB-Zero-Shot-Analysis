# AirBnB-Zero-Shot-Analysis
Clustering Airbnb hosts based on review types, focusing on key words related to cleanliness across NYC's five boroughs. This helps identify why listings get negative feedback and offers suggestions to improve property appearance and guest experience, ultimately boosting bookings and host income.

Zero-shot Text Classification requires no training data and easy to add new input data. It is great for classifying text into well-known categories that aren’t highly specialized or expertise-dependent.

<div align="center"> 
  <img src="https://raw.githubusercontent.com/sreenijakurra/AirBnB-Zero-Shot-Analysis/main/negativekeywords.png" />
</div>



<h2>Data Source</h2>

<p>
The model uses publicly available Airbnb datasets, which include detailed information about listings, availability of bookings, host information, and information about room/property, etc. Key features include:
</p>

<ul>
  <li><strong>Listing Attributes:</strong> Property type, location, pricing, amenities, etc.</li>
  <li><strong>Booking Trends:</strong> Historical availability calendars, minimum and maximum periods of stay, instant availability, etc.</li>
  <li><strong>Reviews Information:</strong> Review score rating, reviews per month, review per quality metrics, etc.</li>
  <li><strong>Host Information:</strong> Host’s identification, host verification, response rate, host’s listings, etc.</li>
</ul>

<br>

<h2>Use Cases</h2>
<p><strong>For Hosts:</strong></p>
<ul>
  <li>Optimize pricing strategies to improve occupancy and revenue.</li>
  <li>Respond effectively to market demand with adaptive pricing recommendations.</li>
</ul>

<p><strong>For Airbnb:</strong></p>
<ul>
  <li>Strengthen platform credibility by offering transparent, data-backed pricing tools.</li>
  <li>Enhance market insights to support hosts in achieving competitive positioning.</li>
</ul>

<p><strong>For Guests:</strong></p>
<ul>
  <li>Experience fair and market-aligned pricing, improving the overall booking experience.</li>
</ul>

<br>

<h2>Insights from Model Results</h2>

<p>
Our analysis revealed that positive reviews significantly outnumber negative reviews. However, in the practical realm of machine learning model deployment, even a 1% change can impact business performance. For Airbnb listings, a single negative review can dramatically reduce a property's visibility compared to other highly-rated listings. Our research focuses on the broader context of Airbnb listings, examining neighborhoods, keyword patterns, and overall review scores, rather than drilling down into the number of reviews per individual property.
</p>

<p>
The scatter plot provides critical insights into review scores across different Airbnb hosts. The data strongly supports our hypothesis about cleanliness as a key factor in improving Airbnb revenue potential. By analyzing the x-axis of negative keywords against the y-axis of average review scores, several interesting patterns emerge.
</p>

<p>
Notably, check-in convenience received the highest ratings. Conversely, average negative review scores declined most significantly in areas such as communication, accuracy, location, overall rating, and cleanliness. The graph particularly highlights cleanliness as a critical factor driving lower average review scores. Our findings suggest that a targeted approach to improving cleanliness could enhance overall review ratings for Airbnb properties across New York City, leading to high visibility, attractiveness to potential guests, and ultimately, improved revenue for hosts.
</p>


<p align="center">
  <img src="https://raw.githubusercontent.com/sreenijakurra/AirBnB-Zero-Shot-Analysis/main/avgreviewscores.png" alt="Average Review Scores" width="300"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/sreenijakurra/AirBnB-Zero-Shot-Analysis/main/avgreviewscoresscale.png" alt="Scaled Average Review Scores" width="200"/>
</p>


<p>
Our analysis reveals a distinctive geographic pattern of negative keyword distribution across NYC boroughs. Queens and Brooklyn emerge as the boroughs with the highest concentration of negative keywords, indicating potential areas of concern for Airbnb hosts and property managers. Manhattan and the Bronx follow closely, ranking as the second most problematic neighborhoods in terms of negative review terminology. Staten Island stands out as the borough with the least occurrence of negative keywords, suggesting relatively more satisfactory guest experiences in this area.
</p>

<h2> Conclusion </h2>
<h3>Geographic and Economic Disparities in Airbnb Reviews</h3>

<p>
The disparities in Airbnb review patterns extend beyond mere keyword occurrences, deeply rooted in complex geographical and economic factors. Staten Island's unique characteristics significantly influence its Airbnb market dynamics. The borough's relative isolation and limited transportation infrastructure create substantial barriers for both hosts and potential guests.
</p>

<p>
Airbnb hosts in Staten Island predominantly operate small to mid-sized properties with constrained financial resources. This economic limitation significantly restricts their ability to invest in property improvements or enhance their ratings. Moreover, the low transaction rate in the borough makes any potential improvements economically unviable, rendering extensive interventions both impractical and unprofitable.
</p>

<p>
Given these considerations, our project will strategically concentrate on four key boroughs: <strong>Queens, Brooklyn, Bronx, and Manhattan</strong>. These areas demonstrate more dynamic and economically significant Airbnb markets with higher potential for meaningful impact. Of particular interest are <strong>Queens</strong> and <strong>Brooklyn</strong>, which exhibit the highest concentrations of negative reviews. Notably, <em>"Littered"</em> emerges as the most frequently commented negative keyword in these regions, highlighting a critical area of concern for property hosts and potential guests.
</p>

<p>
By focusing on these boroughs, we aim to develop targeted strategies that can meaningfully improve Airbnb hosting experiences, property standards, and ultimately, guest satisfaction.
</p>
