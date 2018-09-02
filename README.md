# ipythonPresentation

## Creating Presentation using iPython notebook

### Tools required
1. jupyter
2. Markdown
3. reveal.js

Step1#
## Open Jupyer 

1.1 cd Documents/myProjects/Presentations/
1.2 source ~/.bash_profile
1.3 jupyter notebook

Step 2#
## Download Reveal.js

2.1 git clone https://github.com/hakimel/reveal.js

Step 3#
## Set Anaconda / Python Home path or use fully qualified address

3.1 Create a new iPython notebook 
3.2 Use Slide Style = Slide
3.2 Code Type = Markdown
3.3 Save & Checkpoint the notebook

Step4#
## jupyter-nbconvert to convery the ipython notebook to html page

4.1 /Users/pmitra/anaconda3/bin/jupyter-nbconvert --to slides MyPresentation.ipynb --reveal-prefix=reveal.js

Step 5#
Open the notebook

5.1 open ./MyPresentation.slides.html

:wq

