# Sentiment Analysis using BeautifulSoup and NLTK

## 📌 Overview
This project performs sentiment analysis on web articles by scraping content using **BeautifulSoup** and analyzing the text using **NLTK** and **TextBlob**. The analysis calculates sentiment scores and various linguistic features, which are saved in an Excel output file.

## 🛠️ Features
- Scrapes article text from provided URLs using **BeautifulSoup**
- Tokenizes text using **NLTK**
- Performs sentiment analysis using **TextBlob**
- Computes linguistic features like polarity, subjectivity, and readability metrics
- Saves the results in an **Excel file** for further analysis

## 🗂️ Project Structure
```
📂 Sentiment-Analysis  
 ├── 📄 Text Analysis.py  # Main script for scraping and analysis  
 ├── 📊 Output.xlsx       # Processed results stored in an Excel file  
 ├── 📄 README.md         # Project documentation  
 ├── 📂 input.xlsx        # Input file with article URLs  
 ├── 📄 positive-words.txt # List of positive words  
 ├── 📄 negative-words.txt # List of negative words  
```

## 🚀 Installation
### 1️⃣ Install dependencies
Make sure you have Python installed. Then, install the required libraries:
```sh
pip install beautifulsoup4 requests nltk textblob openpyxl
```

### 2️⃣ Run the script
```sh
python Text\ Text Analysis.py
```

## 📊 Sentiment Analysis Metrics
| Metric                   | Description |
|--------------------------|-------------|
| **Positive Score**       | Count of positive words in the text |
| **Negative Score**       | Count of negative words in the text |
| **Polarity Score**       | Overall sentiment of the text (-1 to 1) |
| **Subjectivity Score**   | Degree of personal opinion in the text (0 to 1) |
| **Fog Index**            | Readability score based on sentence length and complexity |
| **Average Sentence Length** | Average number of words per sentence |
| **Percentage of Complex Words** | Ratio of complex words in the text |
| **Word Count**           | Total words in the article |

## 📝 Output
The final sentiment analysis results are stored in **Output.xlsx**, which includes URL IDs, sentiment scores, and readability metrics.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Repository Owner
Maintained by [Sajid Tamboli] - feel free to reach out for collaboration!

## 🤝 Contributing
Feel free to open an issue or submit a pull request for improvements!
