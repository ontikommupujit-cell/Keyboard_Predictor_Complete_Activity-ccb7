KEYBOARD PREDICTOR: COMPLETE ACTIVITY (teacher copy, contains the solution)

What is in this folder
- predictor.py      : the full working solution.
- predictor_app.py  : the Gradio web page (step 8). It uses predictor.py.
- requirements.txt  : gradio and a recent jinja2 (needed only for the web page).
- books/            : alice.txt and sherlock.txt (public domain, from Project Gutenberg).

Setup
1. Python 3.10 or newer.
2. For the web page:  pip install -r requirements.txt

Run
- The program:   python predictor.py        (Windows: py predictor.py)
- The web page:  python predictor_app.py    then open http://127.0.0.1:7860

Expected results (teacher): Alice has 26776 words and 2636 different words, Sherlock 105285 and 7945. The greedy sentence from "alice was" is the same every time. The random one changes.
Do not share this folder with students: the boilerplate zip is the student copy.
