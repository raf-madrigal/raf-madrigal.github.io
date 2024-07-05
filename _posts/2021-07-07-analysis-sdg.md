---
layout: post
title: "SDG News Articles Topic Modeling"
categories: nlp
permalink: /posts/sdg-topic-modeling
---


### Summary
Identifying Global Gaps in Sustainable Development Goals (SDGs) Achievement Through Topic Modeling of News Articles

### Background
In 2015, the United Nations established 17 Sustainable Development Goals (SDGs) with 169 targets and 232 unique indicators to be achieved by member states by 2030. The increasing interest in sustainable development stems from economic instability, finite resources, and environmental challenges. However, assessing and tracking sustainability indicators is often expensive and time-consuming.

### Business Challenge
The primary challenge lies in efficiently measuring progress towards achieving Sustainable Development targets. Traditional methods of assessment are resource-intensive, making it difficult to get a timely and comprehensive view of global efforts. There's a need for an innovative approach to identify gaps in SDG achievement using readily available data.

### Goals
- Measure success in achieving Sustainable Development targets through Topic Modeling.
- Focus on 5 SDGs related to the environment (SDGs 6, 7, 13, 14, and 15).
- Identify gaps in global efforts towards SDG achievement.
- Provide insights to guide future initiatives and resource allocation.

### Solutions
- Data Collection: Scraped 1000 latest news articles from the SDG Knowledge Hub.
- Natural Language Preprocessing: Applied techniques such as stopword removal, punctuation elimination, accent mark removal, contraction expansion, and removal of dates and comments.
- Tokenization and N-gram Modeling: Used Gensim for tokenization and building n-gram models.
- Topic Modeling: Employed Latent Dirichlet Allocation (LDA) to generate topics for each SDG subset.
- Gap Analysis: Identified gaps in SDG achievement by comparing generated topics with SDG targets.

### Results
The study identified several gaps across the analyzed SDGs:
- SDG 6 (Clean Water and Sanitation): Gaps in strengthening wastewater treatment, water resources management, and protection of water-related ecosystems.
- SDG 7 (Affordable and Clean Energy): Gap in strengthening the expansion of energy services in developing countries.
- SDG 13 (Climate Action): Gap in strengthening resilience and adaptive capacity to climate-related disasters.
- SDG 14 (Life Below Water): Gaps in reducing ocean acidification and promoting sustainable fishing.
- SDG 15 (Life on Land): Gaps in restoring degraded land and eliminating poaching and trafficking of protected species.

### Conclusion
The project successfully utilized topic modeling on news articles to identify gaps in global efforts towards achieving SDGs. Common themes across all SDGs included Voluntary National Reviews, SDG Program Initiatives, and monitoring of SDG programs progress reports. This approach provides a cost-effective and scalable method for assessing SDG progress and highlighting areas needing more attention.

### Tools
- Python: For data extraction, preprocessing, and analysis.
- Natural Language Processing techniques: For text preprocessing.
- Gensim: For tokenization and n-gram modeling.
- Latent Dirichlet Allocation (LDA): For topic modeling.

### Future Recommendations
- Perform frequent itemset mining and association rule or clustering to identify co-occurring topics.
- Conduct sentiment analysis on each topic to understand tonality and polarity.
- Extend the dataset to span from 2015 to present and analyze other SDGs.
- Explore other topic modeling algorithms such as Hierarchical LDA.
- Include SDG-related news articles from major news outlets to broaden the analysis.

This innovative approach to SDG progress assessment offers valuable insights for policymakers, NGOs, and researchers working towards sustainable development goals.