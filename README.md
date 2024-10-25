# Supply-Chain-Report
  * **Domain** - FMCG
  * **Function** - Strategy
  * **[Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTBkMmNhOGYtNWQwNS00Y2YyLWJiZDctYmVmMjUzZmZlZjM1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&embedImagePlaceholder=true)**
  * [Linkedin Post](https://www.linkedin.com/feed/update/urn:li:ugcPost:7242908079690788865/)

## Problem Statement-
AtliQ Mart (Imaginary Company) is facing an issue where key customers are not renewing their annual contracts, potentially due to service-related concerns. The company's management wants to resolve this problem before expanding the business to other cities. Currently, AtliQ Mart operates in three cities in Gujarat: Surat, Ahmedabad, and Vadodara. The management has tasked the analytics team to track and analyze the "On Time," "In Full," and "On Time In Full" (OTIF) metrics daily, comparing them against target values for all customers. This analysis will help the company identify and address service issues promptly.

## Task-
  * Create the necessary metrics based on the list provided by stakeholders.
  * Design a dashboard per the requirements from the business review meeting.
  * Analyze and provide relevant insights that go beyond the specified metrics.

## Dataset-
  you can find the dataset- [Resume Project Challenge-2: Generate Insights to Solve a Supply Chain Issue in the FMCG domain by Codebasics](https://codebasics.io/challenge/codebasics-resume-project-challenge)
  
## Data Model
![Screenshot 2024-09-20 132637](https://github.com/user-attachments/assets/0ce24594-88e6-4a34-b93e-393ab52c786f)

## Steps Taken
  * Performed ETL (Extract- Transform- Load) using Power Query & Data Modelling on the dataset.
  * Created necessary key measures like -OT% (On Time %), IF% (In Full %), OTIF% (On Time In Full %), LIFR% (Line Fill Rate %), VOFR% (Volume Fill Rate %), Total Orders, Average Delay in Delivery in Days (ADD), Ordered Quantity & Delivered Quantity and more utilizing DAX functionality.
  * Created various dashboards to gain insights by customers, products, orders, order lines, city, food category, date.

## Key Insights - Customer Performance

### Top Customers
- **Top Customers**: Acclaimed Stores, Lotus Mart, Vijay Stores, Rel Fresh, Coolblue, and Propel Mart are the top customers by order volume.
- For Acclaimed Stores, Coolblue & Lotus Mart, almost 70% of the time, order lines are delayed.
- **Recommendation**: These customers should be prioritized for maintaining strong relationships and ensuring high service levels.

### Performance by City
- **Surat**: 
  - Lotus Mart and Acclaimed Stores have the highest average delivery delay of 1.26 days.
  - **Focus**: Improve on-time delivery performance for these key customers. For Info Stores, focus on increasing the order fulfillment rate.

- **Ahmedabad**:
  - Coolblue, Acclaimed Stores, and Lotus Mart experience average delivery delays of 1.27 days.
  - **Focus**: Prioritize on-time delivery and demand fulfillment for Lotus Mart and Sorefoz Mart to avoid delays and stockouts.

- **Vadodara**:
  - Coolblue, Acclaimed Stores, and Lotus Mart face an average delay of 1.265 days.
  - **Focus**: Enhance on-time delivery while concentrating on fulfilling the orders of Coolblue, Elite Mart, and Vijay Stores in-full.

### Product Category Insights
- **Dairy** accounts for the largest number of orders—approximately three times more than the Food & Beverages category.
- **Commonly Ordered Packages**: 250g, 100g, and 500g packages are the most popular across all cities.
- **Recommendation**: Optimize supply chain efficiency for the Dairy category to handle its high demand.

### Order Fulfillment Insights
- **Average OT%**, **IF%**, and **OTIF%** are significantly lower than the targeted value.
  - On-Time Delivery (OT%) and In-Full Delivery (IF%) are both around 50%, while On-Time In-Full (OTIF%) is much lower at 30%, indicating a substantial gap in achieving both timeliness and full deliveries simultaneously.
  - While analyzing key metrics on a daily basis, not a single day’s actuals were able to reach the target.
  
- **Average Delivery Delay**: The current delay stands at 0.42 days, with 40% of orders delayed.
- **Recommendation**: Focus on strategies to improve both OTIF and reduce delays by optimizing logistics and inventory management.

## Next Steps
  - Implement targeted interventions to reduce delivery delays in key cities and Customers.
  - Engage with top customers to understand their needs and address delivery issues.
  - Streamline the supply chain for the Dairy category to handle increased order volume.
  - Demand for product packages of 100, 250 & 500 gms are high, ensure proper stocking to avoid delays and ensuring on time delivery.

## Tools Used
  * Power BI
  * [Freepik](https://www.freepik.com/)
  * [Flaticon](https://www.flaticon.com/)
  * [Coolors](https://coolors.co/palettes/trending)
  * [iStock](https://www.istockphoto.com/)
