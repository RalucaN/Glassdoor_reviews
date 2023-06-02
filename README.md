# Glassdoor_reviews
This repository includes a Data science project about collecting and analyzing Glassdoor reviews

**Planning**
- **Research question and objective**: what are the most common skills, qualifications, and experiences that applicants for a particular job have.
- **Data collection and cleaning**: 
    - using web scraping tools or APIs to extract the reviews from Glassdoor.
    - Filter the reviews by the job title and location of innterest, and remove any duplicates, missing values, or irrelevant information.
- **Exploratory data analysis (EDA)**: Using descriptive statistics, visualizations, and natural language processing techniques to understand the distribution, trends, and patterns of the reviews
- **Sentiment analysis on the reviews**: Using sentiment analysis tools or models to classify the reviews into positive, negative, or neutral categories based on their tone and emotion.
- **Extract features and insights from the reviews**: 
    - using text mining techniques such as topic modeling, keyword extraction, named entity recognition, or word embeddings to identify the main themes, skills, qualifications, experiences, or attributes that are mentioned in the reviews. 
    - using machine learning techniques such as clustering, classification, or regression to find relationships, correlations, or predictions among the features and the sentiment of the reviews.
- **Communicate and visualize findings**: Use tools such as dashboards, reports, or presentations to summarize and communicate results (word clouds, charts, graphs, or maps to highlight the key insights and recommendations from the analysis)


```mermaid
graph TB
    A[Start] --> B[Define question]
    B --> C[Collect and clean data]
    C --> D[EDA and sentiment]
    D --> E[Extract features]
    E --> F{Choose technique}
    F -->|Clustering| G[Find groups]
    F -->|Classification| H[Classify reviews]
    F -->|Regression| I[Predict outcomes]
    G --> J[Summarize findings]
    H --> J
    I --> J
    J --> K[End]
    C -- Web scraping or APIs --> L((Data))
    L -.-> C
    D -- Sentiment tools or models --> M((Categories))
    M -.-> D
    E --> N[Text mining]
    N --> Q[Themes]
    N --> R[Skills]
    N -->S[Qualifications]
    N --> T[Experiences]
    Q -.-> E
    R -.-> E
    S -.-> E
    T -.-> E
    style A circle, 50px;
    style K circle, 50px;
 ```
**Timeline**
```mermaid
gantt
    title Glassdoor reviews Data Science Project Timeline
    dateFormat YYYY-MM-DD
    axisFormat %b %d
    section Define question
        Define research question and objectives: 2023-06-01, 2023-06-03
    section Collect and clean data
        Research available web scraping methods: 2023-06-03, 2023-06-04
        Collect Glassdoor reviews data: 2023-06-04, 2023-06-05
        Clean and preprocess data: 2023-06-05, 2023-06-08
    section EDA and sentiment
        Perform descriptive statistics and visualizations: 2023-06-08, 2023-06-11
        Perform sentiment analysis on reviews: 2023-06-11, 2023-06-18
    section Extract features
        Apply text mining techniques: 2023-06-18, 2023-06-22
        Extract features from reviews: 2023-06-22, 2023-06-25
    section Choose technique
        Choose machine learning technique: 2023-06-26
        Find relationships or predictions from reviews: 2023-06-27, 2023-06-30
    section Communicate findings
        Create summary of results: 2023-07-01, 2023-07-02
```
