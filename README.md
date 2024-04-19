# Semantic Based Video📺 Subtitle Search engine

<p align="center">
    <img width="800" src="https://github.com/HannahIgboke/Semantic-Based-Video-Subtitle-Search-engine/blob/main/Images/Search.jpg" alt="Search">
</p>

# Note

This is a team project between [Sarthak Agrawal](https://github.com/IamME1311) and [myself](https://github.com/HannahIgboke) during our internship at [Innomatics Research Labs](https://www.linkedin.com/school/innomatics-research-labs/mycompany/).


# Background

In the fast-evolving landscape of digital content, effective search engines play a pivotal role in connecting users with relevant information. Example, for Google, providing a seamless and accurate search experience is paramount. This project focuses on improving the search relevance for video subtitles, enhancing the accessibility of video content.

# Problem⁉

There is a difficulty of finding relevant video content through traditional keyword-based search methods when searching for subtitles. Currently, most search engines rely on keywords within video titles, descriptions, or closed captions. However, this approach is not ideal for finding specific content within a video based on dialogue or spoken information.

# Objective

Develop an advanced search engine algorithm that efficiently retrieves subtitles based on user queries, with a specific emphasis on subtitle content. The primary goal is to leverage natural language processing and machine learning techniques to enhance the relevance and accuracy of search results by building a semantic search engine.

# About the data

The database provided contained a sample of 82,498 subtitle files from opensubtitles.org. Most of the subtitles are of movies and TV-series which were released after 1990 and before 2024.

Database File Name: eng_subtitles_database.db

Database contains a table called 'zipfiles' with three columns:
- num: Unique Subtitle ID reference for www.opensubtitles.org 
- name: Subtitle File Name
- content: Subtitle files were compressed and stored as a binary using 'latin-1' encoding.

# Project steps🪜

Below is an outline of the steps taken to meet the project's objective:

1. Reading the Data from the Database – decompressing and decoding
2. Data cleaning
3. Data chunking
4. Generating text embedding
5. Storing data in a vector database (vector stores)
6. Frontend application to access the Search Engine

Find the comprehensive documentation of these steps [here](https://github.com/HannahIgboke/Semantic-Based-Video-Subtitle-Search-engine/blob/main/Search_Engine_Final.ipynb)

# Tech stack🛠

In the course of this project the following tools and languages were utilized:

- Python
- ChromaDB
- Natural Language Processing
- Streamlit 
- Google Colab

You can also find the project report [here](https://github.com/HannahIgboke/Semantic-Based-Video-Subtitle-Search-engine/blob/main/Semantic%20based%20search%20engine%20-%20Report.pdf) as well.


# Final output

Below is the final ouput of our project - an interactive web application.

<p align="center">
    <img width="800" src="https://github.com/HannahIgboke/Semantic-Based-Video-Subtitle-Search-engine/blob/main/Images/Final%20output%201.JPG" alt="Final output 1">
</p>


The figure below shows the redirection to the OpenSubtitles.org page 
<p align="center">
    <img width="500" src="https://github.com/HannahIgboke/Semantic-Based-Video-Subtitle-Search-engine/blob/main/Images/Final%20output%202.JPG" alt="Final output 2">
</p>


# Conclusion

In this project we built an MVP (Minimum Viable Product) that bridges the gap between a user’s search intent and the content of video subtitles. We did this by utilizing techniques like light cleaning to preserve contextual meanings, semantic chunking on our subtitle files to mitigate information loss and created an iterative web app to test our solution. This is a glimpse of what can be done in building a semantic based search engine for video subtitles. We encourage exploring this concept deeper in building a more robust search engine.

