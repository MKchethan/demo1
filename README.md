```bash
requirements file 

touch requirements.txt
pip intsall -r requirementrs.txt
```


touch README.md

```bash
creating directiories and files
touch template.py
python template.py
```


mkdir data_given

```bash 
intializing git and dvc
git init
dvc init
dvc add data_given/BankNote_Authentication.csv
```

```bash 
To keep track of our code
git add .
git commit -m "first commit"
```

```bash
Adding origin
git remote add origin https://github.com/MKchethan/demo1.git
git branch -M main
git push -u origin main
```

```bash 
git add . && git commit -m "parameters added" && git push origin main
```

```bash 
touch src/get_data.py
dvc repro
git add . && git commit -m "get_data added" && git push origin main
```

```bash
touch src/load_data.py
dvc repro
git add . && git commit -m "load_data added" && git push origin main
```

```bash
touch src/split_data.py
python src/split_data.py
dvc repro
git add . && git commit -m "load_data added" && git push origin main
```

```bash
touch src/train_and_evaluate.py
python src/train_and_evaluate.py
dvc repro
git add . && git commit -m "trained and evaluated" && git push origin main
```

tracking reports 
```bash
mkdir report
touch report/params.json
touch report/scores.json
```

tracking added
```bash
dvc repro
dvc params diff
dvc metrics show
dvc metrics diff
```

```bash
touch setup.py
pip install -e .
git add . && git commit -m "setup done" && git push origin main
```

intsall jupyter notebooks
```bash
pip install jupyterlab
jupyter-lab notebooks/
```

After train and evaluate stage
```bash
mkdir prediction_service\model
mkdir webapp
touch app.py
touch prediction_service/__init__.py
touch prediction_service/prediction.py
mkdir webapp\static\css
mkdir webapp\static\script
touch webapp/static/css/main.css
touch webapp/static/script/index.js
mkdir webapp/templates
touch webapp/templates/base.html
touch webapp/templates/index.html
touch webapp/templates/404.html
```

```bash
git add . && git commit -m "web structure added" && git push origin main
```

copying the model.joblib from saved models to prediction_service
```bash
cp saved_models/model.joblib prediction_service/model
```

