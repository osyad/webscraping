
![Web_Scraping_for_Common_Words_in_a_Novel](https://user-images.githubusercontent.com/80264351/236859756-a92d4555-2195-40d0-9b6c-d7715986e960.png)

<iframe title="NCAA Profit and Losses Summarized" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=99e4880d-5446-41b2-9fbf-242537bd460b&autoAuth=true&ctid=a0552c99-dfde-4735-98e6-23a96e2b9e32" frameborder="0" allowFullScreen="true"></iframe>
# Introduction
Web scraping is a powerful method for collecting data across the web. In this project, I use Python to web scrape a novel and count the most common words. The goal is to answer the question, "What are the most common words in the Moby Dickor the Whale novel?" By analyzing the most frequent words in a novel, we can gain insight into its themes, characters, and plot.

# Steps Taken During the Project
## 1. Ask a Question
I started this project by asking a question: "What are the most common words in the Moby Dick novel?" This question was driven by my curiosity to understand the themes, characters, and plot of the novel.

## 2. Get Your Data
  The source of this data is https://www.gutenberg.org/ which is an awesome site with a great collection of books. To collect the data, I used Python's __'requests'__ library. __'requests'__ is an awesome and popular library that is used by giant tech companies such as Netflix. It's easy to use and provides a simple and intuitive API for making HTTP requests, making it easy for developers to send requests and receive responses from servers.

<img src="https://user-images.githubusercontent.com/80264351/236862522-d57818a5-fde6-44c9-bc9f-f311052ab9bd.png" alt="Banner" width="30%" height="30%">

## 3. Wrangle the Data
Python has many tools for data wrangling such as __'pandas'__, __'numpy'__, and more. For this project, I used __'BeautifulSoup'__ to extract the relevant text from the novel's HTML page. I also used natural language processing techniques to remove common words such as "he," "they," "a," and "and."

## 4. Answer the Question
Looking at long rows of text or numbers can be tiring to the eye. Therefore, the best way to answer this question is by visualizing the data. I used __'Seaborn'__ and __'Matplotlib'__ to create a chart that shows the most common words in the novel.
   the entire code I used for this documentaion. 
   ![code](https://user-images.githubusercontent.com/80264351/236861601-66d8ffcf-3562-44b2-bdb9-0bf898d3d24d.png)

## 5. Present Your Solution
I designed the chart to be easy to understand. Below is a list of books with the most common words. I also created a function that allows the user to remove common words that may have been missed by the natural language processing.
#### A. Moby Dick or the Whale 

![fd](https://user-images.githubusercontent.com/80264351/236865274-f713a640-9646-44c4-99e8-16e058312c52.png)

#### B. Makers of Japan by Joseph E. Morris
![carbon2](https://user-images.githubusercontent.com/80264351/236866431-7d37da7d-c639-4a06-a97a-05d6f43576e2.png)

![fd](https://user-images.githubusercontent.com/80264351/236865410-5acd2697-3044-42b3-bd6f-70597de16da7.png)

#### I wanted to remove words such as "Japan" , "men", "many" as I consider them common words 
![code1](https://user-images.githubusercontent.com/80264351/236866294-2e23d6c4-7130-4ec4-877e-92fe8490a92b.png)
![fd](https://user-images.githubusercontent.com/80264351/236865546-17fd4dab-9428-4148-828d-708727e51cf8.png)

# Conclusion 
 In conclusion, this project demonstrates the power of web scraping and natural language processing in extracting insights from text data. By scraping and analyzing the most common words in Moby Dick novel, we were able to gain insight into the themes, characters, and plot of the novel. The use of Python libraries such as requests, BeautifulSoup, pandas, and matplotlib enabled us to efficiently and effectively collect, wrangle, and visualize the data. The project also highlights the importance of data visualization in communicating insights in a clear and concise manner. Overall, this project showcases the potential of data analysis to provide valuable insights into various fields and industries.
