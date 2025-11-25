---
slug: github-media-and-policy
title: Analyzing Media Coverage of Gun Control Policy Post-Parkland
repo: justin-napolitano/media-and-policy
githubUrl: https://github.com/justin-napolitano/media-and-policy
generatedAt: '2025-11-23T09:18:08.738063Z'
source: github-auto
summary: >-
  This project analyzes media coverage and its impact on gun control policy
  following the Parkland shooting, focusing on data collection and analysis
  methods.
tags:
  - media-analysis
  - policy-analysis
  - textual-data
  - gun-control
  - news-coverage
  - media analysis
  - gun control
  - NexisUni
  - textual analysis
  - natural language processing
  - data processing
  - political discourse
seoPrimaryKeyword: media coverage analysis gun control
seoSecondaryKeywords:
  - Parkland shooting media
  - political commentary analysis
  - data collection methods
  - textual data analysis
  - NLP in media studies
seoOptimized: true
topicFamily: datascience
topicFamilyConfidence: 0.9
topicFamilyNotes: >-
  The post is focused on analyzing media coverage data related to the Parkland
  shooting event using textual data analysis techniques, including consideration
  of time series and volume of news articles. This matches the datascience
  family's description of data analysis projects and scripts for economic and
  scientific data workflows, despite the analysis being mostly manual and
  qualitative.
kind: project
id: github-media-and-policy
---

# Media and Policy: An Analytical Reference

## Motivation

The project addresses the intersection of media coverage and gun control policy by focusing on the Parkland shooting event of February 14, 2018. This incident generated extensive media attention and catalyzed political discourse around gun legislation. The motivation is to understand the volume, timing, and framing of media reports in response to a high-profile event that influenced public policy debates.

## Problem Statement

Media coverage of significant events often blends factual reporting with political agendas, complicating efforts to analyze the media's role in shaping policy discourse. The challenge lies in distinguishing between straightforward event reporting and politically motivated commentary. This repository attempts to aggregate and narrow down media articles to those directly related to the incident and its immediate aftermath.

## Project Construction

The project is constructed around a textual data file (`full-text`) that documents an initial analysis of news article counts and publication dates related to the Parkland shooting. Data was sourced from NexisUni, focusing on prominent newspapers such as The New York Times, The Washington Post, and the Los Angeles Times.

The approach involved:

- Conducting keyword searches ("Parkland && Shooting") to identify relevant articles.
- Filtering results by date to isolate immediate event coverage (February 14–17, 2018).
- Recognizing limitations in automated classification, leading to a decision to generalize findings rather than manually reviewing each article.

## Implementation Details

- The textual analysis highlights the volume of media coverage, noting over 10,000 news results initially, with approximately 406 articles published in the immediate days following the shooting.
- The data suggests continuous media attention extending months beyond the event, shifting focus from factual reporting to political and social responses.
- The repository does not include automated tools or scripts; the analysis appears manual and qualitative.

## Practical Considerations

For developers or analysts returning to this project, the key takeaway is the need for more sophisticated data processing to differentiate between event reporting and political commentary. Future work should prioritize:

- Implementing natural language processing techniques to classify article content.
- Automating data collection and filtering pipelines.
- Expanding the scope to include sentiment analysis or discourse framing.

This project serves as a foundational reference point for understanding the complexities of media influence on policy through the lens of a specific, high-impact event.

