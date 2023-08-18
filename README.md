# AIDIFINALS
Analysis on a research paper about Offensive language.
# Predicting the Type and Target of Offensive Posts in Social Media

## Group Member
- Sakshi Sushilkumar Patel

## Introduction

This project focuses on the identification and categorization of offensive language on social media platforms, particularly Twitter. The goal is to predict both the type and target of offensive posts using machine learning techniques.

## Aim

The aim of this project is to perform data preparation, data visualization, and modeling tasks for the identification and categorization of offensive language on social media (Twitter).

## Github Repo

[Offenseval GitHub Repository](https://github.com/joeykay9/offenseval)

## Description of the Paper

Offensive content has become a prevalent issue in social media, prompting significant research efforts in identifying such content. However, previous studies often concentrated on specific types of offensive content, like hate speech or cyberbullying, without addressing the problem comprehensively. In this project, we tackle various forms of offensive content, employing a hierarchical approach to identify both the type and target of offensive messages.

## Problem Statement

To address this challenge, we introduce the Offensive Language Identification Dataset (OLID), which includes annotated tweets categorized using a fine-grained three-layer annotation scheme. We compare OLID with existing datasets for hate speech identification and aggression detection. We also experiment with different machine learning models on OLID to evaluate their performance.

## Context of the Problem

Offensive content is a growing concern on social media platforms. While previous research focused on specific offensive content types, this project introduces the Offensive Language Identification Dataset (OLID). This dataset features fine-grained annotation, enabling the identification of offensive content type and target, thus providing a more nuanced analysis of offensive language in social media.

## Solution

### Compilation of OLID Dataset

The Offensive Language Identification Dataset (OLID) is a diverse collection of tweets with fine-grained annotations. A three-layer annotation scheme categorizes offensive messages based on their type and target, enhancing our understanding of different offensive contexts.

### Hierarchical Modeling

The project employs a hierarchical modeling approach, addressing offensive content identification in multiple layers. The first layer identifies the offensive content type (e.g., hate speech, aggression), followed by identifying the target of the offensive message (e.g., individual, group, topic).

### Machine Learning Models

We explore various machine learning models, including Naive Bayes, Support Vector Machines, Random Forest, and potentially deep learning models like LSTM or BERT. These models are evaluated on the OLID dataset to achieve accurate results.

### Performance Comparison

The performance of different machine learning models is compared on the OLID dataset, evaluating accuracy, precision, recall, and F1-score. This comparison provides insights into model effectiveness for offensive content identification tasks.

### Insights and Recommendations

The project's results offer insights into effective models for identifying offensive content. Based on these findings, recommendations can guide the selection of models for specific offensive content identification tasks.

By adopting a hierarchical modeling approach and utilizing the OLID dataset, this solution aims to enhance the understanding and identification of offensive language in social media. The fine-grained annotation scheme and performance comparison contribute to a comprehensive approach to addressing the pervasive issue of offensive content.

## License

This project is licensed under the [MIT License](LICENSE).
