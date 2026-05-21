<!-- <body align="center" style="background-color: lightblue;"> -->
<body style="
  background-color: lightblue;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
">
	
<div align="center">
<img   width="40%" alt="ApexPlay logo design with glowing effect" src="https://github.com/user-attachments/assets/3be3e981-be3b-44cc-ba54-57d55417bbb1" / margin=0px>
</div>
  
<h1 align="center">Client Backgorund</h1>

<p>ApexPlay Gaming and Electronics Retail is an e-commerce company specializing in popular electronic products across the United States. Since its launch in 2018, the company has experienced significant growth, expanding its reach to a global customer base across four regions. Along the way, ApexPlay has faced increasing competition from industry peers, as well as both challenges and opportunities driven by the COVID-19 pandemic.

Reporting to the Head of Operations, an in-depth analysis was conducted to uncover key insights, trends, and overall business performance from ApexPlay’s transaction data between 2019 and 2022. This analysis provides actionable insights for cross-functional teams including Finance, Sales, Product, and Marketing to better understand performance, optimize day-to-day operations, and enhance the company’s ability to deliver high-quality products to customers worldwide.
</p>

<ul>
  <h2>North Star Metrics</h2>
  <li><b>Sales Trends:</b> Focusing on key metrics of sales revenue, order volume, and average order value (AOV).</li>
  <li><b>Product Performance:</b> Analyzing different product lines, market impact, and refund rates to inform strategic product decisions.
</li>
  <li><b>Loyalty Program Evaluation:</b> Evaluating the effectiveness of ApexPlay's loyalty program and providing recommendations to maximize customer engagement and retention.
<!-- Assessing the effectiveness of the company’s loyalty program in driving customer engagement, repeat purchases, and retention, with recommendations to enhance its impact.</li> -->
  <li><b>Regional Performance:</b> Evaluating regional demand and product performance across regions to identify growth markets and areas for improvement.</li>
</ul>

<div>
<br>
<h1 align="center">Executive Summary</h1> 
<img width="2268" height="1212" alt="image" src="https://github.com/user-attachments/assets/d36c1bf2-c68e-4de0-982c-e539cf402efa" />

<!-- <img width="2280" height="1188" alt="image" src="https://github.com/user-attachments/assets/93b9c28c-3700-42de-a60d-e549111a5289" /> -->


* ApexPlay Gaming and Retail generated over **$28M in sales revenue** from 108K orders between 2019 and 2022 with customers spending an **average of $260 (AOV) per transaction**.

* Revenue growth in 2020 was driven by both a 101% increase in order volume and higher customer spending, indicating a **temporary demand surge caused by the pandemic rather than sustainable growth**. Although order volume remained strong post 2020, declining AOV led to reduced revenue signaling a customer behavioural shift towards more valued purchases.
	
* By 2022, declines in both demand and spending suggest a broader market slowdown, highlighting the need to **focus on increasing current customer spend value rather than additional investments in new customer acquisition.**
  
* Historically, non loyalty customers have been outspending loyalty customers in basket size up until the end of 2021. However, as the loyalty program gained popularity over time AOV increased and **loyalty customers were spending on average $30 more than non-loyalty customers in 2022**.
  
* **One in nine MacBook Air customers decided it wasn't worth keeping**, and at $1,588 a unit, those 451 decisions didn't just reverse a sale, they likely **cost the business close to $743K in real net losses**.

  <div align="center">
  <table>
	  <tr>
		  <th>Recommendation</th>
		  <th>Primary Owner</th>
		  <th>Revenue Impact</th>
		  <th>Urgency</th>
	  </tr>
	  <tr>
		  <td>Q4 2023 recovery plan</td>
		  <td>Sales, Marketing</td>
		  <td>$800K–$1M</td>
		  <td>Immediate</td>
	  </tr>
	<tr>
		  <td>MacBook Air refund root cause investigation</td>
		  <td>Product, Finance</td>
		  <td>$300K–$350K recovery</td>
		  <td>Immediate</td>
	  </tr>
	  <tr>
		  <td>Loyalty enrollment acceleration</td>
		  <td>Marketing</td>
		  <td>$200K–$400K incremental</td>
		  <td>Short-term</td>
	  </tr>
	 
  </table>
  </div>
<br>
<!-- <br> -->

<h1 align="center"> Dataset Structure and ERD (Entity Relationship Diagram)</h1>
The database structure as seen below consists of four tables: orders, customers, geo_lookup, and order_status, with a total row count of 10,8127 records.
<div align= "center">
<img  width="690" height="482" alt="image" src="https://github.com/user-attachments/assets/6a098414-3697-4752-bd45-feecacbb4284" />
</div>


<h1 align= "center">Deep Level Insights</h1>

## Sales Trends
<DIV>
	<img width="2514" height="508" alt="image" src="https://github.com/user-attachments/assets/18712b4c-d2ec-45aa-902b-7c49feff0b4e" />

<!-- <img width="2294" height="610" alt="image" src="https://github.com/user-attachments/assets/dc8584dd-5e99-4c85-8818-db378710ec20" /> -->
</DIV>

* **Revenue grew steadily throughout 2019 before experiencing explosive growth in 2020**, reaching an all-time monthly high of $1.2M in December 2020. This surge was largely driven by the COVID-19 pandemic.

- However, **this level of growth was not sustained.** Revenue declined by 43% sharply in early 2021 from AOV ($311-$255) and over-volume contraction(4K-2.5K), before showing a modest recovery toward the end of 2022, mostly driven by seasonal factors such as Black Friday sales and holiday promotions.

- **Revenue declined sharply from 2021-2022 by a 46% drop** indicating a broader market  slowdown and contraction on a quarter-over-quarter basis until it hit an all time low of $178K in October 2022, lowest in the entire time peroid.

- **Revenue and order volume remained 28% above 2019 levels**, indicating that some pandemic-driven gains were retained. 



## Product Level Insignts
<DIV align="center">	
<img width="861" height="469" alt="Screenshot 2026-04-23 at 1 53 36 PM" src="https://github.com/user-attachments/assets/99908e2f-3780-4e79-9aea-40295eb746bf" />
</DIV>
  
* **Top performing product was the 27In 4K Gaming monitor**(~$10M in sales revenue), **worst performing roduct is the Bose Soundport Headphones** ($3k) though missing some monthly sales data would need to check in with the sales and product team.
  
* * While 27In 4K Gaming Monitor contributed mjorly to the total revenue (35%), customers were making more and frequent orders for the apple airpods and headphones, which is almost double the volume amount of the gaming monitor.
</ul>


## Loyalty Program Performance
<div align="center">
<img width="2098" height="904" alt="image" src="https://github.com/user-attachments/assets/30a51b14-41a3-4dda-ab67-0551a3a423e0" />
</div>


<!--* Historically, non loyalty customers have been outspending loyalty customers in basket size up until the end of 2021. However, as the loyalty program gained popularity over time AOV increased and **loyalty customers were spending on average $30 more than non-loyalty customers in 2022**.-->
  
* **AOV and order volume for loyalty customers have sustained growth beyond the pandemic boom** with revenue growing from $0.4M in 2019 to $2.7M in 2022 and an AOV growth rate of 18% from 2019 to 2022.
  
* **Non-loyalty customers who initially outspent loyalty members began to decline in early 2021**,with both order frequency and spend per transaction decreasing over time and by Q4 2022 both segments had dipped following similar downward trend in overall sales.
  
* **Loyalty customers who sign-up from mobile place their first order faster than non-loyalty members**~91 days vs 100 days. Likely due to frequent app user engagements such as push notifications and cart reminders.


## Refund Rates
<div align="center">
	<img width="80%" alt="image" src="https://github.com/user-attachments/assets/132a02b1-b25b-42d2-813e-f395a0e3eb95" />
