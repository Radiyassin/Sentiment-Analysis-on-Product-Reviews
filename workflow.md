🔧 System Workflow
User Uploads CSV

# 🔧 System Workflow

## 1. User Uploads CSV

- CSV contains at least one column with the review text.

## 2. Preprocessing

- Clean text (remove special chars, lowercase, etc.)
- Optional: language filtering, stopword removal

## 3. Aspect Extraction (ML/Transformer-based)

Use a pretrained or fine-tuned model to identify common aspects like:

- Battery
- Camera
- Screen/Display
- Performance/Speed
- Design
- Price/Value
- Storage
- Sound

## 4. Sentiment Classification

Predict sentiment (positive, neutral, negative) per aspect using:

- Fine-tuned BERT or RoBERTa models (Hugging Face)
- Custom classifier for each aspect (if necessary)

## 5. Aggregation

- Count total positive/negative reviews overall
- Count positive/negative sentiments per aspect

## 6. Visualization (using plotly, matplotlib, or seaborn)

- Bar chart: Number of positive/negative reviews by aspect
- Pie chart: Overall sentiment distribution
- Time series (optional): Sentiment evolution over time

CSV contains at least one column with the review text.

Preprocessing

Clean text (remove special chars, lowercase, etc.)

Optional: language filtering, stopword removal

Aspect Extraction (ML/Transformer-based)

Use a pretrained or fine-tuned model to identify common aspects like:

Battery

Camera

Screen/Display

Performance/Speed

Design

Price/Value

Storage

Sound

Sentiment Classification

Predict sentiment (positive, neutral, negative) per aspect using:

Fine-tuned BERT or RoBERTa models (Hugging Face)

Custom classifier for each aspect (if necessary)

Aggregation

Count total positive/negative reviews overall

Count positive/negative sentiments per aspect

Visualization (using plotly, matplotlib, or seaborn)

Bar chart: Number of positive/negative reviews by aspect

Pie chart: Overall sentiment distribution

Time series (optional): Sentiment evolution over time
