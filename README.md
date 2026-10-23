# Phishing URL Detection Using Machine Learning

## Project description
This beginner-level cybersecurity project demonstrates a machine-learning workflow that classifies example URLs as likely legitimate or suspicious/phishing using simple URL features.

## Dataset
The project uses the included `phishing_urls.csv` sample dataset. The dataset is illustrative and small; it is not a verified real-world phishing feed.

## Technologies used
- Python
- Jupyter Notebook
- pandas
- scikit-learn
- Python standard library (`re`, `urllib.parse`)

## Setup and run instructions
1. Install Python 3.10 or later.
2. Keep `Phishing_URL_Detection.ipynb`, `phishing_urls.csv`, and `requirements.txt` in the same folder.
3. Install dependencies by running: `pip install -r requirements.txt`
4. Start Jupyter Notebook: `jupyter notebook`
5. Open `Phishing_URL_Detection.ipynb` and run the cells from top to bottom.

## Files
- `Phishing_URL_Detection.ipynb`: code and model workflow.
- `phishing_urls.csv`: labelled example dataset (`0` = legitimate example, `1` = suspicious/phishing example).
- `requirements.txt`: Python dependencies.
- `Sanskruti_ProjectReport.docx`: project report.

## Limitations and safety
The included dataset is only for demonstrating the workflow and cannot establish real-world accuracy. URL patterns can produce false positives and false negatives. Do not open suspicious links to test them, and do not treat the model's prediction as proof that a website is safe. A real evaluation would require a larger, recent, properly licensed dataset and testing on unseen domains.