</div>

  * Product refund rates climbed significantly from 2019 to 2021 (6%-9%) and then improved in more recent years, dropping down to 4% in 2021 and dialing down to 0% in 2022.

  * The Gaming Monitor and MacBook Air Laptop make up Apex play most expensive products (higher AOV) and thus a cause for concern and warrants further investigation into refund reasons.

  * The least returned product is the Bose soundport headphones with a refund rate of 0%, followed by the samsung charging cable pack at 1.3%, a good indication that these products are widely accepted by customers.

 

## Spotlight: Apple Products Refunds
<div align="center">
  <!-- <img width="648" height="439" alt="Screenshot 2026-04-13 at 1 47 06 AM" src="https://github.com/user-attachments/assets/461e32e5-2771-4569-8314-fcc705e81e53" /> -->
<img width="80%" alt="image" src="https://github.com/user-attachments/assets/063b56f9-b2fc-4957-ad12-50ea6054c10a" />
</div>



* **Apple products make up more than half of the total revenue lost due to refunds**, ~53% at $1.2M loss in revenue to refunded products and a 5.9% refund rate and 3k returns.

* Frequently most returned apple product was Airpods Headphones (2622 returns) accounting for 85% or apple product returned. Similarly, the Macbook Air Laptop had the highest refund rate (11.9%) amongst apple products, 451 out of 3946 orders.

* **One in nine MacBook Air customers decided it wasn't worth keeping**, and at $1,588 a unit, those 451 decisions didn't just reverse a sale, they likely cost this business close to $743K in net losses. 


## Regional Trends
* All regions exhibit similar trends in sales, with a spike and peaking in 2021 and steadily declining afterwards.
  
* **North America accounts for 55% of total revenue ($15 million)**, reflecting a dominant and well-established market position. However, this **presents a company wide risk of a regional market disruption** and the need for **diversification amongst other underperfomring regions**.
  
* **APAC region persents the biggest opportunity for growth**. Customers from APAC region have over the years spent more per transaction than any other region and has a AOV growth rate of 17.5% from 2019 to 2022.
  
* A high AOV coupled with low order volume ($279, 13K orders) in the **APAC region indicates a potential growth gap** that warrants further exploration. This may point to limited marketing reach or awareness, supported by the relatively flat performance across marketing channels in the region.


<h1 align="center">Recommendations</h1>


### Sales Team
    
* **Prioritize Q4 demand recovery** by building out reecovery plans with specific revenue targets, promotional calendar, and marketing channel investment to prevent a repeat at the most commercially critical moment of the year.

* **Develop a dedicated sales strategy for the APAC region** with its own customer acquisition funnel and conversion optimization approach which targets order volume growth.
<!--* **A 20% increase in APAC order volume, at the region's $279 AOV, would generate approximately $725,000** in incremental revenue from a market that already demoonstrates strong willingness to spend.-->

### Product Team
* **Launch a root cause investigation for MacBook Air refunds** targeting reasons for returns and address the dominant driver.
  
<!--* **Address the Gaming Monitor Revenue Concentration Risk Through Portfolio Expansion** by bundling adjascent products that compliment high volume products like adding mechanical keyboards, gaming headsets, monitor stands to the Gaming Monitor product line.-->
  
* Reaccess the continuation of Bose Soundsport and Apple Iphone due to their low sales performance.

 ### Marketing Team
* **Build dedicated APAC market activation campaign** tied around local language content and culturally relevant promotional events and celebrations.
  
* **Assess the APAC purchase journey for friction points** such as payment methods, currency display and close out barriers before campaign launch to ensure traffic generated converts at a rate that justifies the investment.


### Loyalty Program
* **Accelerate loyalty program enrollment as a primary revenue growth strategy** with the target of converting existing non-loyalty customers into active loyalty members without the need for new customer acquisition costs (CAC).
  
* **Build in-app enrollment prompts, push notification sequences, and cart reminder automations** that capture the behavioral advantage already demonstrated by mobile enrolled members.

<h2 align="center">Further Analysis</h2>

* Conduct an immediate Q4 2022 investigation to identify the primary cause of the collapse (internal or external market conditions) such as decline in conversion rate, site traffic decline or major competitor entry into the market.


</body>
