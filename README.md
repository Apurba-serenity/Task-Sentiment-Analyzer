
---

# Task Sentiment Analyzer

A simple and efficient **Sentiment Analysis Tool** to analyze the sentiment of tasks, comments, or user feedback. This Python-based tool uses the **TextBlob** library to evaluate the sentiment and provides a detailed report with **Polarity** and **Subjectivity** scores.

---

## Features

- **Analyze Sentiment**: Detect whether the text sentiment is **Positive**, **Neutral**, or **Negative**.
- **Detailed Scoring**:
  - **Polarity**: Indicates sentiment strength on a scale from -1 (negative) to +1 (positive).
  - **Subjectivity**: Measures how subjective (personal opinion) or objective the text is.
- **Clean and Preprocess Text**: Removes special characters and extra whitespace for accurate analysis.
- **Interactive Console**: User-friendly interface to analyze single or multiple text inputs.
- **Beginner-Friendly**: Designed for easy understanding and modification.

---

## How It Works

### 1. Sentiment Analysis
- **Positive Sentiment**: Polarity > 0
- **Neutral Sentiment**: Polarity = 0
- **Negative Sentiment**: Polarity < 0

### 2. Preprocessing
- Removes special characters (e.g., punctuation).
- Converts text to lowercase for consistent analysis.

---

## Installation and Usage

### Prerequisites
Ensure you have **Python 3.x** installed on your system.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Apurba-serenity/task-sentiment-analyzer.git
   ```
2. Navigate to the project folder:
   ```bash
   cd task-sentiment-analyzer
   ```
3. Install the required Python library:
   ```bash
   pip install textblob
   ```

### Running the Program
1. Start the analyzer:
   ```bash
   python sentiment_analyzer.py
   ```
2. Follow the interactive prompts to:
   - Analyze a single text.
   - Analyze multiple texts.

---

## Example Output

### Single Text Analysis:
```plaintext
Enter the text to analyze: I love learning Python!
Analysis Results:
--------------------------------------------------
Text: I love learning Python!
Sentiment: POSITIVE
Polarity Score: 0.50
Subjectivity Score: 0.60
```

### Multiple Text Analysis:
```plaintext
Enter text #1: I am so excited about this project!
Enter text #2: This task is stressful but manageable.

Analysis Results:
--------------------------------------------------
Text: I am so excited about this project!
Sentiment: POSITIVE
Polarity Score: 0.75
Subjectivity Score: 0.80

Text: This task is stressful but manageable.
Sentiment: NEUTRAL
Polarity Score: 0.00
Subjectivity Score: 0.50
```

---

## Contribution

Contributions are welcome! If you have ideas to enhance the tool, feel free to:
1. Fork this repository.
2. Create a feature branch.
3. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## About the Creator

Created with 💻 by **Apurba**  
Feel free to connect or contribute!  

GitHub Profile: [Apurba-serenity](https://github.com/Apurba-serenity)

---

