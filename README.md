# Scielo_Journal_Metadata_Downoader
This Jupyter notebooks present some functions to download all the articles from a journal in the SCielo database, and use the XML JATS protocol to classify the articles.

There are three Jypiter notebooks on this repository so far. **Download Articles** will download all the articles of a specific scientific journal indexed in SCielo provided the link to that journal. **Article Metadata to DataFrame** will create a DataFrame object in Pandas and store a local csv file on your devise including the most relevant metadata of each article such as authors name, data of publication, keywords, abstract and so on. Finally, **Extract Article Text** will extract the article text to a txt format in a local folder. This could be very useful if you want to develop Natural Language Processing to the texts, of corpus linguistics. 

## Requirements
To execute these notebooks you required to have Python 3.X installed aswell as BeautifulSoup and Pandas. 

