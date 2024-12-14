# Sephora Review Sentiment Analysis Case Study

![image](https://github.com/user-attachments/assets/f713537a-b627-46a6-8ca4-25f08c6fa3bb)

  This project is exploring customer perception of several types of skincare products, namely moisturizer, sunscreens, and cleansers, as prices increase, according to reviews submitted on Sephora’s website through sentiment analysis.

## Context

Before doing anything, read the 2 files within the Reference Materials folder. The CS3 Hook Document provides context for this project, while the CS3 Rubric details the specific benchmarks needed to meet specifications on this assignment.



## Documentation

- **Articles folder:** a folder containing articles contectualizing the project
  - *ConsumerReviews.pdf:* an article explaining the role of reviews and ratings on consumer activilty
  - *SentimentAnalysisInfo.pdf:* an article describing and demonstrating one application of sentiment analysis using the VADER package
- **Data folder:** a folder containing the following 3 files
  - *Data Instructions.pdf:* a pdf file detailing how to obtain and clean the data
  - *Data Appendix.pdf:* a pdf file containing information about the dataset (variables, observations, etc.)
- **Reference Materials folder:** a folder containing the reference materials
  - *CS3 Hook Document.pdf:* a file providing context to the project
  - *CS3 Rubric.pdf:* a file dtailing to benchmarks needed to meet specifications for this assignment
- **Scripts folder:** a folder containing the following files
  - *Sentiment_review_analysis.ipynb:* a file completing the sentiment analysis on the reviews about each product
  - *Sentiment_review_plots.ipynb:* a file completing the visualizations summarizing the sentiment analysis
  - *dataset_construction.ipynb:* a file compiling and cleaning the dataset for analysis
- **LICENSE.md:** a file citing the terms under which this repository may be used and cited
- **README.md:** a file containing all information about the files within the repository

## Producing Results

The most simple way to conduct the analysis is through using Google Colab. You are welcome to use VSCode or Jupyter Notebook, but you will likely have to download some of the packages utilized in the script.

In order to produce the results of this study, first read and follow the instructions in the Data Instructions pdf located in the Data folder. Output the resulting dataset onto your device. Then read the resulting dataset into the Sentiment_review_analysis by replacing the value within the parenthesis of the read_csv() function with the file path to the dataset on your device. Run the edited Sentiment_review_analysis file and the analysis will be complete and compiled into a dataset that can also be outputted to your device to make the visualizations. You then run the Sentiment_review_plot file to make the visualizations.

## References

[1] “Welcome to Vadersentiment’s documentation!,” Welcome to VaderSentiment’s
documentation! - VaderSentiment 3.3.1 documentation,
https://vadersentiment.readthedocs.io/en/latest/

‌
[2] Nady Inky, "Sephora Products and Skincare Reviews", March, 2023, https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data

[3] L. Geetha, “Vader: A Comprehensive Guide to Sentiment Analysis in Python,” Medium, Feb. 28, 2023. https://medium.com/@rslavanyageetha/vader-a-comprehensive-guide-to-sentiment-analysis-in-python-c4f1868b0d2e

[4] Dima Raketa, “How Reviews And Ratings Affect Clients’ Buying Decisions,” Forbes, Aug. 12, 2024. Available: https://www.forbes.com/councils/forbesbusinessdevelopmentcouncil/2024/07/11/how-reviews-and-ratings-affect-clients-buying-decisions/
‌
