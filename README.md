# Project Title: AI-Powered-Study-Notes-Generator

# Description:
Students often struggle to efficiently extract key points and prepare study materials from lengthy lecture notes or documents. This project aims to automatically generate summarized notes, flashcards, and quizzes from PDF, DOCX, or PPTX files to simplify learning.

# Technologies:
| Component             | Tool / Library                                    | Purpose                   |
| --------------------- | ------------------------------------------------- | ------------------------- |
| Backend               | Flask                                             | Web framework             |
| File Parsing          | PyPDF2, python-docx, python-pptx                  | Extract text from files   |
| NLP                   | Hugging Face Transformers (`distilbart-cnn-12-6`) | Summarization             |
| Frontend              | HTML + Bootstrap                                  | Simple UI                 |

# Features:
1. User uploads PDF, DOCX, or PPTX file.

2. Automatic text extraction from uploaded files.

3. Summarization using Hugging Face Transformers.

4. Flashcards generation for key points.

5. Simple multiple-choice quiz generation.

6. Web interface built using Flask and Bootstrap.


