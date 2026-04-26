# Traveler Emotion Mining from User-Generated Travel Content

## Overview

This project analyzes large-scale YouTube comments to uncover emotional and thematic engagement patterns in destination marketing content.

Understanding traveler emotions is critical for designing effective digital experiences and content strategies. However, large volumes of user-generated content remain underutilized due to their unstructured nature. This project transforms raw textual responses into structured behavioral insights using natural language processing (NLP), topic modeling, and keyword network analysis.

A key contribution of this project is the differentiation between affective ("love") and cognitive ("like") emotional responses using keyword network structures.

---

## Project Objectives

The primary objectives of this project include:

- Extract emotional signals from large-scale YouTube comment datasets  
- Identify latent themes using topic modeling  
- Detect emotionally dominant keywords through network analysis  
- Compare emotional structures across multiple destination campaigns  
- Translate raw user-generated content into interpretable behavioral insights  

---

## Data Sources

This project analyzes YouTube comments collected from national tourism organization (NTO) promotional videos across multiple destinations.

Countries included:

- South Korea  
- Japan  
- Australia  
- Switzerland  

These datasets represent audience reactions to destination storytelling content, including music, imagery, celebrity appearance, and cultural narratives.

Each observation includes:

- Video identifier  
- Destination country  
- User comment text  

Large-scale text preprocessing was applied to standardize the data for analysis.

---

## Methods

This project integrates multiple analytical techniques into a unified NLP pipeline.

---

### Step 1 — Text Cleaning and Preprocessing

Raw YouTube comments were cleaned and standardized through:

- Lowercasing text  
- Removing punctuation and non-alphabetic characters  
- Tokenization  
- Stopword removal  

This step ensured consistent text structure for downstream modeling.

---

### Step 2 — Sentiment Analysis

Sentiment scores were calculated using:

**VADER (Valence Aware Dictionary and Sentiment Reasoner)**

Each comment was assigned a compound sentiment score representing overall emotional polarity.

Sentiment categories included:

- Positive sentiment  
- Neutral sentiment  
- Negative sentiment  

This allowed large-scale emotional pattern detection across datasets.

---

### Step 3 — Topic Modeling

Latent thematic structures were identified using:

**Latent Dirichlet Allocation (LDA)**

Topic modeling enabled the discovery of recurring thematic patterns such as:

- Cultural identity references  
- Entertainment-driven reactions  
- Emotional appreciation  
- Destination curiosity  
- Promotional engagement  

Topic modeling provided an interpretable structure for large-scale textual content.

---

### Step 4 — Keyword Network Construction

Keyword co-occurrence networks were constructed using:

**networkx**

Edges were created between keywords appearing within the same comment context.

This enabled visualization of:

- Keyword relationships  
- Emotional clusters  
- Engagement structures  

---

### Step 5 — Network Centrality Analysis

Centrality metrics were computed to identify dominant emotional signals.

Metrics included:

- Degree Centrality  
- Betweenness Centrality  
- Eigenvector Centrality  

These metrics identified emotionally influential keywords such as:

- "love"  
- "like"  
- destination-specific references  

Emotionally central keywords often represented strong engagement anchors.

---

## Example Workflow

Raw YouTube Comments
↓
Text Cleaning
↓
Sentiment Analysis (VADER)
↓
Topic Modeling (LDA)
↓
Keyword Network Construction
↓
Centrality Analysis
↓
Behavioral Insight Generation


---

## Key Findings

This project revealed several consistent behavioral patterns across destinations.

### Emotional Anchor Keywords

Emotionally dominant keywords frequently formed central nodes in keyword networks.

Examples included:

- "love" — representing affective emotional attachment  
- "like" — representing cognitive appreciation  
- destination-specific terms reflecting identity engagement  

The differentiation between "love" and "like" revealed meaningful differences in emotional intensity.

---

### Cross-Destination Emotional Patterns

Distinct emotional structures emerged across destinations.

For example:

- Music and rhythm frequently triggered affective engagement  
- Celebrity appearances influenced emotional clustering  
- Cultural imagery generated strong symbolic reactions  
- Narrative structure affected viewer attention patterns  

These results demonstrate how storytelling elements shape audience response.

---

### Network-Based Emotion Structures

Keyword networks revealed structured emotional patterns rather than isolated reactions.

Highly centralized emotional keywords suggested:

- Strong audience resonance  
- Collective emotional engagement  
- Reinforced cultural signaling  

This network-based perspective enables deeper behavioral interpretation beyond simple word counts.

---

## Business Applications

This analytical framework supports practical decision-making in digital experience and content design.

Potential applications include:

- Audience sentiment monitoring  
- Content strategy optimization  
- Marketing performance analysis  
- Cultural signal detection  
- Destination engagement analysis  

These insights are applicable to:

- Travel platforms  
- Hospitality companies  
- Digital marketing teams  
- Experience design teams  

---

## Example Outputs

Typical outputs generated by this pipeline include:

- Sentiment distribution charts  
- Topic distributions  
- Keyword network graphs  
- Centrality ranking tables  
- Destination-level emotional comparisons  

These outputs enable both quantitative and visual interpretation of audience behavior.

---

## Technical Skills Demonstrated

This project demonstrates applied expertise in:

- Natural Language Processing (NLP)  
- Sentiment Analysis  
- Topic Modeling  
- Social Network Analysis  
- Behavioral Analytics  
- Text Mining  
- Data Visualization  

---

## Tools and Libraries

Primary tools used:

- Python  
- pandas  
- nltk  
- gensim  
- networkx  
- matplotlib  

These tools supported scalable text analysis and network modeling.

---

## Reproducibility

This repository includes:

- Sample comment dataset  
- Reproducible notebook workflow  
- Example outputs  

The workflow is designed to be easily adaptable to other large-scale text datasets.

---

## Author

Jaewan Heo  
Ph.D. Candidate — Hospitality Analytics  
Natural Language Processing | Behavioral Analytics | Data Science
