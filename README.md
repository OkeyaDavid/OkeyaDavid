## Hi, I'm David

Third-year Computer Science student at Toronto Metropolitan University, graduating
April 2028. I like problems where the answer has to hold up to a follow-up question,
so most of what I build ends in a decision and a number rather than a chart.

Looking for a **Summer 2027 internship** in data, analytics or software engineering.

### What I've shipped

**[Loan Default Risk & Approval Tool](https://github.com/OkeyaDavid/loan-default-risk)** ·
[live app](https://credit-loan-default-risk.streamlit.app)

Scores an applicant's probability of default, explains each decision in plain English
with SHAP, and prices every approval policy in dollars. ROC-AUC 0.767 on 76,878
held-out applicants. The model is not the interesting part: approving the safest 86%
instead of everyone holds defaults among approved loans to 5.30% against 8.07% and
avoids $632.8M of expected loss. Age and gender are excluded deliberately, and the
cost of excluding them is measured and written down rather than assumed away.

`Python` `LightGBM` `scikit-learn` `SHAP` `Streamlit`

**[Canadian EV Adoption Dashboard](https://github.com/OkeyaDavid/canada-ev-adoption)** ·
[live app](https://canada-ev-adoption.streamlit.app)

Tracks zero-emission vehicle registrations by province across 38 quarters of Statistics
Canada data, 8.1 million rows. The build refuses to run if it cannot reproduce StatCan's
published totals exactly. The four-quarter forecast is back-tested against a naive
baseline, and since it only wins in Ontario, the dashboard says so on the page instead
of hiding it.

`Python` `pandas` `SQL` `SQLite` `Plotly` `Streamlit`

### Working with

Python, SQL, Java, C, Lisp, Bash, Git. Currently deeper into model evaluation,
calibration and the parts of machine learning that decide whether a number can be
trusted.

### Also

I shoot and edit video as [Ozii](https://oziithecreator.com), and I built that site by
hand. It is the reason I care about load time and about writing for someone who is
not technical.

### Reach me

[LinkedIn](https://www.linkedin.com/in/okeyadavid) · davidokeya04@gmail.com
