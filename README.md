<div align="center">
  
# PDF Based Generative AI Quiz Maker <br> (PDF 수업자료 기반 생성형 AI 퀴즈 메이커)
<br>

## With the use of Ollama Gemma2, you can study efficiently just by uploading a PDF file!
</div>
<br>

### Open Source Libraries Utilized:
- Fitz (PyMuPDF)
- PyQt5
- Ollama (Gemma 2)
- Random
- Nltk
- LangDetect
- OS
<br>

### Summary of Process
- Choose and upload your **"Korean" or "English PDF file** to the program (**Best: Word file converted to PDF**, Warning: Avoid using image-based pdf like PPT exported as a PDF).
- **Enter the page number** of the page you want to focus on (only this page will be used for question generation). 
- PyMuPDF reads and **extracts text** from the chosen file.
- The extracted text is used as **input for Ollama Gemma2** to summarize into 5 sentences
- Said sentences are randomly chosen to be **"True (O)" or "False (X)"**
- If a sentence is chosen to be false, Gemma2 will change details in the sentence and generate a "false statement"
- **5 O-X Questions** are displayed on the screen - you can answer them by pressing the buttons (the color of the button doesn't change even if it's clicked - **if you click it, it is clicked even if it doesn't show**)
- After answering all the questions, a pop-up notification will show you **your score**.
<br>

<div align="center">
  
## Good Luck On Studying! 열심히 공부하세요!
</div>
