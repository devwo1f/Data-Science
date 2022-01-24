# Data Science

Set of methodologies for taking in thousands of forms of data that are available to us today and using them to draw meaningful conclusions.

Data can be used to better describe the present or better predict the future.

> **“The ability to take data — to be able to understand it, to process it, to extract value from it, to visualize it, to communicate it — that’s going to be a hugely important skill in the next decades.” ~ *Hal Varian***
> 

### What can Data do?

- Describe current state of an organisation or process
- Detect anomalous events
- Diagnose the cause of events and behaviours
- Predict future events

### Data Science Workflow

![Untitled](https://user-images.githubusercontent.com/48999616/150672566-9e8d7aab-30c6-46d9-a49b-8af7ba07e07d.png)


### Applications of Data Science

- Traditional Machine Learning
- Internet of Things (IoT)
- Deep Learning

### Machine Learning

Machine learning is the study of computer algorithms that can improve automatically through experience and by the use of data.

**What do we need for Machine Learning?**

- A well defined question
    - *"What is the probability that this transaction is fraudulent"*
- A set of example data
    - *Old transactions labeled as “fraudulent” or “valid”*
- A new set of data to use our Algorithm on
    - *New credit card transactions*

### Internet of Things (IoT)

Refers to gadgets that aren’t standard computers but still have the ability to transmit data.

- Smart Watches
- Internet connected home security systems
- Electronic toll collection systems
- Building energy management systems

### Deep Learning

- Multiple layers of mini algorithms called neurons work together to draw complex conclusions
- Requires much more data, but also able to learn relationships that traditional models cannot
- Used in complex problems:
    - Image classification
    - Language learning/ Understanding

## Data Science Roles and Tools

There isn’t a single job in data science. Generally, there are 4:

- Data Engineer
    - Information Architects
    - Build data pipelines and storage solutions
    - Maintain Data Access
- Data Analyst
    - Perform simple Analysis that describe data
    - Create reports and dashboards to summarize data
    - Clean data for analysis
- Data Scientist
    - Versed in statistical methods
    - Run experiments and analysis for insights
    - Traditional machine learning
- Machine Learning Scientist
    - Predictions and extrapolations
    - Classifications
    - Deep Learning
        - Image processing
        - Natural language processing

| Data Engineer | Data Analyst | Data Scientist | Machine Learning Scientist |
| --- | --- | --- | --- |
| Store and maintain data | Visualise and describe data | Gain insights from data | Predict with data |
| SQL+Java/Scala/Python | SQL+BI Tools+Spreadsheets | Python/R | Python/R |

## Sources of Data

| Company Data | Open Data |
| --- | --- |
| Collected by companies | Free, open data sources |
| Helps them make data-driven decisions | Can be used, shared, and built-on by anyone |

## Company data

We are generating vast amounts of data on a daily basis simply by surfing the internet, tracking a run, or paying by card in a shop. The companies behind these services that we use, collect this data internally. They use this to help them make data-driven decisions.

### Examples:

- Web events
    
    <img width="656" alt="Screenshot_2022-01-23_at_2 54 11_PM" src="https://user-images.githubusercontent.com/48999616/150672570-0758d959-7095-4d65-8ee1-028d5d14b1bc.png">

    
    - Events
    - Timestamps
    - User Information
- Survey Data
    - Asking people for their opinions
    - Methods:
        - Face to Face interview
        - Online Questionaire
        - Focus group
- Customer Data
- Logistics Data
- Financial Transactions

## Open Data

Free, open data sources

- Data API’s
    - Application Programming Interface
    - Request data over internet
    - Exaples:
        - Twitter API
        - Wikipedia API and many more...
- Public records
    - International organisations
        - eg.: World Bank, UN, WTO
    - National statistical offices
        - eg.: censuses, surveys
    - Government agencies
        - eg.: weather, environment, population
## Why care about Data Types?

- Storing the data - Because all types of data cannot be stored together
- Visualising/Analysing - Not all visualisations and analysis can be performed with all data types

### There are two general types of data

- Qualitative
    - Deals with descriptions
    - Data cannot be measured but observed
- Quantitative
    - Counted/Measured

### Other data types

- Image Data
- Text Data
- Geospatial Data
- Network Data

### Things to consider when storing data

- location
- Data type
- Retrieval

### Location

Parallel Storage Solution

- Storing the data across many different computer

The Cloud

- Storing the data in Cloud

### Type

- Unstructured
    - Email
    - Text
    - Video/Audio
    - Web Page
    - Social Media
- Tabular
    - Stored in table
    - Relational Database

### Retrieval

- Data Querying
    - Document Database - NoSQL
    - Relational Database - SQL

# Data Pipeline

A **data pipeline** is a series of data processing steps. If the data is not currently loaded into the data platform, then it is ingested at the beginning of the pipeline. Then there are a series of steps in which each step delivers an output that is the input to the next step. This continues until the pipeline is complete. In some cases, independent steps may be run in parallel.

Data pipelines consist of three key elements: a source, a processing step or steps, and a destination. In some data pipelines, the destination may be called a sink.

![24_DataPipleline-1](https://user-images.githubusercontent.com/48999616/150748994-e6800310-f098-4f80-a420-d2046fe4edb7.png)


- Moves data in defined storage
    - Eg: From data insertion from an API to loading data into a database.
- Automated Collection and storage
    - Scheduled, hourly or Daily
    - Triggered by an Event
- Monitored with generated alerts
- Necessary for Big Data projects
- Data Engineers works to customise solution
- Extract Transform Load (ETL) - Data Pipeline Framework

### How does it all come together?

- Extracting
    - We begin extracting the data from all sources
- Transform
    - We then organise the data
        - Joining the data sources into one data set
        - Converting data structures to fit database schemas
        - Removing irrelevant data

*Data exploration and preparation does not occur on this stage*

- Load
    - We load the data so that it could be used for visualisation and analysis

