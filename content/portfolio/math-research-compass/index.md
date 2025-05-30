---
title: Math Research Compass
date: 2025-05-30
type: portfolio
# external_link: https://mathresearchcompass.com
tags:
  - Topic Modeling
  - arXiv
  - NLP
  - BERTopic
  - Research Tools
  - Full Stack
  - Database Optimization
  - Production Deployment
---

A production data dashboard analyzing mathematical research trends across 290,000+ arXiv papers. This full-stack application uses advanced topic modeling and NLP to map the thematic landscape of modern mathematical research, deployed with professional infrastructure and custom domain.

<!--more-->

## Overview

Math Research Compass transforms the vast landscape of mathematical research into an interactive, explorable dashboard. By analyzing nearly 300,000 arXiv mathematics papers from the past five years, the application identifies 1,938 distinct research topics and presents them through an intuitive web interface.

## Key Features

**Interactive Topic Exploration:**
- Browse 1,938 discovered research topics across 31 mathematical subfields
- Dynamic filtering by arXiv categories (algebraic geometry, number theory, etc.)
- Detailed topic views with top contributing authors and representative papers
- Real-time category distribution analysis

**Advanced Analytics:**
- AI-enhanced topic labeling using Claude for human-readable descriptions
- Author productivity rankings and collaboration patterns
- Research trend identification across mathematical disciplines
- Cross-category thematic analysis

**Professional Web Application:**
- Lightning-fast performance with optimized SQLite database architecture
- 5x improvement in interactive response times through indexed queries and LRU caching
- Custom domain with SSL certificates (mathresearchcompass.com)
- Production deployment on Heroku with professional reliability

## Technical Architecture

**Data Pipeline:**
- ArXiv metadata ingestion and preprocessing (290K+ papers)
- Advanced topic modeling with BERTopic, UMAP, and HDBSCAN clustering
- Claude AI integration for enhanced topic labeling and interpretation
- Comprehensive data validation and quality assurance

**Backend Optimization:**
- Optimized SQLite database with indexed tables and connection pooling
- LRU caching for frequent queries achieving sub-second response times
- Efficient data structures supporting real-time filtering and aggregation
- Memory optimization for handling large-scale academic datasets

**Frontend Development:**
- Interactive Shiny dashboard with responsive design
- Dynamic visualizations using Plotly for data exploration
- Intuitive user interface supporting both overview and detailed analysis
- Mobile-responsive design for accessibility across devices

**Production Infrastructure:**
- Professional deployment on Heroku with custom domain configuration
- SSL certificates and security best practices
- DNS management and domain forwarding
- Performance monitoring and optimization

## Impact and Applications

This dashboard serves multiple audiences in the mathematical research community:

- **Researchers** can identify emerging trends and potential collaboration opportunities
- **Graduate students** can explore active research areas and understand field dynamics
- **Department administrators** can analyze research productivity and focus areas
- **Funding agencies** can assess research landscape and identify investment priorities

## Future Development

Planned enhancements include:
- Collaboration network analysis with NetworkX for author relationship mapping
- Temporal trend analysis showing topic evolution over time
- Citation impact analysis (when data becomes available)
- Geographic and institutional affiliation analysis

## Links

**Live Application:** [mathresearchcompass.com](https://mathresearchcompass.com)  
**Source Code:** [GitHub Repository](https://github.com/brian-hepler-phd/MathResearchCompass)  

## Technologies Used

- **Machine Learning:** BERTopic, UMAP, HDBSCAN, Sentence Transformers
- **AI Integration:** Claude API for topic enhancement
- **Database:** SQLite with optimization and indexing
- **Web Framework:** Shiny for Python with Plotly visualizations
- **Deployment:** Heroku with custom domain and SSL
- **Data Processing:** Pandas, NumPy, advanced NLP pipelines