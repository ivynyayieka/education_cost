In this project, I analysed the rising cost of education in Kenya and the low income teachers earn. 

<h2>How I analysed rising cost of education:</h2>
I scraped the [Kenya National Bureau of Statistics](https://www.knbs.or.ke/data-releases/) website to download the PDFs with details of Consumer Price Index every January for the last decade.  
With the results, I scraped the PDFs for the tables inside.
I merged the relevant resulting CSVs, got the percentage rise in the cost of education and assigned 2010 as the base, giving it 100%. 

<h2>How I analysed cost of kindergartens and the cost of universities:</h2>
I researched school fees for a variety of schools across different parts of Nairobi for school fees for PP1 students. I found that they were much higher than the cost of fees at the University of Nairobi. 
To compare like with like, I found out through calling the schools the tuition fees for some of the 20 best ranked primary schools in Nairobi for PP1 students.
The cost of universities is publicly available so I used just the best-ranked university fees cost.

<h2>How I analysed the cost of living</h2>
For this, I scraped the  PDFs of the government food basket statistics for the last decade.
I then made a waterfall chart. 
A further step in the visualisation would be to use the ggplot version in the notebook and make the blackboard image the background. At the moment, the addition of a background image blocks the chart details and the waterfall colours appear permanent. The ggplot version is also difficult to change colours.

<h2>How I compared prices of items</h2>
I collected data via the [Glovo app](https://glovoapp.com/) on the cost of items in Nairobi's most popular supermarkets compared to the cost government statistics assigned them on the KNBS website.

<h2>How I analysed cost of cooking fuel and electricity</h2>
I got the government data for cooking fuel and electricity over the years. I then divided it by data on minimum wage over the years to get the trend. Minimum wage data is from [Trading Economics](https://tradingeconomics.com/kenya/minimum-wages)

<h2>Data sources</h2>
Kenya National Bureau of Statistics

Glovo app

Trading Economics 

Tech: #Python, #R, #Datawrapper, #Canva, #HTML, #CSS

