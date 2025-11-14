# Data Acquisition Project

This assignment was done as a part of the Data Acquisition and Preprocessing module. It aimed to obtain, clean and combine data across various sources and analyse it using visualisation.

## Project overview

- **Kaggle dataset**: U.S. Pollution Data (https://www.kaggle.com/datasets/sogun3/uspollution)
- **Scraped Website**: USA: States and Major Cities (https://www.citypopulation.de/en/usa/cities/)
- **Goal**: To examine the relationship between population size and level od air pollution in a city especially the NO₂ and CO air pollution.

## Steps covered:

1. Imported and cleaned the pollution dataset with pandas.
2. Getting a random sample of 20000 rows from the original dataset.
3. Scraped a website with USA city population data using 'panda.read_html()'.
4. Merged the two datasets on 'City' and 'State'.
5. Analysed the data with the help of Seaborn visualisations.
6. Produced knowledge regarding the levels of NO₂ and CO in comparison with population.
7. Documented AI usage.

## Tools and Libraries used

- Visual Studio Code
- Python (Jupyter Notebook)
- pandas
- seaborn
- matplotlib
Note: I have thought of using BeautifulSoup to scrap data on website initially, but the data on the target site was formatted into clean table of HTML.
So, I asked to the AI which could have been another way to scrap the website with pandas.
Then, I have used pandas.read_html() as a more useful option because it enabled me to get the data directly instead of manually parsing the HTML code.
