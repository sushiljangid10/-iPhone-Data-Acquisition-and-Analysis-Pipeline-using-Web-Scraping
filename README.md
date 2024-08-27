For this project, we focused on designing and developing a Data Acquisition and Pre-processing Pipeline using the Flipkart India website as our data source. We began by importing essential libraries such as BeautifulSoup for web scraping, Pandas for data manipulation, and Requests for handling HTTP requests.


Data Acquisition:

We specified the URL of the Flipkart website and performed a GET request to retrieve the HTML content. Using BeautifulSoup, we parsed the HTML and extracted relevant data points for iPhones, including their names, original prices, ratings, offer percentages, and offer prices. We looped through multiple pages of the website to gather extensive data, storing it in a list called Mobile_Details.


Data Preprocessing and Transformation:

We constructed a DataFrame from the extracted data and performed various preprocessing tasks, including replacing special characters in the price and discount columns. We also converted the data types of specific columns (e.g., prices and ratings) from strings to floats for accurate numerical analysis. Missing values in the "Offer_%" column were filled with 0, ensuring no null values remained.


Querying the Data:

With our cleaned dataset, we executed several queries, such as finding a white iPhone under ₹60,000, identifying iPhones with discounts greater than 17% and prices above ₹90,000, and locating iPhones with ratings higher than 4.5, discounts over 15%, and prices within ₹70,000. These queries allowed us to extract specific insights from the dataset effectively.


The data pipeline we developed showcases our ability to scrape, preprocess, and analyze data, yielding valuable information about iPhone products on Flipkart.









