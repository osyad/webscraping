
![Web_Scraping_for_Common_Words_in_a_Novel](https://user-images.githubusercontent.com/80264351/236859756-a92d4555-2195-40d0-9b6c-d7715986e960.png)


# Web Scraping for Common Words in a Novel
Web scraping is a powerful method for collecting data across the web. In this project, I use Python to web scrape a novel and count the most common words. The goal is to answer the question, "What are the most common words in the Moby Dick novel?" By analyzing the most frequent words in a novel, we can gain insight into its themes, characters, and plot.

# Steps Taken During the Project
## 1. Ask a Question
I started this project by asking a question: "What are the most common words in the Moby Dick novel?" This question was driven by my curiosity to understand the themes, characters, and plot of the novel.

## 2. Get Your Data
  To collect the data, I used Python's __'requests'__ library. __'requests'__ is an awesome and popular library that is used by
giant tech companies such as Netflix. It's easy to use and provides a simple and intuitive API for making HTTP requests, making it easy for developers to send requests and receive responses from servers.

## 3. Wrangle the Data
Python has many tools for data wrangling such as __'pandas'__, __'numpy'__, and more. For this project, I used __'BeautifulSoup'__ to extract the relevant text from the novel's HTML page. I also used natural language processing techniques to remove common words such as "he," "they," "a," and "and."

## 4. Answer the Question
Looking at long rows of text or numbers can be tiring to the eye. Therefore, the best way to answer this question is by visualizing the data. I used __'Seaborn'__ and __'Matplotlib'__ to create a chart that shows the most common words in the novel.

## 5. Present Your Solution
I designed the chart to be easy to understand. Below is a list of books with the most common words. I also created a function that allows the user to remove common words that may have been missed by the natural language processing.
