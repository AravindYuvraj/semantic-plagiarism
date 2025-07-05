# Plagiarism Detector - Semantic Similarity Analyzer

A sophisticated web-based plagiarism detection tool that uses multiple embedding techniques to identify semantic similarities between texts.

## Features

- **Multi-Model Analysis**: Compare texts using Sentence Transformers, Word2Vec, TF-IDF, and Jaccard Similarity
- **Dynamic Input System**: Add/remove text inputs as needed
- **Similarity Matrix**: Visual representation of all text pair similarities
- **Clone Detection**: Automatic flagging of potential plagiarism above configurable thresholds
- **Model Comparison**: Side-by-side analysis of different embedding approaches
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Technical Implementation

### Embedding Models
- **Sentence Transformers**: Contextual embeddings for semantic understanding
- **Word2Vec**: Position-aware word embeddings
- **TF-IDF**: Term frequency-inverse document frequency analysis
- **Jaccard Similarity**: Set-based word overlap calculation

### Similarity Calculation
- Cosine similarity for vector comparisons
- Pairwise analysis of all text combinations
- Percentage-based scoring system
- Color-coded results (red=high, orange=medium, green=low)

### Clone Detection
- Configurable similarity thresholds
- Preview snippets of flagged content
- Clear visual indicators for potential issues


## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/plagiarism-detector.git
   cd plagiarism-detector
