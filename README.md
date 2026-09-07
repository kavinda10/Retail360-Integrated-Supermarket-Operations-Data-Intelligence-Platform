Retail360-Integrated-Supermarket-Operations-Data-Intelligence-Platform
End-to-end data engineering platform for integrated supermarket retail, inventory, supply chain, bakery, prepared food, online sales, and customer analytics.
 Project Overview

Retail360 is an end-to-end data engineering project designed to simulate a modern supermarket group's integrated data platform.
The platform brings together multiple operational domains including retail sales, customers, inventory, suppliers, distribution, bakery production, prepared food operations, fresh produce, online orders, and food waste.

The project focuses on building reliable and scalable data pipelines that transform operational data into trusted analytical datasets for business decision-making.

 Business Context

LankaMart Retail Group is a fictional multi-store supermarket organization used as the business context for this project.

The organization operates across several connected business areas:

- Retail stores and POS transactions
- Customer loyalty
- Inventory management
- Supplier and purchasing operations
- Distribution
- In-store bakery
- Prepared food and kitchen operations
- Fresh produce
- Online sales
- Food and operational waste

 Business Problem

The organization currently generates operational data across multiple business processes and systems.

Management requires a reliable way to integrate these datasets and answer questions such as:

- Which stores are performing best?
- Which products generate the highest sales?
- Which products are slow-moving?
- Where are stockouts occurring?
- How efficiently are bakery products being produced?
- Which products are high moving in bakery ?
- How much food is being wasted?
- Which suppliers have delivery issues?
- How does customer behaviour differ between physical and online channels?
- What is the overall performance of each business domain?
-which products are high moving?
-which stores are performing weak?
The objective of Retail360 is to solve this data integration and analytics problem through a structured data engineering platform.

Project Objectives

1. Integrate data from multiple supermarket operational domains.
2. Implement reliable data ingestion and transformation pipelines.
3. Support incremental daily data processing.
4. Implement data quality validation and error handling.
5. Design a centralized analytical data warehouse.
6. Build domain-specific analytical data marts.
7. Analyse retail, inventory, supply chain and production operations.
8. Build a Customer 360 analytical view.
9. Provide management-ready analytical datasets and dashboards.
10. Automate and orchestrate data pipelines using modern data engineering tools.

Business Domains
| Domain | Description |
|---|---|
| Retail | Store sales and POS transactions |
| Customer | Customer and loyalty information |
| Product | Products and categories |
| Inventory | Stock levels and inventory movements |
| Supplier | Suppliers and purchasing |
| Distribution | Distribution centre and store replenishment |
| Bakery | Bakery production and finished products |
| Prepared Food | Kitchen and prepared meal production |
| Fresh Produce | Fresh produce receiving, sales and waste |
| Online | Online orders and delivery |
| Waste | Food and operational waste |

---

 Planned Data Platform

```text
Operational Data Sources
          │
          ↓
      Data Ingestion
          │
          ↓
     Data Validation
       ┌──┴──┐
       ↓     ↓
     Valid  Rejected
       │
       ↓
      RAW
       │
       ↓
    STAGING
       │
       ↓
  DATA WAREHOUSE
       │
       ↓
    DATA MARTS
       │
       ↓
     POWER BI
