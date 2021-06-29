1. create new environment - conda create -n mlops python=3.7 -y

2. activate the environment - conda activate mlops

3. create requirements.txt - touch requirements.txt
open requirements.txt and write - 
dvc 
dvc[gdrive]
sklearn

4. Install the requirements.txt - pip install -r requirements.txt

5. git init

6. dvc init

7. dvc add data_given/winequality.csv

8. git add .

9. git commit -m "First commit"

10. 