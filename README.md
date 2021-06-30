1. create new environment - conda create -n mlops python=3.7 -y

2. activate the environment - conda activate mlops

3. create requirements.txt - touch requirements.txt
open requirements.txt and write - 
dvc 
dvc[gdrive]
sklearn

4. Install the requirements.txt - pip install -r requirements.txt

5. make a file template.py - touch template.py and then add the content in it for the structure of your model

6. Then make a folder data_given - mkdir data_given

7. In the data_given folder add your data.csv file

8. git init

9. dvc init

10. dvc add data_given/winequality.csv

11. git add .

12. git commit -m "First commit"

13. create an empty repo on git

14. git remote add origin https://github.com/Tanishkaagarg/DVC-Demo.git

15. git branch -M main

16. git push -u origin main

17. tox command - tox

18. for rebuilding - tox -r 

19. pytest command - pytest -v

20. setup commands - pip install -e . 

21. build your own package commands- python setup.py sdist bdist_wheel

22. Install jupyter notebook for testing - pip install jupyterlab 