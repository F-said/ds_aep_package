# Project

For this fellowship you will be developing an analysis (or engineering) data project that is immediately applicable to a specific company or role that you would like to apply to. 

While the ideation portion of this project is covered under the **Project Framework** section in your `README.md` file, this document will describe the planning steps you should take before completing this project.

This includes:
* Goals: What are the main high-level goals that you are aiming to accomplish? 
* Requirements: You will notice that this section has been filled out for you. These are the baseline pre-conditions that your project should meet to be considered complete.
* Datasets: Which datasets have you identified that are pertinent to your project? 
* Tech-Stack: Which technical tools will you use?
* Risks: Which realities might hold your project back from being completed in 3 weeks?
* Solutions: How will you address each risk?
* Schedule: This is also filled for you already. This is simply the syllabus schedule. 

More information is listed in each subsequent section below

## Goals

You should begin your project by stating your overarching goals.

This goes beyond technical terms and describes the *thing* that your project will accomplish. If you were to describe the purpose of this project to someone that does not operate in Python, or in any other technical capacity, how would you describe it to them?

Keep in mind that 3 weeks is a fairly quick turnaround to develop a comprehensive MVP, so expectations should be tempered. In fact, you should aim for a goal that could be complete within two weeks of moderate work. 

For example, if you were designing a project that scraped data from multiple "predictions markets" and evaluated "market sentiment" by calculating descriptive statistics, you may state that the overarching goal of this project is to *"Evaluate and identify to which political or economic outcome the market is biased towards, by aggregating prediction market trends.*"

## Requirements

Each project, regardless of its core-content, will fulfill the outlined specifications (based on the type of project you choose). As you complete your project, ensure that you are on the correct path by comparing your work to this list.

**Analytics**
* Exploratory analysis is performed
* Confirmatory findings through statistical analysis is done
* Data cleaning, validation, and potentially transformation is performed
* Repository is organized
* Comprehensive README on findings is complete

**Engineering**
* ETL/ELT pipeline is complete
* Non-local data store is set up
* Code abides by Pythonic standard
* Code abides by OOP design principles (where applicable)
* Code is well documented
* Brief README on project architecture is complete

## Datasets

Next, you will identify a dataset that you will use for your project. This is more important to those of you that select the *analytics* type project, as the quality of your findings will be dictated by the quality of data you find.

For your targeted project, ideate and find a dataset that will allow you to complete your planned goals. Utilize the following resources to find your data:
* https://data.gov/
* https://www.kaggle.com/datasets
* https://datasetsearch.research.google.com/

There are also datasets that are readily available for you to use, just ask your staff for access:
* honeypot cyber-intrusion data
* anonymized educational data

Sometimes, you will have to implement your own data-collection algorithm to create your defined dataset. This could either come in the form of a web-scraper, or through a pdf-processer. Using the *market sentiment* example project from above, your method of data-collection will entail querying the [GraphQL](https://thegraph.com/docs/en/querying/graphql-api/#time-travel-queries) API to pull data. 

## Tech-Stack

You will also identify the tools you need to complete your project. In a bulleted list, identify the tool you will need and the purpose of each tool. You should also identify the "sub-packages" that you will need for each tool.

Again, using the market sentiment example project, a bulleted list of tools might include:

* Python: Programming language to handle data flow & interface
    * Streamlit: A dashboard tool to build interactive visualizations
    * GraphQL: API to interface with Polymarket data
    * Pandas: Package for data manipulation
* Git: Version-control tool to push code
* Excel: Sheet software for simple data exploration

## Risks

Next, you will outline the possible risks that might prevent you from completing your project. These risks should encapsulate all possible problems, including those that relate to limited resources (i.e. paid datasets), or even limited person-hours.

Using our example project, risks that could prevent us from completing our market sentiment analysis include:

1. Time to learn new GraphQL API is not sufficient for data pulling
2. Polymarket API requires paid subscription
3. Streamlit server memory limits are not sufficient for project
4. Market sentiment is too varied for conclusive findings
5. Many different betting markets on Polymarket, scope is not well defined

Of course, we cannot predict all possible risks that come with our project. However, by using our knowledge of previously completed projects, we can at least prepare for the most common ones.

## Solutions

The reason that we list our risks is so that we can ideate next actions and frameworks that will help us avoid these issues. For each risk that you've listed, follow up with a possible solution that mostly or completely negates this risk. Feel free to get creative and utilize project management patterns that you've used in the past!

Using the above list of risks, some possible solutions include:

1. Utilize ChatGPT to design an initial GraphQL template to pull code.
2. Explore free/trial API services. Or alternatively, use `selenium` and `bs4` to scrape your own data.
3. Limit data to under 1gb.
4. Select a specific scope before beginning your analysis, and present findings even if not conclusive (no [p-hacking](https://scienceinthenewsroom.org/resources/statistical-p-hacking-explained/#:~:text=This%20is%20a%20technique%20known,is%20no%20real%20underlying%20effect.)!)
5. Related to above problem, select specific scope before beginning analysis.

## Schedule

Below will be the schedule that our AEP follows. 

1. Sprint 1 10/18: Project selection & planning
2. Sprint 2 10/25: Technical analysis or pipelining complete.
3. Sprint 3 10/31: Prescriptions & visualization complete.
