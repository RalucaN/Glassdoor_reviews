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
