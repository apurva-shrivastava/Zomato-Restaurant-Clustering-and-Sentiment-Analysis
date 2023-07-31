# Zomato Restaurant Clustering and Sentiment Analysis



## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Clustering](#clustering)
- [Sentiment Analysis](#sentiment-analysis)
- [Findings](#findings)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The "Zomato Restaurant Clustering and Sentiment Analysis" project employs unsupervised learning techniques to analyze and categorize restaurants based on customer reviews and sentiments.

Zomato is a prominent restaurant aggregator platform that provides user-generated reviews, ratings, and comprehensive details about various dining establishments. In this project, our primary objective is to explore, preprocess, and analyze this rich dataset to gain valuable insights. 

We aim to cluster similar restaurants into distinct groups, enabling users to explore restaurants with similar attributes and characteristics. Additionally, we perform sentiment analysis on customer reviews to understand the overall sentiment towards different restaurants.

Understanding customer preferences and sentiments is paramount for the restaurant industry's success.

Through this unsupervised learning project, we strive to offer valuable insights to both customers and restaurant owners.

Customers can discover restaurants that align with their preferences and expectations, while restaurant owners can gain valuable feedback on their establishments and make data-driven decisions to enhance customer experiences.

## Dataset

The dataset used for this project can be obtained from [here](https://drive.google.com/file/d/1JG_8OGZ6tS-0SOstH_x3n9sN0ZI1AFNC/view?usp=drive_link) and [here](https://drive.google.com/file/d/1m4lylf_iAyxlsIW1uTGrMSuhHYwuntJl/view?usp=drive_link). 

It encompasses a wide range of information related to restaurants, including:

Restaurant information Dataset:-

Name : Name of Restaurants

Links : URL Links of Restaurants

Cost : Per person estimated Cost of dining

Collection : Tagging of Restaurants w.r.t. Zomato categories

Cuisines : Cuisines served by Restaurants

Timings : Restaurant Timings

Reviews of restaurant Dataset:-

Restaurant : Name of the Restaurant

Reviewer : Name of the Reviewer

Review : Review Text

Rating : Rating Provided by Reviewer

MetaData : Reviewer Metadata - No. of Reviews and followers

Time: Date and Time of Review

Pictures: No. of pictures posted with a review

The dataset may include additional relevant features, such as opening hours, amenities, and contact information, depending on the source.

## Installation

To run this project locally, follow these steps:

1. Copy the Colab File into your drive.


2. Run the Colab File.


## Usage

Once the project and its dependencies are installed, you can perform clustering analysis and sentiment analysis using the provided Colab Notebooks.

The main files in this repository are:

- `zomato_restaurant_analysis.ipynb`: Colab Notebook containing the step-by-step process of clustering and sentiment analysis.


Feel free to modify the code according to your needs and experiment with different clustering algorithms and sentiment analysis techniques.

## Clustering

In the Colab Notebook, we apply unsupervised learning algorithms such as K-Means, and Hierarchical Clustering to group restaurants with similar features into clusters. Clustering allows us to identify patterns in the data and discover restaurants that offer similar cuisines, have comparable ratings, or cater to similar demographics. By visualizing the clusters, we gain a deeper understanding of the restaurant landscape and identify distinct market segments.

## Sentiment Analysis

Using Natural Language Processing (NLP) techniques, we perform sentiment analysis on customer reviews to determine the overall sentiment towards each restaurant. The analysis helps identify restaurants with predominantly positive or negative feedback. Sentiment analysis provides invaluable feedback to restaurant owners, enabling them to address customer concerns and enhance their offerings based on real-time feedback.

## Findings

The results of the clustering analysis and sentiment analysis are presented in the Jupyter Notebook. Some of the key findings and insights may include:

- Identification of restaurant clusters with similar attributes, helping customers discover restaurants that match their preferences.
- Discovering popular cuisines and their association with specific locations, assisting travelers and locals in finding diverse culinary experiences.
- Understanding the sentiment towards various restaurants based on customer reviews, guiding restaurant owners in improving customer experiences, and addressing any concerns.

These findings can be utilized by customers to explore restaurants that match their preferences and by restaurant owners to understand customer sentiments and make data-driven decisions to improve their services.

## Contributing
Contributions to this project are highly encouraged! If you have any ideas for improving the clustering or sentiment analysis process, visualizations, or any other aspect of the project, please don't hesitate to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code under the terms of this license.

---

We hope this comprehensive README provides you with all the necessary information to get started with your "Zomato Restaurant Clustering and Sentiment Analysis" unsupervised learning project. Should you require any further assistance or have questions, please feel free to reach out to us.

Happy clustering and sentiment analysis of Zomato restaurants! :fork_and_knife: :grinning:
