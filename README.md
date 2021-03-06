Python | Jupyter Notebook | Classification
# Investigating Buying Patterns
 
<b>Objective:</b> Explore customer transaction data, from recent online and in-store sales, and see if you can infer any insights about customer purchasing behavior.<br><br>
The following questions should be addressed: <br>
<ul>
	<li>Do customers in different regions spend more on purchases?</li>
 	<li>Are in-store customers older than online customers?</li>
	<li>What age spends the most money on purchases?</li>
  <li>Which customers are more likely to purchase online?</li>
</ul>

## Code & Resources

<b>Python Version</b>: 3.7 <br>
<b>Packages:</b> pandas, numpy, sklearn, matplotlib, seaborn, pandas_profiling <br>
<b>Supervised learning approach:</b> Classification <br><br>
	

<b>Data Composition:</b> Dataset was comprised of $66M worth (or 80,000 rows) of transactional data containing the following 5 attributes. 
<ul>
	<li>Type of Purchase (Online or In-Store)</li>
 	<li>Amount of Purchase ($5 - $3000)</li>
	<li>Number of Items Purchased (1 - 8 items)</li>
  <li>Customer Age (18 - 85 years old)</li>
 	<li>Region of Purchase (North, South, East, West)</li>
</ul>

## <b>Conclusion:</b> <em><b> (comprehensive conclusion attached as a <a href="https://github.com/MLSpreitzer/Customer-Buying-Patterns-and-Demographics/blob/main/Bike%20Rental%20-%20Report.pptx" target="_blank">powerpoint.</a>)</em></b>
<ul>
	<li>Customers in the Western Region spend the most per purchase and account for $33M (or 50%) of total sales.</li>
	<li>The Southern Region had nearly 20,000 transactions under $500 and only 34 transactions over $500.</li>
	<li>Regardless of the number of items purchased, the average cost per transaction didn’t waver.</li>
  <li>Customers under 62 years old account for 93% of total sales.</li>
  <li>Customers under 40 years old spend the most per purchase.</li>
</ul>
<b>Northern Region:</b><ul>
	<li>Average age is 43.</li>
	<li>Shops 100% in-store.</li>
	<li>Spends $745 on average per transaction.</li>
</ul>
<b>Southern Region:</b>
<ul>
	<li>Oldest region - average age is 56.</li>
	<li>Shops 100% online</li>
	<li>Spends less than other regions with $252 average per transaction. </li>
</ul>
<b>Eastern Region:</b>
<ul>
	<li>Average age is 45.</li>
	<li>Shops 61% online & 39% in-store.</li>
	<li>Spends $918 on average per transaction.</li>
</ul>
<b>Western Region:</b>
<ul>
	<li>Youngest region - average age is 38.</li>
	<li>Shops 50% online & 50% in store.</li>
	<li>Spends most than other region with $1,284 average per transaction.</li>
</ul>
<br>
<b>Business Recommendations:</b><br> <br>
<ul>
  <li>Focus marketing efforts in Northern & Southern region to increase sales. </li>
  <li>Run promotional sales for higher-priced products in the South Region.</li>
  <li>The Southern Region shops 100% online, spends the least and is the oldest. If there is a brick & mortar store in this region, the recommendation would be to close the store to reduce expenses. Alternatively, opening a brick & mortar store, if there is not one, could bring in more profits.</li>
</ul>
<br>
<br>

<b>Future Data Mining Considerations:</b><br>

<ul>
  <li>Researching the Southern Region to understand local consumer base and existing business assets to determine if future assets should be established or not.</li>
  <li>Capture the date of the transaction to determine seasonality/predictability of purchases.</li>
  <li>Capture transaction time to determine optimal hours of operation for a store and aid with proper staffing of the store.</li>
  <li>Gather additional customer data to track customer retention.</li>
  <li>With customer retention data, better project and obtain sales goals.</li> 
  <li>Collect product information to understand what items are being purchased in-store vs. online.</li>
  <li>Collect gender information to better understand customer demographics.</li>
 </ul>
<br>
