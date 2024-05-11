# Ben-s-Pizza-Project
The task entails crafting a customized relational database to support a burgeoning pizzeria. Employing Excel for data structuring, Quick Database Diagrams for schema design, and SQL for database administration, the project ensures robust data management. Furthermore, Looker Studio enables intuitive data representation, complemented by seamless integration with Google Cloud Console for reliable data storage and processing.

## About Project

### SITUATION
Ben is launching a new pizzeria in his locale, emphasizing take-out and delivery akin to Domino's. He's outlined a project to craft a bespoke relational database for his venture, capturing crucial data on orders, inventory, and personnel. This database empowers him to track business metrics and construct dynamic dashboards for insightful analytics.

### TASK
The initial phase of the project entails creating an orders table within the database infrastructure. This table must encompass fields for item details like name, category, size, price, and quantity, alongside customer information such as first and last names, along with delivery address and pertinent particulars. The assignment further encompasses data normalization, the incorporation of associated tables, and the establishment of table relationships to optimize data storage and adaptability.

### ACTION
The project entails crafting distinct tables to manage various aspects like customers, orders, addresses, items, recipes, ingredients, inventory, rota, shifts, and staff. Each table is assigned a unique ID, facilitating interconnection through this key. Subsequently, the database is prepared for utilization in MySQL. Additionally, a dashboard is developed to oversee and assess the pizzeria's performance, offering insights into its operational metrics.

### RESULT
Upon project completion, Ben will possess a robust database capable of seamlessly managing customer orders, streamlining stock management, and enhancing staff oversight. Leveraging interactive dashboards derived from this database, Ben can effectively monitor and assess his business's performance, empowering informed decision-making with valuable insights gleaned from real-time data analysis.

## Built With

### Normalization
The project implemented normalization techniques within Excel to enhance data integrity and reduce redundancy. This process entailed crafting table mock-ups and meticulously organizing data prior to its integration into the database.

### Database Design Tools
The project utilizes QuickDBD, a database design tool, to construct a graphical depiction of the database schema. With QuickDBD, users define tables along with their respective fields, generating a comprehensive diagram illustrating the database structure and its constituent tables.

![Screenshot (1091)](https://github.com/kaifahmed2002/Ben-s-Pizza-Project/assets/92524691/b12629ce-140e-4406-95c4-68a74744bc7c)

## Dashboards
The project incorporates Looker Studio in tandem with Google Cloud Console. Looker Studio facilitates the creation of interactive dashboards for monitoring business performance, while integration with Google Cloud Console ensures secure and scalable data storage and processing capabilities.

### Dashboard 1: Orders
The initial Looker dashboard provides a visual overview of order-related insights, including total orders, sales, items, and average order value. Sales distribution by product is depicted in a pie chart, while total sales by product subcategory are displayed in a bar graph. Another pie chart distinguishes orders with and without delivery. A line graph showcases the flow of total orders and sales hourly, and a map pinpoints order locations for a geographic perspective on distribution.

![1_page-0001](https://github.com/kaifahmed2002/Ben-s-Pizza-Project/assets/92524691/4570966f-75a2-4181-8ce9-ff8cc70597e5)

### Dashboard 2: Inventory
The subsequent Looker dashboard focuses on inventory metrics, illustrating ingredient costs, total quantity, total cost, and the percentage of remaining inventory. It also calculates the cost of each pizza based on ingredient costs, aiding the team in monitoring inventory health and making informed decisions regarding ingredient procurement and usage.

![2_page-0001](https://github.com/kaifahmed2002/Ben-s-Pizza-Project/assets/92524691/ab3b3609-ac99-48bb-977c-1af43843dda9)

### Dashboard 3: Staff
The third Looker dashboard offers insights into staffing costs and hours worked, visually presenting staff costs, total hours worked, and other staffing details. This information assists in optimizing workforce management, ensuring alignment of staffing resources with peak hours of operation.

![3_page-0001](https://github.com/kaifahmed2002/Ben-s-Pizza-Project/assets/92524691/9ac260c2-8ed7-4c84-a38f-2851b86a29ed)

Try Dynamic Dashboard 👇
https://lookerstudio.google.com/reporting/56ffe238-2d1a-4245-ac57-8b2c7fa0f5c5
