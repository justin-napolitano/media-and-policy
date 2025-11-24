---
slug: github-media-and-policy-writing-overview
id: github-media-and-policy-writing-overview
title: 'Analyzing Media Coverage and Gun Control: My "media-and-policy" Repo'
repo: justin-napolitano/media-and-policy
githubUrl: https://github.com/justin-napolitano/media-and-policy
generatedAt: '2025-11-24T17:41:42.498Z'
source: github-auto
summary: >-
  I've been diving into the relationship between media coverage and gun control
  policy, particularly through the lens of the Parkland shooting on February 14,
  2018. This GitHub repository, "media-and-policy," is my playground for
  examining the political and social responses that followed this tragic event.
  If you find yourself wrestling with media narratives and policies, let me walk
  you through what this project entails and where I plan to take it next.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: writing
entryLayout: writing
showInProjects: false
showInNotes: false
showInWriting: true
showInLogs: false
---

I've been diving into the relationship between media coverage and gun control policy, particularly through the lens of the Parkland shooting on February 14, 2018. This GitHub repository, "media-and-policy," is my playground for examining the political and social responses that followed this tragic event. If you find yourself wrestling with media narratives and policies, let me walk you through what this project entails and where I plan to take it next.

## Why This Project Exists

The media landscape after mass shootings is chaotic. Headlines flood in, narratives develop rapidly, and opinions form almost instantaneously. I wanted to cut through the noise and explore how media coverage shapes public perception and policy responses to gun violence, specifically in this case. By aggregating and summarizing articles, I aimed to provide a clearer picture of how the media addressed the Parkland shooting and its aftermath.

## What This Repo Does

At its core, this repository focuses on collecting and analyzing media data related to the Parkland shooting. Here's what you can expect:

- **Media Coverage Collection:** I've gathered a variety of articles associated with the shooting, which serves as the foundation for my analysis.
- **Temporal Filtering:** This allows me to drill down into event-specific reporting, isolating the coverage that directly relates to Parkland.
- **Preliminary Analysis:** I’ve started to look at trends in the volume of media coverage and the themes present over time.

These features form the backbone of my exploratory analysis, giving insights into how the media narrative evolved.

## Tech Stack & Tools

The tech stack for this project is lean. I've primarily utilized the NexisUni news database to source the articles. The text data is simply stored as raw text files. While I don’t have complex tooling or code integrated yet, the repository is designed for usability. You won’t have to jump through hoops to get started. Here's how you can dig in:

1. Clone the repository:
   ```bash
   git clone https://github.com/justin-napolitano/media-and-policy.git
   ```
2. Navigate to the `full-text` file to get a look at my media analysis.

### Project Structure

The repo is straightforward, focusing on clarity and accessibility:

```
media-and-policy/
└── full-text          # Text file containing the media coverage analysis and commentary
```

## Key Design Decisions

When I was setting this up, I had to make a few design choices:

- **Simplicity:** I opted for a manual collection methodology to start. This transparency allows anyone reviewing the data to understand its origin and context.
- **Focus on Textual Data:** Instead of integrating complex data processing tools, I decided to keep the project centered around text files. This approach lets others easily review the content without needing a specific environment or software.
- **Limited Scope for Now:** The aim isn’t to create an exhaustive datasets immediately. I wanted to start with focused analysis on a single event before expanding into broader territory.

## Tradeoffs

Every choice comes with tradeoffs. Here are a few I encountered:

- **Manual Data Collection:** While this gives me precise control, it also limits the scalability of expanding the dataset. Automating this process is on my roadmap.
- **Lack of Visualizations:** Right now, it's all in text form. Adding visualizations would enhance understanding but requires more tools and effort.
- **Static Nature:** The analysis as it stands lacks interactivity. I'd love to turn this into something more engaging, maybe a dashboard with clickable elements or a live data feed.

## Future Work / Roadmap

Looking ahead, there's a lot I want to improve and add:

- **Automation:** I plan to develop scripts that will help automate the collection and classification of articles. This would streamline the process and allow me to expand the dataset effectively.
- **Broader Dataset:** I’m looking to broaden the scope beyond just Parkland. Including diverse media sources and more recent events will provide richer insights.
- **Sentiment Analysis:** Quantitative sentiment and topic modeling analysis would deepen the critical examination of the articles.
- **Visualizations:** Creating visual representations of coverage trends over time can make the findings more digestible and accessible.
- **Publication:** I’d like to encapsulate the findings in a structured format like a research paper or interactive dashboard. Making it public would foster broader discussions.

## Stay Updated

I’m continually updating my progress on this project, sharing insights on social media. If you want to follow along or contribute thoughts, catch me on Mastodon, Bluesky, or Twitter/X. Your feedback helps me refine this work and expand its impact.

To sum it up, "media-and-policy" is more than just a repo. It's a step toward understanding how media influences public policy and sentiment around issues that matter deeply. Join me on this exploration, and let’s seek clarity in the chaos of media narratives together.
