# APPLIED-DATA-SCIENCE-CAPSTONE
## Capstone Progress Log

### July 24, 2026 — Project Kickoff and Data Collection

Reviewed the IBM Applied Data Science Capstone scenario and established a clear understanding of the project’s purpose, stakeholders, and expected deliverables.

#### Project Objective

Act as a data scientist for the fictional company SpaceY and analyze SpaceX launch data to identify the factors associated with successful first-stage rocket landings and reusability.

The project will involve:

- Collecting real-world data from APIs and webpages
- Cleaning and organizing data with Python and pandas
- Querying structured data with SQL
- Performing exploratory data analysis
- Creating data visualizations
- Examining numerical and categorical variables
- Developing and evaluating predictive models
- Communicating the findings through a professional presentation and cohesive data story

#### Work Completed

- Reviewed the capstone scenario, business problem, and expected deliverables.
- Completed the introductory GitHub lab requirements using prior experience with repositories, README files, and commits.
- Used the Python `requests` library to retrieve data from APIs and webpages.
- Converted JSON API responses into pandas DataFrames with `pd.json_normalize()`.
- Selected and filtered multiple DataFrame columns using pandas.
- Used BeautifulSoup to parse the Wikipedia page containing Falcon 9 and Falcon Heavy launch information.
- Located the appropriate HTML launch table and extracted its column headings.
- Iterated through table rows and populated a Python dictionary with launch data.
- Converted the collected records into a pandas DataFrame.
- Generated a CSV dataset for use in later capstone labs.
- Completed the associated graded assessment with a passing score.

#### Troubleshooting and Problem Solving

- Interpreted Python traceback messages to identify missing variables, syntax errors, and data-extraction problems.
- Corrected multi-column pandas selection by supplying a list of column names inside double brackets.
- Diagnosed a SpaceX API failure by inspecting the HTTP status code, response content type, and returned HTML.
- Reproduced the HTTP `525` error in both Coursera and a local Anaconda Jupyter Notebook, confirming that the failure was external rather than caused by the notebook code.
- Used the course’s static data and correct processing sequence when the live API was unavailable.
- Modified the web-scraping logic to extract customer information from both linked and plain-text HTML table cells.
- Verified that the correct processed DataFrame was used when calculating assessment results.

#### Lessons Learned

This phase reinforced the importance of reading traceback errors carefully instead of treating them only as failures. Troubleshooting helped strengthen my understanding of Python syntax, pandas DataFrame operations, JSON normalization, HTML structure, and data extraction.

I also learned how to distinguish a programming error from an external-service failure by checking HTTP status codes, response content types, and results across multiple environments.

The experience demonstrated that reliable data collection requires validating the source, accounting for inconsistent webpage elements, and confirming that the correct dataset and processing sequence are being used. Python-based data extraction and web scraping remain important areas for continued practice.

#### Next Steps

- Continue strengthening Python data-extraction skills.
- Use the generated SpaceX CSV files in the data-wrangling phase.
- Clean and validate the collected launch data.
- Begin exploratory data analysis and SQL exercises.
- Continue documenting technical decisions, problems, and lessons learned.
