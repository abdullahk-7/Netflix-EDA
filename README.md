This project performs Exploratory Data Analysis (EDA) on the Netflix Movies & TV Shows dataset using Apache Spark and PySpark, running inside a Docker container. The goal is to derive meaningful insights from the dataset by applying various Spark-based data analysis techniques.
	•	Data Loading & Preprocessing: Handle missing values and clean data.
	•	Data Analysis & Insights:
	•	Top 10 directors with the most titles.
	•	Average release year by content type.
	•	Duration statistics (average, max, min) by content type.
	•	Top countries with the most diverse genres.
	•	Titles with the longest names.
	•	Content count by rating distribution.
 Technologies Used
	•	Apache Spark: Distributed data processing framework.
	•	PySpark: Python API for Apache Spark.
	•	Docker: Containerized environment for running Spark.
	•	Python: Data processing and analysis scripting.
 How to Run the Project

1. Clone the Repository
   
git clone[https://github.com/your-username/netflix-eda-spark.git](https://github.com/abdullahk-7/Netflix-EDA.git)
cd netflix-eda-spark
3. Run Docker Container
docker run -it --rm -p 8888:8888 -v "$PWD":/app apache/spark-py bash
4. Execute the EDA Script
   python3 netflix_eda.py
   Dataset
	•	Source: Netflix Movies & TV Shows Dataset (Kaggle)
netflix-eda-spark/
│── netflix_eda.py         # Main PySpark script
│── netflix_titles.csv     # Netflix dataset
│── Dockerfile (optional)  # Docker setup (if needed)
└── README.md              # Project documentation
Analysis Highlights
	1.	Dataset Overview: Column names, total records, and basic statistics.
	2.	Top Directors: Top 10 directors with the most Netflix titles.
	3.	Release Year Analysis: Average release year by content type.
	4.	Duration Analysis: Average, max, and min durations by content type.
	5.	Countries & Genres: Countries producing the most diverse content.
	6.	Longest Titles: Titles with the longest character counts.
	7.	Rating Distribution: Number of records per rating type.
 8.	
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.
