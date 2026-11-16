# Chart_to_Text_Summarization_2330456
CPU-Based MLLP mini-project for chart and infrographics text summarization using EasyOCR and FLAN-T5-small.
# Chart-to-Text Summarisation

**MLLP Mini-Project | KIIT University | B.Tech ECSc**

## 1. Project Overview

Chart-to-Text Summarisation is an NLP application that extracts textual information from bar charts, pie charts and infographics and generates concise natural-language summaries.

## 2. Technologies Used

- Python
- Google Colab / Jupyter Notebook
- EasyOCR
- Hugging Face Transformers
- Google FLAN-T5-small
- PyTorch
- Pillow
- Pandas and NumPy
- Matplotlib

## 3. Processing Pipeline

Image Upload → Image Preprocessing → OCR → Structured Data Verification → Data Analysis → FLAN-T5 Summarisation → Text Output.

## 4. How to Run

1. Open `notebooks/Chart_to_Text_CPU.ipynb` in Google Colab.
2. Select CPU as the runtime.
3. Run the installation cells.
4. Upload a chart image.
5. Run OCR extraction.
6. Verify the extracted category-value pairs.
7. Generate the natural-language summary.
8. Download the JSON and TXT results.

## 5. Pretrained Models

- EasyOCR: [https://github.com/JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)
- FLAN-T5-small: [https://huggingface.co/google/flan-t5-small](https://huggingface.co/google/flan-t5-small)

## 6. Repository Structure

- notebooks/: Jupyter implementation.
- src/: Python source code.
- data/: Sample chart images.
- outputs/: Generated summaries and JSON results.
- docs/: Processing pipeline and documentation.
- report/: Project report.
- presentation/: Presentation slides and video.

## 7. Limitations

CPU is slow, so a lot of features are made simple so we can run the Model

GPU is better for running this Project.

OCR may incorrectly recognize labels or values. Category-value relationships require verification, particularly for unfamiliar chart layouts and complex infographics. The system therefore includes a verification stage.

## 8. Author

Henrique Helder Bila
B.Tech Electronics and Computer Science(ECSc)
KIIT University, India

## 9. Academic Note

Individual project submission
