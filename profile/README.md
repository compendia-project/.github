# Compendia Project 📊

**Automated Data Story Generation from Online Article Collection**

Compendia is an intelligent system that automatically generates compelling data stories by crawling, analyzing, and synthesizing information from online articles. The project combines advanced AI techniques with modern web technologies to transform raw web content into structured, narrative-driven data visualizations.

## 🚀 Project Overview

The Compendia Project consists of two main components:

### 🔧 Backend (compendia-backend)
A Python FastAPI-based service that handles the core data processing pipeline:

- **Article Crawling**: Automated collection of articles from specified websites
- **Fact Extraction**: AI-powered extraction and filtering of relevant information
- **Data Processing**: Validation, refinement, and organization of extracted facts
- **Story Generation**: Intelligent clustering and narrative creation
- **Visualization**: Automated generation of charts, wordclouds, and visual elements

**Key Features:**
- Multi-stage processing pipeline with logging and error handling
- Concurrent processing for improved performance
- Flexible search query system with country-specific results
- RESTful API endpoints for frontend integration
- Comprehensive prompt engineering for AI-driven content generation

### 🎨 Frontend (compendia-frontend)
A modern Svelte-based web application that provides an intuitive interface:

- **Interactive UI**: Clean, responsive design for story exploration
- **Data Visualization**: Integration with D3.js and Chart.js for dynamic charts
- **Real-time Updates**: Live preview of generated stories
- **Modern Stack**: Built with SvelteKit, Vite, and modern web technologies

## 🛠️ Technology Stack

**Backend:**
- Python 3.x with FastAPI
- AI/ML integration for content processing
- Concurrent processing with ThreadPoolExecutor
- CSV/JSON data handling
- CORS-enabled API

**Frontend:**
- SvelteKit framework
- D3.js for data visualization
- LayerCake for chart components
- Vite for build tooling
- Modern CSS with autoprefixer

## 🎯 Use Cases

- **Market Intelligence**: Generate insights from industry reports and news
- **Content Creation**: Transform complex topics into engaging, data-driven narratives
- **Business Intelligence**: Extract actionable insights from web-based information

## 🌟 Key Capabilities

1. **Intelligent Content Extraction**: Advanced AI algorithms identify and extract relevant facts from web articles
2. **Automated Fact Validation**: Multi-stage validation ensures data accuracy and reliability
3. **Smart Clustering**: Groups related information to create coherent narrative structures
4. **Visual Story Generation**: Automatically creates charts, graphs, and visual elements
5. **Narrative Synthesis**: Generates human-readable stories from structured data
6. **Scalable Architecture**: Handles multiple concurrent requests with efficient processing

## 📈 Workflow

1. **Query Input**: User provides search terms and target websites
2. **Article Collection**: System crawls and collects relevant articles
3. **Content Processing**: AI extracts, validates, and refines factual information
4. **Data Organization**: Facts are clustered and organized into coherent themes
5. **Story Generation**: Narrative structures are created with supporting visualizations
6. **Presentation**: Final story is rendered with interactive elements and visual components

---

*Compendia transforms the way we consume and understand information by automatically creating data-driven stories from the vast ocean of online content.*
