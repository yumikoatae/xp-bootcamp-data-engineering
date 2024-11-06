# Data Engineering

Data Engineering is a field responsible for collecting, processing, enriching, storing, and making data available. It serves as a bridge between the source of the data and its consumption by Data Analysts, Data Scientists, and Machine Learning Engineers. This enables these professionals to perform analyses and extract information to support decision-making by stakeholders.

To develop an effective data flow, several fundamental questions should be asked:

- Who will have access to the data?
- Are there personal data that need to be masked?
- How often will the data be updated?
- What method will be used for updating the data?

There are two main approaches to data processing:

1. **Extract, Transform and Load (ETL)**: Data is extracted, transformed, and then stored, usually used to feed Data Warehouses.

2. **Extract, Load and Transform (ELT)**: Data is extracted, loaded, and then transformed. This method is common in streaming and micro-batch pipelines.

|![image](https://github.com/user-attachments/assets/ab2f7a1b-af93-4723-a050-7ff8dffa147d)|
|:---:|


## Data Processing

1. [**Streaming**](https://www.upsolver.com/wp-content/uploads/2019/09/Screen-Shot-2020-05-25-at-17.05.22.png):
   - Refers to the real-time processing of data as it is generated or received.
   - Allows for continuous and immediate analysis, ideal for scenarios that require instant response, such as fraud monitoring in financial transactions (e.g., detecting suspicious activities in real time) and recommendation systems for movies or music based on user behavior.



2. [**Batch**](https://www.upsolver.com/wp-content/uploads/2019/09/Slide1.png):
   - Involves processing large volumes of data in groups or "batches" at specific time intervals.
   - Data is collected, processed all at once, and then stored or used for reporting. An example would be processing sales data in an e-commerce store at the end of the day to generate performance and inventory reports.


3. [**Micro Batch**](https://www.researchgate.net/profile/Martin-Andreoni/publication/327183263/figure/fig6/AS:662772144697357@1535028601564/Micro-batch-processing-used-in-Spark-stream-The-input-streams-are-received-by-receptors.png):
   - This is an intermediate approach between streaming and batch, where data is processed in small batches at very short intervals.
   - It allows for near real-time processing, useful in scenarios where a small delay is acceptable, such as analyzing server logs for performance monitoring and error identification.

➡️ [In-depth explanation](https://www.upsolver.com/blog/batch-stream-a-cheat-sheet)

## Data Workloads

Data can be processed in different ways:

- **Transactional Workloads (OLTP)**: Refers to online transaction processing, allowing for simultaneous operations. A common example is the point-of-sale system in supermarkets, where multiple transactions are processed simultaneously, ensuring that inventory and sales information are updated in real time.

- **Analytical Workloads (OLAP)**: Involves analyzing historical data for information retrieval. An example is analyzing purchase data in a supermarket app, where historical data is used to identify buying patterns and product preferences, enabling the company to optimize its marketing campaigns and inventory.

## The 5 V's of Big Data

Data Engineering considers five essential characteristics of Big Data, known as the 5 V's:

1. **Velocity**: The speed at which data is generated and processed, crucial for real-time analysis.
2. **Variety**: The diversity of data types collected, requiring tools that can handle different formats.
3. **Value**: The ability to transform data into useful insights that add value to the business.
4. **Volume**: The amount of data generated, which grows exponentially and requires robust infrastructure for management.
5. **Veracity**: The quality and reliability of the data, ensuring that analyses and decisions are based on accurate information.

These 5 V's are essential for Data Engineering, as they help shape how organizations manage and utilize data at scale, allowing them to become more agile and competitive.
