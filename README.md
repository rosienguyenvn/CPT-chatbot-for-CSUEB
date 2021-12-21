# CPT-chatbot-for-CSUEB
A deep learning project using Python and Flask
Built a chatbot for answering all questions about CPT for Cal State East Bay
A video of the web app interaction

https://loom.com/share/6ed5849db9024fa6af08b0d90f0e0605

Inside your working directory you should have the following files:
|
|______ static
|          |______ jquery.min.js
|
|______ templates
|           |______ index.html
|
|____ app.py
|____ chatbot.py
|____ job_intents.json
|____ processor.py

Job_intents.json contains information getting from CSUEB website: 
https://www.csueastbay.edu/cie/f-1-students/employment/cpt-curricular-practical-training.html
CPT Handout:
https://www.csueastbay.edu/cie/files/docs/pdfs/employment-handouts/cpt-handout.pdf
CPT Tutorial: https://www.csueastbay.edu/cie/files/docs/pdfs/employment-handouts/cpt-tutorial.pdf

The order of code run:
chatbot.py ->  processor.py ->  app.py
Platform using to run the py file is Pycharm
