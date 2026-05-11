# AI Quiz Generator and Text Summarizer

AI Quiz Generator and Text Summarizer is an AI-based educational web application that helps students generate interactive quizzes and summaries from Arabic or English text.

## Features

- Generate quiz questions from study text.
- Support Multiple Choice and True/False questions.
- Check answers interactively.
- Show the final quiz score.
- Summarize text into short summary, main points, and keywords.
- Support Arabic and English.
- Professional Gradio user interface.

## Technologies Used

- Python
- Gradio
- Groq API
- LLaMA 3.1
- Google Colab
- JSON
- HTML and CSS

## How to Run

Install the required libraries:

```python
!pip install -q gradio groq

Connect the Groq API key:
from google.colab import userdata
from groq import Groq

api_key = userdata.get("GROQ_API_KEY")

if not api_key:
    raise ValueError("GROQ_API_KEY is missing. Add it in Colab Secrets.")

client = Groq(api_key=api_key)

How to Use
	Quiz Generator
	Paste the study text.
	Choose the question type.
	Select the number of questions.
	Click Generate Smart Quiz.
	Choose an answer.
	Click Submit Answer.
	Click Next Question.
	View the final score.
Text Summarizer
	Open the AI Summarizer tab.
	Paste the text.
	Click Generate Summary.
Limitations
	The system requires an internet connection.
	The system requires a valid Groq API key.
	The quality of questions depends on the quality of the input text.
	The AI output may sometimes need minor review.
Future Improvements
	Save quiz results.
	Export questions to PDF or Word.
	Add difficulty levels.
	Add file upload support.
	Add student progress tracking.
Conclusion

	This project helps students study more effectively by converting text into quizzes and summaries using artificial intelligence.
