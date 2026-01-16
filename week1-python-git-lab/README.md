Average Tip by Day

Dataset Chosen
Name: Tips 
URL: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv  

How to run (copy/paste commands)
uv venv
uv init
uv add pandas matplotlib
.venv/Scripts/activate
uv add requests
python analyze.py
uv pip freeze > requirements.txt

What it does
prints dataset summary (rows/cols, columns list, first 5 rows, grouped averages)
generates output/chart.png

Reflection (3–5 sentences)
What was the hardest part?
We found working with the command line to be a challenging part of this activity. As we are more accustomed to graphical user interfaces, accessing the features of the virtual environment (working with uv) and working with git became more difficult to grasp at first.
What did you learn about Git commits (small commits, staging, meaningful messages)?
Git commits benefits the group by serving as a form of documentation. As we use Git to work collaboratively, it is important for us to properly enumerate the actions done on the workspace to update one another on the progress made.
