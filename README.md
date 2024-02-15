# World Oldest Businesses
In this project, we analyze world oldest businesses that are still being today, almost in every country. An important part of business is planning for the future and ensuring that the company survives changing market conditions. Some businesses do this really well and last for hundreds of years.
![WorldOldestBusinesses](https://github.com/IoanaMRusu/DataCampSQL---World-Oldest-Businesses/assets/144055123/2423c624-862b-433f-9515-9ae08126c21d)
# Data and Tables
*https://www.BusinessFinancing.co.uk*

This comprehensive research project involved compiling a dataset with information on the founding years, categories, countries, and continents of these venerable establishments. Our analysis is based on three key tables: "categories," "countries," and "businesses." These tables provide insights into the diverse array of businesses that have managed to navigate through centuries of change and evolution.

<h3 id="categories"><code>categories</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>business</code></td>
<td>varchar</td>
<td>Name of the business</td>
</tr>
<tr>
<td style="text-align:left;"><code>year_founded</code></td>
<td>int</td>
<td>Year the business was founded</td>
</tr>
<tr>
<td style="text-align:left;"><code>category_code</code></td>
<td>varchar</td>
<td>Code for the category of the business</td>
</tr>
<tr>
<td style="text-align:left;"><code>country_code</code></td>
<td>char</td>
<td>ISO 3166-1 3-letter country code</td>
</tr>
</tbody>
</table>
<h3 id="reviews"><code>countries</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>country_code</code></td>
<td>varchar</td>
<td>ISO 3166-1 3-letter country code</td>
</tr>
<tr>
<td style="text-align:left;"><code>country</code></td>
<td>varchar</td>
<td>Name of the country</td>
</tr>
<tr>
<td style="text-align:left;"><code>continent</code></td>
<td>varchar</td>
<td>Name of the continent that the country exists in</td>
</tr>
</tbody>
</table>
<h3 id="reviews"><code>categories</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>category_code</code></td>
<td>varchar</td>
<td>Code for the category of the business</td>
</tr>
<tr>
<td style="text-align:left;"><code>category</code></td>
<td>varchar</td>
<td>Description of the business category</td>
</tr>
</tbody>
</table>

# Visualization
