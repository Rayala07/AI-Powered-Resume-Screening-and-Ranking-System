# AI-Powered Resume Screening and Ranking System
🔗 **Live Project Link:** [AI-Powered Resume Screening and Ranking System](https://ai-powered-resume-screening-and-ranking-system.streamlit.app/)

## Overview

The **AI-Powered Resume Screening and Ranking System** is a **Streamlit-based web application** designed to automate the recruitment process by analyzing and ranking resumes based on job descriptions. Using **Natural Language Processing (NLP)** and **TF-IDF with Cosine Similarity**, the system extracts and evaluates relevant information from resumes to determine the best candidates for a given job role.

## Features

- **Resume Parsing**: Extracts text from PDF resumes using **PyPDF2**.
- **Candidate Ranking**: Uses **TF-IDF Vectorization** and **Cosine Similarity** to rank resumes.
- **Web-Based Interface**: Built with **Streamlit** for easy user interaction.
- **Automated Resume Screening**: Reduces manual effort by providing instant candidate rankings.

## Tech Stack

- **Backend & Frontend**: Streamlit (Python)
- **NLP & Text Processing**: Scikit-learn (TF-IDF), Cosine Similarity
- **File Handling**: PyPDF2 (for PDF text extraction)
- **Data Handling**: Pandas

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/NeelBorad00/AI-powered-Resume-Screening-and-Ranking-System.git
cd AI-powered-Resume-Screening-and-Ranking-System
```

### 2. Set Up a Virtual Environment

```bash
python -m venv env
source env/bin/activate  # On Windows, use 'env\Scripts\activate'
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

Access the application at `http://localhost:8501/` in your web browser.

## Usage

1. **Enter Job Description**: Provide the job role requirements.
2. **Upload Resumes**: Upload multiple resumes in **PDF format**.
3. **Candidate Ranking**: The system extracts text, compares resumes to the job description, and ranks them based on relevance.
4. **View Results**: The ranked resumes are displayed in a structured table.

## Project Structure

```
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
```

## Future Enhancements

- **Integration with Machine Learning Models** for better resume ranking.
- **Support for Multiple File Formats** (e.g., DOCX, TXT).
- **Enhanced UI & Visualization** using interactive charts.

## Contact

**Neel Borad**  
Email: neelborad00@gmail.com  
GitHub: [NeelBorad00](https://github.com/NeelBorad00)

---
