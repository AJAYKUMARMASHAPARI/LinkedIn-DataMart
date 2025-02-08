LinkedIn DataMart (Feb 2024)
🚀 A Comprehensive Data Engineering & Business Intelligence Project

📌 Project Overview
This project extracts, transforms, and visualizes LinkedIn profile data to provide insights into user connections, job trends, and engagement metrics. The workflow involves ETL pipelines, cloud technologies, and business intelligence tools to enable data-driven decision-making.

🔹 Tech Stack:
Python | SQL | Power BI | Azure | Docker | Dremio | Pentaho

🔹 Key Features:
✅ Data Extraction: Ingests LinkedIn profile data using APIs & web scraping.
✅ ETL Pipeline: Cleans, transforms, and loads data into a structured DataMart.
✅ Data Warehouse: Uses Dremio & Azure SQL for fast query performance.
✅ Cloud Integration: Hosted on Azure Cloud for scalability.
✅ Data Visualization: Interactive Power BI Dashboards for insights.
✅ Containerization: Dockerized deployment for portability.

🛠 Pipeline Flow:
1️⃣ Extract – Retrieve LinkedIn data (APIs, Web Scraping).
2️⃣ Transform – Clean, standardize, and enrich data using Pentaho.
3️⃣ Load – Store transformed data in Dremio & Azure SQL.
4️⃣ Visualize – Build interactive dashboards with Power BI.

📷 Sample Dashboards
📌 User Profile Analysis Dashboard
📌 Company Engagement Dashboard
📌 Job Trends & Network Growth Insights

🛠 Tech Stack & Tools
Category	Tools Used
Programming	Python, SQL
ETL & Processing	Pentaho, Azure Data Factory
Database	MySQL, Azure SQL, Dremio
Cloud & DevOps	Azure, Docker
BI & Visualization	Power BI, DAX
📂 Project Structure
bash
Copy
Edit
LinkedIn-DataMart/
│── data/                      # Sample dataset (sanitized)
│── etl/                       # ETL workflows (Pentaho KTR files)
│── dashboards/                # Power BI visualization files
│── scripts/                   # Python scripts for data processing
│── sql/                       # SQL scripts for database setup
│── docker/                    # Docker containerization files
│── README.md                  # Project documentation
│── LICENSE                    # License details

🛠 Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/AJAYKUMARMASHAPARI/LinkedIn-DataMart.git
cd LinkedIn-DataMart
2️⃣ Set Up the Environment
sh
Copy
Edit
pip install -r requirements.txt
3️⃣ Run ETL Pipeline
sh
Copy
Edit
python scripts/extract_data.py
python scripts/transform_data.py
python scripts/load_data.py
4️⃣ Start Docker Container
sh
Copy
Edit
docker-compose up
5️⃣ Access Power BI Dashboards
Open dashboards/LinkedIn_Insights.pbix in Power BI.
👨‍💻 Future Enhancements
🔹 Real-time Streaming – Implement a Kafka-based pipeline.
🔹 AI Insights – Use ML for predictive analytics on user engagement.
🔹 Expanded Dataset – Integrate job postings & salaries for deeper insights.

📬 Connect with Me
📧 Email: amashapari@hawk.iit.edu
💼 LinkedIn: Ajay Kumar Mashapari
🐍 GitHub: AJAYKUMARMASHAPARI
