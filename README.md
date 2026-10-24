# Abhik Chakraborty

**Engineering Manager, Data and Backend at REA Group** · 📍 Gurugram, India

I build and run data platforms, and I've done it at scale for nearly 12 years: first as an engineer at ZS, Expedia Group and Amazon, and now as an engineering manager. My work sits where streaming systems, cloud cost and team building meet. Lately I've added AI-assisted delivery to that list, and it has become the highlight of my current role.

🌐 [abhikchakraborty92.github.io](https://abhikchakraborty92.github.io) · 🔗 [LinkedIn](https://www.linkedin.com/in/abhik-chakraborty-77bb1275/) · ✏️ [Medium](https://medium.com/@abhik-chakraborty92)

## 💼 Career

### <img src="assets/logos/rea.png" alt="" width="24" height="24"> REA Group · Engineering Manager, Data and Backend
*September 2025 – present*

I lead a 10+ person data engineering group across multiple pods: the Gurgaon team I built, and an existing team in Xi'an, China. Between them they own REA Group's clickstream data platform and the Real Commercial Australia (RCA) email marketing data platform. When I joined, ownership of the platform sat in Australia. I built the Gurgaon team, moved ownership across, and set the hiring, operational and engineering standards the team runs on. The platform handles hundreds of millions of customer events a day across AWS and BigQuery, on streaming infrastructure built from Kinesis, Snowplow, Lambda, ECS and DynamoDB with sub-minute real-time SLAs, and feeds hundreds of analytics, BI and ML use cases downstream.

Cost has been a big theme. Under my direction, the team moved real-time processing from Flink to a Lambda-based architecture and right-sized workloads and scaling across our streaming and serverless platforms, which together have cut our annual cloud bill by over AUD 100K a year. When we took on the RCA platform, we also took ownership of a set of marketing and email campaign data pipelines. The highlight so far is AI delivery: I led the team in building an AI-driven agentic workflow of multiple agents in Claude Code that works as an AI engineer inside our delivery process, and it has cut our delivery cycle time substantially.

### <img src="assets/logos/expedia.png" alt="" width="24" height="24"> Expedia Group · Manager, Data Engineering
*March 2023 – September 2025*

I came back to Expedia to lead a team of data engineers, the only platform analytics team in India, building the data behind experimentation, research and competitive insights. Our biggest project, which I led, was moving the team's data ecosystem from Redshift to Expedia's data lake on Spark, Docker and Airflow. It removed data silos, brought us in line with company-wide data standards and saved over USD 50K a year. Releases were slow along the way, so I designed and coded Chariot myself, end to end: an in-house CI/CD tool on Docker, Airflow and GitHub Actions that took production deployments from over an hour down to minutes.

The team also built several data products. We built the single source of truth for checkout analytics from clickstream data, which tracked adoption of Expedia's One Checkout Page (one checkout across all platforms) against the older site-specific checkout pages. We also delivered Connectivity Quality Score pipelines and dashboards, end to end, that scored airlines on price consistency, bag attach and purchase success to improve customer recommendations. And we built curated datasets for the localization program, tracking translation progress, performance and customer sentiment as Expedia grew in non-English-speaking markets.

### <img src="assets/logos/amazon.png" alt="" width="24" height="24"> Amazon · Data Engineer II
*October 2022 – March 2023*

My time at Amazon was short and very hands-on. I built PySpark pipelines on AWS EMR for order-inquiry metrics, with stronger transformation and validation on large-scale datasets, and brought metric inaccuracy down from double digits to under 1%. On Just Walk Out (JWO), I built near-real-time ingestion on API Gateway and Lambda that compared high-volume event streams from Franke coffee machines with JWO-captured events, catching errors early and cutting sensor errors by a double-digit percentage. I also built a scalable near-real-time pipeline on Lambda, SQS and S3 that ingested millions of rows a day for a critical shadow experiment, which helped cut associate errors by a double-digit percentage.

### <img src="assets/logos/expedia.png" alt="" width="24" height="24"> Expedia Group · Data Engineer II → Data Engineer III → Lead Data Engineer III
*May 2018 – October 2022*

This is where I grew from building pipelines to leading the people who build them. I started in Corporate IT, where I built a central data warehouse on SQL Server with Python ETL that pulled together incident data, SLA compliance and call records from Cisco and Avaya. On top of it I built an eIT scorecard with dozens of KPIs in Tableau that leadership used to track Corporate IT performance. I also built a Python alerting service that checked ServiceNow SLA compliance every hour and sent batched notifications with escalations, which eliminated the large majority of SLA breaches. That performance management work earned me the ECommerce Platform Champion Award.

As a Data Engineer III, I modernized a legacy outage prediction platform, replacing its near-real-time database schedulers with Python ETL pipelines and tuning the APIs to cut prediction errors by a double-digit percentage. I built a data warehouse for licence and cost management that merged databases, APIs and flat files into one source of truth. It shrank the licensing footprint and got unused applications removed. Other work from this period included an analytics scorecard for Expedia DPI (a Redshift warehouse fed from ServiceNow, with KPIs and Tableau drill-downs), Slack analytics apps with slash commands on AWS Lambda that put insights on leaders' phones, and sentiment analysis of email campaign feedback using Python, Redshift and AWS Comprehend.

As Lead Data Engineer III in Infrastructure Analytics, I provided technical leadership for a small team of analytics engineers. I designed an automated CI/CD setup on Docker and Jenkins that cut data pipeline integration time by well over half. I also designed and deployed a metadata correction service on the GitHub API, S3, Lambda and Redshift that improved metadata accuracy and completeness across tens of thousands of applications. Along the way I received Expedia's Way to Go! award several times.

### <img src="assets/logos/zs.png" alt="" width="24" height="24"> ZS · Business Technology Analyst → Senior Business Technology Analyst
*June 2015 – April 2018*

I started my career at ZS doing data engineering for one of the world's largest pharmaceutical companies, and managed a small team. I standardized physician and patient profile data across Europe with Python ETL pipelines on AWS Redshift and S3. I built a terabyte-scale data warehouse and ETL pipelines in Dataiku DSS to capture sales data for the client's rare disease drugs in Europe, and I built Tableau dashboards that tracked sales, distribution and budget for the client's drug expansion in Asia Pacific. I was promoted to Senior Business Technology Analyst in January 2018.

## 🛠️ What I work with

| Area | Tools |
|---|---|
| Languages | Python, SQL, PySpark, Shell/Bash |
| Streaming and real-time | Kinesis, Snowplow, Lambda, SQS, SNS, API Gateway |
| Batch and big data | Spark, AWS EMR, Airflow, Dataiku DSS |
| Warehouses and databases | BigQuery, Redshift, PostgreSQL, MySQL, MS SQL Server, DynamoDB, RDS |
| Platform and CI/CD | AWS (S3, ECS, ECR), Docker, Jenkins, GitHub Actions |
| AI tooling | Claude Code |
| BI and visualization | Tableau, Streamlit |
| Leadership | Hiring and team setup, mentoring, performance and compensation management, cost optimization, Agile and Kanban |

## 🚀 Projects

- **[India COVID Resource Finder](https://github.com/abhikchakraborty92/india-covid-resource-finder)**: a search engine for COVID resources built on the Twitter feed, using Python, Twitter APIs and Streamlit. Hosted on Heroku, it got 25,000+ hits.
- **[AWS Lambda Slack slash-command template](https://github.com/abhikchakraborty92/aws-lambda-slack-slash-template)**: a Python template for serverless Slack apps that send insights in response to Slack messages, on AWS Lambda, HTTP Gateway and S3.
- **TXP**: single-line Python commands for Tableau. Download data, images and PDFs, manage data sources and read usage data.

## 📜 Certifications

- Kanban System Designer, Kanban University (2025)
- Dataiku Core Designer (2020)
- Certified Data Scientist in Tableau (2020)
- Robotic Process Automation Developer Certification in UiPath (2019)

## ✍️ Outside work

I wrote the mystery novel *Shadows of the Departed*, which was exhibited at the Cairo and Abu Dhabi International Book Fairs.
