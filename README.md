# Resume Screening Assistant

This project uses FLAN-T5 (a Google transformer model) to automatically classify resumes into categories like Data Science, Human Resources, or Software Development.

## 🚀 Features
- Classifies resumes from PDF or CSV
- Uses Natural Language Processing (NLP)
- Built with Google Colab and Hugging Face Transformers

## 🧪 Technologies Used
- Python
- Hugging Face Transformers
- FLAN-T5
- Pandas
- PDFPlumber
- Google Colab

## ▶️ Run in Google Colab
Click below to open the notebook in Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vztbkO0Rp8EeNOFS7q59yxvk5nCFYeAe#scrollTo=Sy6zr79E_PwB&line=7&uniqifier=1)

## 📦 Installation
```bash
pip install transformers pandas pdfplumber
## 📂 Usage
1. Upload resumes as PDFs or a CSV with a column named `resume_text`.
2. The model will process and classify each resume.
3. The results will be saved to a CSV and automatically downloaded.

## 📄 Output
- `classified_resumes.csv` for CSV input
- `pdf_resume_classification.csv` for PDF input

## 📃 License
MIT License
## 📸 Screenshots

### Upload Prompt
![Upload Prompt](screenshots/uploadprompt.png)

### Output
![Output](screenshots/output_csv.png)



